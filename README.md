# track-ip
## Installation :

* `apt update`
* `apt install git curl -y`
* `git clone git://github.com/sandeepdas17/track-ip.git`
* `cd track-ip`

#### > Run : `bash trackip`

## Single Command :
```
apt update ; apt install git curl -y ; git clone git://github.com/sandeepdas17/track-ip.git ; cd track-ip ; bash trackip
```
# IP Address Information Script

## Description
This script is a Bash utility designed to fetch and display detailed information about IP addresses. It uses APIs to retrieve IP details such as location, ISP, time zone, and more. The script is interactive, allowing users to either view their own IP address details or input another IP address to gather its information. The key features and components of the script are outlined below:

## Key Features
- **Banner Display**: Displays a custom ASCII art banner each time the script runs.
- **Interactive Menu**: Offers options to view information about your own IP address or any other IP address.
- **Fetch Own IP Address Details**: Retrieves data such as city, region, country, latitude, longitude, time zone, postal code, ISP, ASN, country code, currency, languages, and calling code.
- **Fetch Details of Any IP Address**: Allows input of any IP address and fetches similar detailed information.
- **APIs Used**: Utilizes `ipapi.co` and `ip-api.com` APIs for comprehensive IP address data.
- **Formatted Output**: Enhances readability using color-coded, well-structured output.

## Components
- **`banner` function**: Displays a stylized ASCII art banner.
- **`menu` function**: Presents options to choose from for IP address information.
- **`myipaddr` function**: Fetches and displays details about your own IP address.
- **`useripaddr` function**: Prompts for an IP address and displays detailed information.

## Usage
1. **Run the script**:
   - Execute the script in a Bash terminal.
   - The banner and menu options will be displayed.

2. **Select an option**:
   - Choose to view details of your own IP address or enter another IP address.

3. **View formatted output**:
   - The script displays the requested information clearly and readably.

<br>
<p align="center">


### <<< If you copy , Then Give me The Credits >>>

## Example
```bash
./ip_info_script.sh





