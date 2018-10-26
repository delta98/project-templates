# Project Title
Please outline the main purpose/core features of the project in one paragraph.
## Interactions with other repos
* Use bullet points to describe any ways this project is reliant or relied upon by other in-house services.
* be extra helpful and add links to repos

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
### Prerequisites
You will need to have these installed before moving onto the `installing` section.  
 - **package name** - link to docs if possible
 - **package name** - `$ npm install command`
 
### Installing
A step by step series of examples that tell you have to get a development env running
Say what the step will be
```
Give the example
```
And repeat with as detailed as relevant and useful.
```
until finished
```
If this section involves a lot of steps, think about creating a `setup.sh` file that can be ran instead (this can be a useful way to document the process as well as speeding up the process for your fellow developers.
 
### Config
All the configuration for this project lives here: `/path/to/config/dir`
## Commands
* `npm run COMMAND_NAME` - add a short description
## Running Tests
Test scripts live here `path/to/tests`
To run tests: `npm run test`
To run test coverage: `npm run test:coverage`
This project aims to exceed **75%** test coverage.
### Development Notes
This project follows [Git Flow](http://datasift.github.io/gitflow/IntroducingGitFlow.html). 
    
### Deployment / Versioning
Deployments are handled by kubernetes, the config lives `path/to/deployment-scripts`
When deploying to *Production*:
1. Update and commit CHANGELOG.md
2. `git tag v1.0.0` Add git tag in this format.
<update this if there a specific format that triggers a certain type of build>
3. `git push origin master --tags` Push
### Dependancies
* library-name - used for this and that
* Mention databases used
* Mention libraries used for features including things like caching, image processing etc
### Gotchas
* This **build error** occurs sometimes. To reset the project files run: 
1. `this` and 
2. `that`
* e.g. explain steps for **clearing cache**
