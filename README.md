# MaliciousUrlShortner- (web & command line)

![hippo](https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif)

🌐 Encrypted Link Masking on Secured Network 🛜 

Only URL shortner that will shorten any extension over secured network is now available through web.

🌟 Shorten any malicious file-carrying URL through pur web interface and easily bypass blacklist filter ! Bypass virus total, bitly, redirectdetective and more..

Our Tool is a complete implementation of a URL shortener with additional functionality, including tracking user device information, VPN detection, and API key validation. Below is a succinct overview of the key components and functionalities present in the script:

### Overview of the Code Components

1. **Imports**:
   - Utilizes various modules such as `http.server` for handling HTTP requests, `json` for parsing JSON data, `uuid` for unique identifier generation, and `psutil` for system and process management.

2. **Configuration**:
   - Defines constants for the host, port, and API keys file, and initializes in-memory stores for URLs and tracking data.

3. **Utility Functions**:
   - **Device Info**: Gathers details about the device using user-agent strings.
   - **API Key Management**: Functions to load, save, and validate API keys with usage limits.
   - **URL Shortening Functionality**: Generates short codes and associates them with original URLs.
   - **Geolocation and ISP Information**: Uses GeoIP databases to retrieve location and ISP details based on the user's IP address.
   - **VPN Detection**: Utilizes an external API to determine if a user is accessing via a VPN.

4. **Request Handling**:
   - Defines the `URLShortenerHandler` class, which handles both GET and POST requests.
     - **GET Requests**: Displays the main interface for URL shortening and handles redirection based on provided short codes.
     - **POST Requests**: Processes URL shortening requests, checks API validity, and responds with the shortened URL and tracking link.

5. **Tracking**:
   - The code keeps track of each access to shortened URLs, storing information about the timestamp, IP address, user agent, and various device and network details.
   - Displays comprehensive tracking logs for both API key users and standard users, showing the effectiveness of the tracking.

6. **HTML and JavaScript**:
   - The HTML for the user interface is built dynamically within the handler and includes JavaScript for collecting advanced device information.

7. **Server Execution**:
   - The `run` function initializes and starts an HTTPS server using SSL certificates, handling requests in a secure manner.

### Key Functionalities
- **URL Shortening**: Shortens given URLs and provides a tracking mechanism.
- **Device Tracking**: Collects comprehensive device information, including OS, browser details, and hardware specs.
- **API Integration**: Provides a mechanism to control access to features based on the usage of API keys.
- **VPN Detection**: Identifies whether the request is coming from a VPN service, applying access controls accordingly.
- **Web-based UI**: Presents a user-friendly interface for shortening URLs and displaying tracking data.

### Usage
The code can be executed as a standalone Python script. Make sure to have the necessary certificates for SSL setup and ensure that required Python packages (such as `user_agents`, `geoip2`, and `requests`) are installed. Adjust the host and port as needed for your deployment, typically in a production environment.

Overall, the script serves as a robust tool for URL shortening and tracking, combining various technologies and approaches to enhance usability and security.

DIRECT ACCESS 

(https://kalkikrivadna.com/u22.shtml)

🚀 Stay safe and happy shortening! 😊

Find more details at https://kalkikrivadna.com 


# Contact
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/kalkimahavatar)
