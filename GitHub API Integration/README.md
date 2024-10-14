# GitHub API Integration
## Project Overview

In this project, I utilized a shell script to interact with the GitHub API, specifically to list users who had read access to a specified repository. The script automated the process of checking collaborator permissions, which is a common task for DevOps engineers. The script was developed using references from the official GitHub documentation.

## GitHub API

The GitHub API allowed programmatic access to GitHub features, enabling me to retrieve and manipulate repository data without using the web interface. I used curl to send HTTP requests to the API endpoint

## Personal Access Token (PAT)

I generated a PAT from my GitHub accounts settings under Developer settings > Personal access tokens. I ensured that it had the necessary scopes, particularly repo, for accessing private repositories.

## Shell Scripting

I created a Bash script to automate tasks related to the GitHub API. The script was organized into functions for better readability and maintainability

## Setup Environment

Ensuring that my Unix/Linux environment had curl and jq installed.
curl: A command line tool for transferring data with URLs
jq: A lightweight command line JSON processor used to parse and filter JSON data

Setting up a VM through MOBAXTERM connected to EC2 (AWS) since my machine is windows.


## Create Personal Access Token

Navigated to my GitHub account settings and generated a new token with the repo scope.

## Script file

Created a new file named list_users.sh

## Making the script executable

Changing permissions using 'chmod'

## Executing the script

Gave access to my repo manually to one of my friend to confirm the functionality of the script.
Later on executing the script reveals the list of people who have read access to the mentioned repository.

## Conclusion

This project demonstrated how I automated tasks related to mangaging repository access using shell scripting and the GitHub API. By following these steps, I effieciently managed colloborators without manually navigating through the GitHub web interface. The script was devloped using references from the official GitHub documentation, ensuring that I adhered to best practices