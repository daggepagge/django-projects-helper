# djelp

Bash script that helps opening and switching between PHP and django projects (and their virtual environments).

With one single command djelp will:
- activate the virtual environment for the project
- launch the project folder in your favourite code editor
- open the project folder in finder
- start up the django dev-server
- open the project in your webrowser

if the project is not a django project but a PHP project djelp will:
- launch the project folder in your favourite code editor
- open the project folder in finder
- start up a local PHP server
- open the project in your webrowser

if the project is neither django nor PHP, djelp will:
- launch the project folder in your favourite code editor
- open the project folder in finder

### Installation

Download and put in your path.


### How to use


`$ djelp projectname`



### Folder structure

djelp assumes you keep your django projects and virtual environments in a certain structure:

- ~/home
  - /Development
    - /myproject        *<-- parent folder with the same name as django folder*
      - /myproject          *<-- normal django project folder*
        - manage.py
        - /myproject
      - /env_myproject      *<-- virtual environment lives here*

### Contributing

I would appreciate any help making djelp better!
