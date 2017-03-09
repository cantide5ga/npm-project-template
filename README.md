Creating a new npm project
-----
1. ```git clone git@github.com:aquicore/npm-project-template.git | https://github.com/aquicore/npm-project-template.git <new_project_name>```
2. cd into <new_project_name> and ```npm run init```
3. Create project in your git manager (e.g. Github, Gitlab) or ```git init --bare``` in remote dir 
4. ```git remote add <shortname> <url>``` corresponding to repo in step 3 above e.g. ```git remote add origin git@github.com:<namespace>/<project_name>.git```, ```git remote add origin ssh://some.url.net/path/to/repo```
5. Be sure to also manually edit package.json's description, update LICENSE.md, and edit this README as appropriate.

Starter Commands
-----
*npm run init*
Used with a new project to hit the ground running: installs all dependencies and initializes a git repo

*npm run build*
Creates the dist/ and compiles Typescript into build/

*npm run clean*

*npm test*
Compiles code, runs unit tests, and reports on coverage enforcing thresholds
