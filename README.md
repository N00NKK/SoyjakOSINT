# Soyjak OSINT

**Version**: 1.0  
**Created by**: Wendego

Soyjak OSINT is a command-line tool designed for basic OSINT (Open Source Intelligence) gathering using different public data sources. It provides a set of useful tools for looking up IP information, phone number details, domain WHOIS data, and performing name/location-based searches.

## Features

- **IP Lookup**: Provides geolocation data for an IP address (Country, Region, City, ISP, and more).
- **Phone Lookup**: Validates and provides information about a phone number (Carrier, Location, Line Type).
- **Domain Lookup**: Displays WHOIS information for a given domain (Registrar, Creation Date, Name Servers).
- **Name Lookup**: Performs a search using a name, city, and country, returning DuckDuckGo results.

## Installation

Ensure you have Python 3.x installed. The script uses the following external libraries:
- `requests` for making HTTP requests.
- `whois` for domain WHOIS lookups.
- `BeautifulSoup` for web scraping.
- `ddgs` for DuckDuckGo searches.

Install the dependencies using:

```bash
pip install requests whois beautifulsoup4 ddgs
```
## Usage

Clone or download the repository.

Run the script:

python soyjak.py


Enter a command from the following list to perform various OSINT operations.

## Available Commands

ip: Lookup geolocation information for an IP address.

phone: Lookup details for a phone number.

domain: Perform a WHOIS lookup for a domain.

name: Perform an OSINT search for a name and location.

help: Display this help menu.

clear: Clear the screen.

credits: Show credits.

exit: Exit the program.

## Example
soyjak> ip
Enter IP: 8.8.8.8
IP: 8.8.8.8
Country: United States
Region: California
City: Mountain View
ISP: Google LLC
Org: Google

## Credits

This tool was created by n00nkk/wendego.

For more information and updates, visit the following:

[Telegram Channel](https://t.me/wendegotools)
[Discord Server](https://discord.gg/uykBnFPKRh)

## License

This project is open-source. Feel free to contribute or use it for educational purposes.


This `README.md` covers the key aspects of your project, including setup instructions, command usage, and examples. Let me know if you'd like to modify or expand anything!
