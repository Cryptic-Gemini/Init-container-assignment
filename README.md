# Init-container-assignment
                                  
                                PIAIC-Faisalabad-Kubernetes-Assignment-02

Preview:
--------
At times you may want to do some pre-work for a container before starting it. That pre-work could be done by another container, which would do its thing and exit before the main container starts. One example could be that you want to serve some static website content which exists as a git hub repository. So you would want something to pull that static content and provide it to the web server. This is called init-container.

Task:
-----
You are required to make a multicontainer pod (initcontainer & nginx) in which one container will pull the static content and other will serve that content.Init-container will pull the static website content from GitHub. The website exists as git repository at https://github.com/Praqma/simple-website.git, we want to serve it through the nginx service.

Note: It's just for practice.

==> Make your yaml file.

==> See your Pod in running status

==> Make your Application running at port 7000. 
    (kubectl port-forward pod-name 7000:80)
