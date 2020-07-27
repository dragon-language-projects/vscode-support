# vscode-support

setting for ease dragon 

 ## json task config should look like
```
{
    // See https://go.microsoft.com/fwlink/?LinkId=733558
    // for the documentation about the tasks.json format
    "version": "2.0.0",
    "tasks": [
        {
            "label": "dragon-run ",
            "type": "shell",
            "command": "dragon-native -r ${file} ",
            "problemMatcher": [],
            "group": {
                "kind": "build",
                "isDefault": true
            }
        }
    ]
```

 ## workspace should should be :

```
{
	"folders": [
		{
			"path": ".."
		}
	],
	"settings": {
	}
}
```

## setting.json 
```
{
}
```
