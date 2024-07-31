# Self Managed Cloud Hosting Deployment Checklist

### Must Have

- [] Use the lastest OS (Ubuntu)
- [] Configure firewall to allow full access on 80 and 443
- [] Configure firewall to allow specific ip address to access on 22
- [] Use new keypair for each instance
- [] Use the latest versions of the installed packages (eg. Nginx, MySQL, PHP, Apache)
- [] Never use the root user to perform any actions
- [] Enable mod rewrite if using the Apache
- [] Enable followsymlinks if using the Apache
- [] Use the Let's Encrypt to secure the website
- [] Limit request size in the web server
- [] Add security headers in the web server
- [] Setup correct file permission for the project code
- [] Setup MFA

### Must Have (Has some cost associated with it)

- [] Setup backups

### Optional

- [] Setup uptime monitoring
