
# Issue Tracker

Build the website to create a project and also create the issue of the project


## Installation

Install my-project with npm

```bash
  git clone https://github.com/oathira/Issue-Tracker.git
  npm install
  cd Issue_Tracker
```
    
## Running Tests

To run tests, run the following command

```bash
  npm start
```


## Folder Structure

* assets
    1. css
        - footer.css
        - header.css
        - home.css
        - issue_page.css
        - layout.css
        - project_page.css
    2. images
    3. js
        - delete_issue.js
        - delete_project.js
        - filterIssue.js
        - searchIssue.js
* config
    - middleware.js
    - mongoose.js
* controllers
    - home_controller.js
    - project_controller.js
* models
    - create_issue.js
    - create_project.js
* routes
    - index.js
    - project.js
* views
   1. partials
        - _footer.ejs
        - _header.ejs
        - _issue_form.ejs
        - _issue_page.ejs
        - _project_form.ejs
    - home.ejs
    - layout.ejs
    - project_page.ejs
- .gitignore
- index.js
- package-lock.json
- package.json

Home Page
Show a list of projects.
Give a button to create a new Project (On creating a new project it should appear in the list)
Create Project Page
Accept the following fields to create a project
Name
Description
Author
Project Detail Page
When the user clicks on a project (in home page) redirect the user to this page which will show bugs related to this project
User should be able to perform following actions on this page
Filter by multiple labels i.e. I should be able to filter by 2 or more labels at the same time
Filter by author
Search by title and description
A button to create an issue
Create issue page
User should be able to create an issue for a project
Accept the following fields
Title
Description
Labels (multiple labels can be added to a project, IF a project has a label already show it (in dropdown) as the user types the label in)
Author




