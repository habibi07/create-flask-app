## Create flask app

### Simple script for creating flask app. This script will create basic app directory structure with optional packages
### and custom port/host. This script will also launch VS Code if installed.

### Usage: 

```
usage: PROG [-h] --name NAME [-p PACKAGES] [--port [PORT]] [--host [HOST]]
            [--use-env [USE_ENV]]

Please do not mess up this text!
--------------------------------
    This script creates flask app, 
    with basic directory 
    structure and/or with 
    virtualenv initialized.

optional arguments:
  -h, --help            show this help message and exit
  --name NAME           Name of application to create, it is also name of
                        created directory
  -p PACKAGES, --packages PACKAGES
                        additional packages to install, separated by commas
  --port [PORT]         app port, default value is 8000
  --host [HOST]         app host, default value is 0.0.0.0
  --use-env [USE_ENV]   whether or not to use virtualenv
```

