# Docker works by default if you add a docker file to the root of the project.
- Still not getting docker management to work.


# Tailscale manual user auth 1/2

Just add 

(https://github.com/tailscale/codespace)[https://github.com/tailscale/codespace]
    
    "runArgs": ["--device=/dev/net/tun"],
    "features": {
      "ghcr.io/tailscale/codespace/tailscale": {
        "version": "latest"
      }
    }

and the run 'sudo tailscale up' in the terminal. It will ask you to authenticate and you are good to go.

# Tailscale key automatic auth 2/2

.devcontainer has build in auth key place and you need to add auth key to github secrets.


![Codespaces secrets](/images/Codespaces_secrets.png)

# Docker non root / Vscode docker management broken

https://code.visualstudio.com/remote/advancedcontainers/add-nonroot-user

![Docker is still broken](/images/Docker-broken.png)