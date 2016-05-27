Ansible - Postfix Relaying
==========================

This is a very basic module for deployment on Ubuntu systems to configure
Postfix for authenticated SMTP relaying via an external service.

* The default relay server is Sendgrid.
* Port 587 for submission is hardcoded in the main.cf template.

Sample configuration:
---------------------

    postfix_relayhost_user: "username"
    postfix_relayhost_pass: "password"
    postfix_relay_server: "fqdn"
