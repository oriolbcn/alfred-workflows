# Focus Work Workflow

## Installation

1. Import the `focus_work.alfredworkflow` file to Alfred.
2. Open Alfred Preferences, select the Workflow and Click on "Configure workflow and variables" in the Workflow header.
3. Add a new variable named "token" with your Slack API token. See below for instructions on how to get it.

## Slack API Token

Go to the [Legacy Slack API page](https://api.slack.com/custom-integrations/legacy-tokens) and genrate a token for your desired Workspace.

## Usage

Type "focus on" on Aflred to start doing focused work. This performs 2 actions:

* Set "Do not disturb" mode on the computer.
* Set a status message on Slack to indicate to your co-workers that you are not available.

Type "focus off" to disable "Do not disturb" and remove the status message.

Enjoy!