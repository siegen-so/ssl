# ssl
A collection of shell-script to automate handling of letsencrypt-certificates.
It can be used to manage
 - domains & subdomains
 - certificate issuance
 - insertion of certificates into the webserver-config
 
## Installation
It is recommended, that this collection of scripts has its own user `ssl`.

1. Clone this repo into the new user's home-directory.
2. Copy `config.sh.example` to `config.sh`.
3. Modify `config.sh` for your needs.
4. Clone [letsencrypt.sh](https://github.com/lukas2511/letsencrypt.sh) into `letsencrypt.sh` or set the path accordingly.
5. -- TODO: Shell-scripts --
6. Check out [script-usage](#usage).
