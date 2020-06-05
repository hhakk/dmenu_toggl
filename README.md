# dmenu_toggl

Fill time-entries to Toggl time tracker with `dmenu` and `cURL`.


The script prompts you for a project, description, start time (currently for today) and the duration of your task.

## Before you use the script

1. Go to your profile in Toggl and copy the API key to `API_KEY` variable
2. Fill the `PROJECTS` variable with your project ids and names (can be any name)
Example:
	```
	PROJECTS="MyFirstProject,123456789\\nMySecondProject,987654321"
	```
(The format is standard CSV with `name` and `pid` columns, the script is wasily modified to read project data from an external file)

1. Fill `DESCRIPTIONS` variable with as follows:
	```
	DESCRIPTIONS="MyDesc1\\nMyDesc2"
	```

## "Installation" to run from anywhere

1. Copy this script to `~/bin` (or some location on your `$PATH`)
2. Run `chmod +x dmenu_toggl` (in the same folder)

## Run the script

```
dmenu_toggl
```



