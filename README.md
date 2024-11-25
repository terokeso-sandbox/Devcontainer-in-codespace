# Welcome to MkDocs + Material + Devcontainers

This a a test site for MkDocs + Material + Devcontainers. Goal is to have a working setup for a documentation site that can be run in a devcontainer, GitHub Codespaces or locally. Basic goals are: 

1) You can have documentation site that runs like normal Github pages site. This template uses Material for MkDocs theme.

2) You can run Vscode WEB editor and read the documentation in the same browser window. Vscode has been pre-configured to work with the devcontainer and mkdocs.

3) You can start local VSCode or use Github Codespaces to run code that is linked to the documentation. This open possibilities to have documentation, code and lab environment in the window. 

Courses that could be used to build this setup:

* Basics of Linux
* Basics of Python
* Basics of Docker
* Basics of Kubernetes (K3s and K3d)
...


Devcontainer settings are in `/.devcontainer/devcontainer.json` and Vscode default settings `/.vscode/settings.json`

Devcontainer has been modify to be able to update MkDocs site, run docker and Tailscale. Tailscale is used to connect to the lab environment with stable ip address and DNS name. Tailscale is not needed in normal setup just dynamic content that need stable ip or dns name.




