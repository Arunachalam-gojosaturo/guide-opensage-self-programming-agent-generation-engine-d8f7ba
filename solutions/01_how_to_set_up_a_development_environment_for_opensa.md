# How to set up a development environment for OpenSage on a Linux machine

_Install OpenSage and required dependencies using apt and pip_

## Steps

1. Update the package list using the command `sudo apt update`
2. Install the required dependencies with `sudo apt install -y python3 python3-pip`
3. Install OpenSage using pip with `pip3 install opensage`
4. Verify the installation by running `opensage --version`
5. Configure the environment variables by adding `export PATH=$PATH:/usr/local/bin/opensage` to the shell configuration file

## Pitfalls

- Forgetting to update the package list before installing dependencies