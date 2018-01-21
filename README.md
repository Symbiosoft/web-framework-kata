# web-framework-kata
**Web Framework Kata** is a way to evaluate different Web Frameworks by hands-on
experimentation (aka "kicking the tires"). A classic *TODO list* web app is used
in all the katas, we will improve that app iteratively. The katas are framework
agnostic, and therefore they should be doable using any existing web framework,
or programming language.

## How to use this repo
If you want to try the Web Framework Kata, first fork this repo. Then, I suggest
that you start a new branch from the `master` branch named against the web
framework you are going to evaluate, for example:

- `git clone git@github.com:your-github-user/web-framework-kata.git`
- `cd web-framework-kata`
- `git checkout master` # Just to make sure we branch from `master`
- `git branch django`
- `git checkout django`

Next, at your choice, you can create a separate branch for each kata, tag your
branch before starting a new kata (to be able to go back later), or whatever you
see fit with your personal coding workflow.

## How to contribute
To contribute:

- fork this repo
- make your changes on the `develop` branch
- submit a pull request with your changes
- once reviewed, your changes will be merge on the `master` branch

## Katas

### 0 - Setup the work environment

This kata is not really a coding kata, but is still essential.  You should
be familiar on how to get the environment right on your OS of choice for the
web framework you are going to evaluate.

### 1 - Create an new app, running the app server

Using the framework tools, create the `todo-list-app`. By the end of this kata,
you should be able to start a local server, visit the app (blank) web page at
`127.0.0.1:FRAMEWORK_PORT/`

#### Objectives

Get familiar to the process of creating a new web app with the framework. It may
or may not imply some configuration to get the routing working. Do only the
minimum to get the local server up and running, this kata should be done fast.
If your framework propose to generate test helpers / squeleton, let it do it for
you as we will use test driven development (TDD) in the next katas.

### 2 - Create a data model

### 3 - Populate the todo list with data

### 4 - Show all todo items

### 5 - Creating new todo items

### 6 - Editing existing todo items

### 7 - Deleting existing todo items

### 8 - Create a restful API

### 9 - Add filters to the todo list

### 10 - Supporting more than one todo list

### 11 - Add "priority" criteria

### 12 - Add "category" criteria

### 13 - Securing the application
