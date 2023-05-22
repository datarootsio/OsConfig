![dataroots.png](https://dataroots.io/assets/logo/logo-rainbow.png)
[![maintained by dataroots](https://img.shields.io/badge/maintained%20by-dataroots-%2300b189)](https://dataroots.io)


# OS Configuration Scripts for Data Science

This repository contains a set of bash scripts to help with the initial setup of a data science environment in different operating systems.

### Packages

The scripts install the following packages:

- Python
- Bash
- Zsh
- Poetry
- Git
- OpenJDK
- Scala
- Apache Spark
- tfenv
- Kubernetes CLI
- AWS CLI
- Azure CLI
- AzCopy
- Google Chrome
- Slack
- Visual Studio Code
- Docker
- Azure Data Studio
- Microsoft Azure Storage Explorer
- Black
- Flake8


### How to use

#### Download the Bash Script
Download the desired Bash script from this repository.

#### Adapt the variables
Modify the variables according to your needs. Here's an example:

```bash
# Define variables
PYTHON_VERSION=3.9
DATAROOTS_FOLDER=~/DataRoots/RootsAcademy
GIT_USER_NAME="David"
GIT_USER_EMAIL="david@dataroots.io"
```

#### Add or remove tools
You can add or remove tools by modifying the list of programs. Make sure to use the correct installation method. Here's an example:
```bash
# Define packages
BREW_PACKAGES=(
    python@$PYTHON_VERSION
    ...
)

BREW_CASK_PACKAGES=(
    google-chrome
    ...
)

PIP_PACKAGES=(
    black
    ...
)
```

#### Run the script
To execute the script, open a terminal and navigate to the directory where the script is located. Then, run the following command:

```bash
bash ./MacConfig.sh
```


### License
MIT license. Please see [LICENSE](LICENSE) for details.