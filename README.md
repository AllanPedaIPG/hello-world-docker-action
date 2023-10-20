# Hello world docker action

## Step 1, create a minimal Dockerfile

## Step 2, Creating an action metadata file (action.yml)

## Step 3, create the code called by the acton file (the entrypoint)

## Step 4, This file must be executable, check with `git ls-files --stage entrypoint.sh`



This action prints "Hello World" or "Hello" + the name of a person to greet to the log.
https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action

# Variables and Commands
https://docs.github.com/en/actions/using-workflows/workflow-commands-for-github-actions

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
