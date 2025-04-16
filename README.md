```markdown
# IP-Changer

This script allows you to change your IP address using the Tor network.

## Prerequisites

- The script must be run as root.
- The `curl` and `tor` packages must be installed.
- The Tor service must be running and configured to use the socks5 proxy at `127.0.0.1:9050`.

## Installation

1. Download the script to your system:

```bash
wget https://freakfrv4/Ip-changer/Ip-Changer.sh
```

2. Make the script executable:

```bash
chmod +x ip-changer.sh
```

## Usage

1. Run the script:

```bash
./ip-changer.sh
```

2. Enter the time interval in seconds for how often you want to change your IP address.
3. Enter the number of times you want to change your IP address.
   - Enter `0` for infinite IP changes.

The script will automatically change your IP address every specified interval or until the specified number of changes are made.

## License

This script is licensed under the [MIT License](LICENSE).

## Details

This README.md file provides an overview of the script, installation instructions, usage information, and a license section. You can customize it further based on your specific needs.
