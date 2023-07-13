## Getting started
# Restaurant App Backend

This is the backend API for a restaurant app built using the Godspeed Framework. It provides REST API endpoints to manage restaurants, menu items, and orders. The API is built with Node.js and uses a PostgreSQL database via the Prisma ORM.

## Getting Started

To set up and run the project locally, follow these steps:

### Prerequisites

Make sure you have the following software installed on your machine:

- NVM with Node LTS (16+) - [Install NVM](https://github.com/nvm-sh/nvm)
- Visual Studio Code LTS with the following extensions:
  - Remote Containers
  - Run on Save
  - Godspeed Extension Pack
- Docker Desktop - [Install Docker](https://www.docker.com/products/docker-desktop)

### Installation

. Install the Godspeed CLI globally:
 npm install -g @mindgrep/godspeed

To create a new project, run:
godspeed create my_test_project AND RUN 
cd <your_git_repo>
CHANGE TO PROJECT DIRECTORY
cd <your_project_directory>

Open Visual Studio Code from the project directory:
code .


Open the project in a development container:

Click on the Remote Containers tray icon.
If it's your first time, click on "Open folder in Dev Container".
For subsequent times, click on "Re-open in Dev Container".
Build the project:
godspeed build

 install PRISMA in your container.

 #set the database AND after 
 godspeed gen-crud-api
 after run
godspeed gen-test-suite
CLI: You can use below command to run the test suite from CLI.
godspeed test
                                                    _ 




The fastest way to get started with Godspeed is by following the [Godspeed documentation](https://docs.mindgrep.com/).
