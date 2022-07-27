# Udacity Cloud DevOps - Course 02 - Final Project

## Project Plan and Task Tracking
- [Project plan spreadsheet](https://docs.google.com/spreadsheets/d/1p29UxxCbZ4jmfiDiYAPbk6N9hc05gtVK5Gno8hvmO3c)
- [Task tracking Trello board](https://trello.com/b/iziwVR8V/build-a-ci-cd-pipeline)

## Azure Cloud Shell
- ![GitHub project cloned on Azure Cloud Shell](screenshots/azure-cloud-shell-project-clone.png)

## Setup
1. Create a Python virtual environment:
    ```sh
    python3 -m venv ~/.udacity-cloud-devops-c02-final
    ```

1. Activate the virtual environment:
    ```sh
    source ~/.udacity-cloud-devops-c02-final/bin/activate
    ```

## Install, Lint and Test
1. Run install, lint and tests:
    ```sh
    make all
    ```

    The result should look like that:
    ![Azure Cloud Shell - Make All command result](screenshots/azure-cloud-shell-make-all.png)
