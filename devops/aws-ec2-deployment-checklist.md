# AWS EC2 Deployment Checklist

### Must Have

- [] Use the lastest AMIs (Latest Amazon Linux or Ubuntu)
- [] Use the newest instance Type (eg. t4,t3)
- [] Don't use the default vpc
- [] Allocate minimum storage of 20GB
- [] Configure security group to allow full access on 80 and 443
- [] Configure security group to allow specific ip address to access on 22
- [] Use new keypair for each instance
- [] Use the latest versions of the installed packages (eg. Nginx, MySQL, PHP, Apache)
- [] Never use the root user to perform any actions
- [] Enable mod rewrite if using the Apache
- [] Enable followsymlinks if using the Apache
- [] Use the Let's Encrypt to secure the website
- [] Limit request size in the web server
- [] Add security headers in the web server
- [] Setup correct file permission for the project code
- [] Setup MFA for the IAM user
- [] Create seperate IAM user for application access and disable console access

### Must Have (Has some cost associated with it)

- [] Use elastic ip address
- [] Setup backups
- [] Autoscaling group
- [] Make s3 bucket private and use cloudfront for serving static assets
- [] Use firewall to protect against the bot

### Optional

- [] Setup uptime monitoring
