# TFSHelper
A small cmd utility intended to simplyfy working with TSF and CC


## Vision
The hope is that this utility will be able to handle the following tasks:

1. Maintaining a persistent idea of which issue/task I am working on
1.1. Maintaining a description of the issue to use when checking out files
1.2. Keeping track of time spent on an issue
1.3. Keeping track of multiple unfinished issue.
1.4. To help keeping notes in regards to the project

2. Keeping track of files checked out in regards to specific issues
2.1. Checking out files with the correct description
2.2. Store history of which files have been involved in the issue
2.3. Checking in all files when issue have been resolved

## Mision
I want this to be as simple as possible so I intend for all these features to 
be available through one command, which will go by the name `task`.

1. To add a new task: `task task "task description"`
1.2. To keep track of time:
	`task pause`
	`task resume`
1.3.1 To list tasks: `task tasks [active|finished|all] [fuzzy]`
1.3.2 To switch to a different task: `task set "fuzzy match description"
1.4.1 To make a note in project: `task note "note"`
1.4.2 To list notes in project `task notes`
2.1 To add a file to currect task: `task file path`
2.2 To list files in task: `task files [fuzzy]
2.3. To check in files when finished: `task finish`

	






	
