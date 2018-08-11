# djelper 

### Installation

Download and put in your path.



### How to use

With one single command djelper opens the project folder, activates the virtual environment, opens your code editor, starts the django server and opens it in your webrowser:

`$ djelper projectname`



### Folder structure

djelper assumes you keep your django projects and virtual environments in a certain structure: 

- ~/home
  - /Development
    - /myproject          <-- parent folder with the same name as django folder
      - /myproject           <-- normal django project folder
        - manage.py
        - /myproject 
      - /env_myproject      <-- virtual environment lives here 
