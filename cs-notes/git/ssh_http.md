### SSH vs HTTPS

SSH and HTTPS both are methods to connect the local machine to a remote repo

- SSH (Secure Shell)
    - A protocol used for secure remote access and authentication
    - Used in Git via SSH keys

- SSH Pros
    - Better security compared to HTTPS
    - Uses public-key cryptography which enhances authentication security
    - Streamlines authentication process

- SSH Cons
    - Setting up and managing SSH keys may be more complex
    - Communication may be restricted by firewall

- HTTPS (Hyper Text Transfer Protocol Secure)
    - A protocol used for secure communication over the web
    - Used in browsers and Git via tokens

- HTTPS Pros
    - More straightforward setup compared to SSH
    - Authenticate with an username and password or with a personal access token if using GitHub
    - More compatible with firewalls

- HTTPS Cons
    - SSH is considered more secure
    - User may need to enter their credentials frequently <br />
        Credential caching tools may be used to avoid this issue <br />
        Windows - Credential Manager <br />
        Mac - Keychain Access
