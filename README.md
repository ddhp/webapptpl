### Introduction:

  This is a template of web application, see following colomns
  to know details.

### Scheme:

The structure is like:

  * lib: required libraries 

  * src: all coffee and template files here 
    - initialize.coffee: all magic happens from here
    - models: put all model here
    - controllers: name of the folder is controller's name
        - templates: .handlebars for related controller

  * less: all less file for styling templates
    - bootstrap: git cloned bootstrap lib less files
    - main.less: import required less files, and generate main.css

  * server: service and controllers for node server

  * test: test cases
    - casper: capserjs for integration test
    - server: mochajs for server

  * GruntFile.coffee: for task manager
  * package.json: npm modules

### Database:

  Data including images, texts are stored at database,
  and fetched through provided api
