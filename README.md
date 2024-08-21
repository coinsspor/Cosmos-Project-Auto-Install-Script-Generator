# Cosmos Project Auto-Install Script Generator

## Overview

The **Cosmos Project Auto-Install Script Generator** is a web-based tool designed to create personalized auto-install scripts for any Cosmos SDK-based project. This generator enables users to configure their scripts by inputting specific parameters like wallet name, moniker, port, chain ID, project directory, and more. The resulting script is ready to be used for automatic node setup and configuration.

This tool is versatile and supports a wide range of Cosmos-based networks by allowing users to customize critical configuration settings specific to each project.

## Features

- **Customizable Inputs:** Easily configure your node by specifying key parameters such as wallet name, moniker, port, and more.
- **Binary Name Flexibility:** Supports various binary names, making it adaptable to different Cosmos SDK projects.
- **Keyring Backend Selection:** Choose from `os`, `file`, or `test` keyring backends, with `test` set as the default.
- **Minimum Gas Prices Configuration:** Customize the gas prices to suit the specific network requirements.
- **Snapshot Support:** Optionally include a snapshot URL for faster node synchronization.
- **Service File Creation:** Automatically generates a systemd service file for managing the node process.
- **User-Friendly Interface:** A clean and straightforward web interface with example filling and instant script generation.

## Usage

1. Fill in the required fields on the webpage.
2. Click **"Generate Script"** to create your customized installation script.
3. Copy the generated script and execute it on your server to set up your node.

### Example Inputs

- **Wallet Name:** `mywallet`
- **Moniker:** `mymoniker`
- **Port:** `17`
- **Chain ID:** `empe-testnet-2`
- **Project Directory:** `.empe-chain`
- **Genesis File URL:** `https://server-5.coinsspor.com/testnet/empeiria/genesis.json`
- **Binary Name:** `emped`
- **Minimum Gas Prices:** `0.0001uempe`
- **Keyring Backend:** `test`

## Installation

To use this tool:

1. Host the HTML file on your preferred web server.
2. Access the hosted page and start generating custom scripts instantly.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to:

- **Submit a pull request**
- **Open an issue**

Let's improve this tool together!

## License

This project is licensed under the [MIT License](LICENSE).

## Live

Check out the live version of the tool here: [Cosmos Project Auto-Install Script Generator](https://cosmos-auto-install-script.coinsspor.com/)

---

**Note:** Always ensure that the parameters provided in the script match the requirements of your specific Cosmos SDK-based network to avoid any issues during node setup.

