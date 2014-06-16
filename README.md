honeypots
=========

Install different honeypot software using Ansible.

Snort (snort-base.yml)
======
 * Install Snort
 * Install mysql and load schema
 * Load community rules
 * Install Base a web front end for snort
 * Web ui is accessible on http://<ip>/base
 * Configure the admin password in the playbook
 * You can test it by running a nmap scan against the host


Artillery (artiller.yml)
======
 * Install https://github.com/trustedsec/artillery
 * This the tarball is copied to the right folders and a service is installed

