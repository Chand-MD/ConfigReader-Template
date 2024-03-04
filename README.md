# ConfigReader Template Overview

The **Config Reader** reusable template fetches the config node values configured in the `config.xml` file into respective variables for further usage in the Parent bot. Before reading the node, it verifies if the given XML is valid. If valid, it fetches the node values; otherwise, it logs the required details and terminates the bot. Feel free to customize the nodes and logic as per your needs.

## Instructions

1. Download the `Config.xml` file from the specified path.
2. Map the path to the `sConfigPath` variable.
3. Create a `Logs.txt` file and pass the value to the `sLogFilePath` variable before running the bot.

## Configure Input Variables

- `sConfigPath`: Path to the `Config.xml` file.
- `sLogFilePath`: Path to the `Logs.txt` file.

## Bot Output

![image](https://github.com/Chand-MD/ConfigReader-Template/assets/34576689/5f8ffb4f-79d3-46db-8c5f-7313346f106d)

