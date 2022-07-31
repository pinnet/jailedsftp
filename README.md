# A jailed ssh user for sftp  

### Usage

    docker run -p 8022:22 -v [path-to-ftpfiles]:/var/jail/home/{SSH_USER} dannyarnoldcom/jailedsftp:latest

### Environment overrides

 - SSH_USER=sshjail
 - SSH_PASS=sshjail
 - AUTH_KEY=[authorized key]
 - SSH_SHELL=/usr/bin/nologin
 - BANNER={local_filename_of_banner_text}
### Repository

<https://github.com/dannyarnoldcom/jailedsftp.git>

License MIT
