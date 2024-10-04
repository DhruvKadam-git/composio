# Presentation Agent Guide

This guide provides detailed steps to create an agent that creates Presentations based on Google Sheets, it leverages LlamaIndex, Composio, and ChatGPT to read the sheets, plot graphs, find key insights and create presentations. Ensure you have Python 3.8 or higher installed.

## Steps to Run
**Navigate to the Project Directory:**
Change to the directory where the `setup.sh`, `main.py`, `requirements.txt`, and `README.md` files are located. For example:
```sh
cd path/to/project/directory
```

### 1. Run the Setup File
Make the setup.sh Script Executable (if necessary):
On Linux or macOS, you might need to make the setup.sh script executable:
```shell
chmod +x setup.sh
```
Execute the setup.sh script to set up the environment, install dependencies, login to composio and 
add necessary tools:
```shell
./setup.sh
```
Now, Fill in the .env file with your secrets.
### 2. Run the python script
```shell
python cookbook/examples/quickstarters/presentation_agent/main.py
```


