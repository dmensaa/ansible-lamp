## LAMP Stack Deployment

- Expects CentOS or Ubuntu hosts

These playbooks deploy a simple all-in-one configuration for a LAMP stack.
Apache, MySQL, PHP. To use, edit the `hosts` file to include the names or
URLs of the servers you want to deploy.

Then run the playbook, like this:

    ansible-playbook -i hosts site.yml

The playbooks will configure Apache, MySQL, PHP. When the run
is complete, you can hit access server to begin the WordPress configuration.