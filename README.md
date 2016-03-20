# openshift-templates
Different templates for openshift

# wordpress-mysql-ephemeral.json
Create / define the template within openshift, oc create -f wordpress-mysql-ephemeral.json .

Create a new application from the template. Point to a git repo containing wordpress, https://github.com/johwes/WordPress.git
The only difference in that repo is the file wp-config.php which contains the necessary "code" to fetch the config from env variables.


