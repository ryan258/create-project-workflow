# Create a Project Workflow

A useful Python/Bash script to get a project up and running with a remote repository on Github.

## Setup

```shell
pip install -r reqs.txt
touch .env
source path/to/.my_commands.sh
```

In your .env file create your variables for your Github USERNAME, PASSWORD, and local project destination folder like so:

```bash
USERNAME="githubUsername"
PASSWORD="githubPassword"
FILEPATH="/path/to/project"
```

## Usage

```shell
create name-of-the-project-folder
```

## Result

You should have a new folder that you have been moved into that has a remote repo on Github.

# Attribution

A great deal of gratitude has to go to Kalle Hallden for his video [One Day Builds: Automating My Projects With Python
](https://www.youtube.com/watch?v=7Y8Ppin12r4) which opened my eyes to the possibilies of Python automation and set me off on this project. His original repo can be found [here](https://github.com/KalleHallden/ProjectInitializationAutomation).
