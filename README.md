# openshift-templates
Different templates for openshift

# wordpress-mysql-ephemeral.json
Create template with oc create -f wordpress-mysql-ephemeral.json
Point to a git repo containing wordpress, https://github.com/johwes/WordPress.git
The only difference in that repo is the file wp-config.php which contains the necessary "code" to fetch the config from env variables.
