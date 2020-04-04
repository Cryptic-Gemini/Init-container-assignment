# Init-container-assignment
                                  
                                  Assignment for init containers

Preview:
--------
At times you may want to do some pre-work for a container before starting it. That pre-work could be done by another container, which would do it's thing and exit before the main container starts. One example could be that you want to serve some static website content which exists as a git hub repository. So you would want something to pull that static content and provide it to the web server. This is called init-container.

Task:
-----
You are required to make a multicontainer pod (initcontainer & nginx) in which one container will pull the static content and other will serve that content.Init-container will pull the static website from github. The website exists as git repository at https://github.com/Cryptic-Gemini/Init-container-assignment.git, we want to serve it through the nginx service.

==> Share your yaml file.
==> Share the screenshot of running Pod.
==> Share the screenshot of Application running at port 7000. 
