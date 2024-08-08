#GPT-GitHub Integration Helper
This repository contains example files and documentation to help you integrate a GPT-powered AI assistant with GitHub using the n8n automation platform.
Overview
The goal of this project is to enable a GPT assistant to directly manage and automate tasks within your GitHub repositories. By leveraging the n8n automation platform, we can create secure workflows that allow the AI agent to execute actions like file creation, deletion, and updates on demand.
The key components include:

##OpenAPI Documentation Example: A sample OpenAPI specification that defines the structure of the GitHub API actions your GPT assistant will need to understand.
n8n Workflow Templates: Example n8n workflow configurations that demonstrate how to set up GitHub-specific automations.
Configuration Guidelines: Instructions on how to properly configure your GPT assistant's instructions and link it to the n8n server for seamless integration.

##Getting Started
To get started, review the example files and documentation provided in this repository. You'll need to have a working n8n server set up beforehand, which you can do by following the n8n installation guides.
Once your n8n server is ready, you can use the resources here to configure your GPT assistant to communicate with n8n and execute GitHub-related tasks. The OpenAPI example and workflow templates should serve as a helpful starting point.

#EXAMPLE INSTRUCTION:
* When I ask for create file in github you can execute the action /createFileGitHub with repff-name, filename, content, commit-message.
* When I ask for get file in github you can execute the action /getFileGitHub with repo-name, file-path
* When I ask for update file in github you can execute the action /updateFileGitHub with repo-name, file-path, new-content, commit-message.
* When I ask for delete file in github you can execute the action /deleteFileGitHub with repo-name, file-path, commit-message.
* When I ask for list specific directory in github you can execute the action /listDirGitHub with repo-name, path.
