# openapi-generator-validate
Github sample workflow to run openapi-generator validate on a openapi yaml spec file

To use:
- checkout the repo
- copy validate-openapi.yml to your repository .github/workflows folder
- edit&customize validate-openapi.yml, in particular:
    - update the "name" to reflect that you are checking
    - update the "paths" to monitor for changes
    - update the docker-entrypoint input file to be checked
- rename validate-openapi.yml to something cool
- checkin the changes

