Hello!

This is creates a django environment locally to help get linux apache Postgres and Django env up for development.

mainsite: folder under which Django files will fall under so docker container files can be easily edited
starting_template: mainsite, but unedited and working for the current environment
*docker: this dir is not included, but should be "docker/djanaconda-container" which actually houses the djanaconda setup.
download the djanaconda container from here: https://github.com/ejortiz/djanaconda-container