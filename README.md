# Discord-Image-Grabber
# Row Image Grabber: Advanced Personal Discord Token Extraction

## Overview
Row Image Grabber is an advanced tool designed to capture sensitive data from Discord accounts, primarily focusing on extracting Discord tokens. It interacts with images or elements within the Discord environment and retrieves a wide range of personal and system information from the target account and device. The tool is capable of collecting comprehensive data across various platforms and browsers.

## Core Features Breakdown

### 1. Discord Token Information Extraction:
The tool is designed to capture personal Discord account tokens, which can then be used for account hijacking or further malicious activities. Key details extracted include:

- **Discord Nitro Status**: Indicates if the account is subscribed to Discord Nitro or Nitro Classic.
- **User Badges**: Identifies and extracts badges associated with the account, such as Nitro or Early Supporter badges.
- **Billing Information**: Retrieves credit card details or other billing-related information linked to the account.
- **Email Address**: The email associated with the Discord account.
- **Phone Number**: Captures the phone number registered to the Discord account, often used for 2FA (Two-Factor Authentication).
- **HQ Guilds**: High-quality servers (guilds) the user is a part of.
- **HQ Friends**: High-quality, often close, friends or contacts within the Discord platform.
- **Gift Codes**: Extracts gift codes, which can be used to redeem Discord services or subscriptions.

### 2. Browser Data Collection:
The tool collects sensitive browser data across several popular browsers, which may be used for further exploitation:

- **Cookies**: Extracts session cookies that can potentially be used to hijack ongoing Discord sessions.
- **Passwords**: Retrieves saved passwords within the browser for accounts, including Discord.
- **Browser History**: Collects browsing history for user identification or tracking purposes.
- **Bookmarks**: Extracts bookmarked URLs that might reveal sensitive or personal information.
- **Autofill Data**: Captures autofill information, such as saved addresses, phone numbers, and other form inputs.

### 3. Discord Injection:
The tool injects code into Discord's processes or browser extensions (if Discord is accessed through a browser) to silently extract:

- **Discord Token**: Directly extracting the authentication token for the Discord account, which is the key to fully accessing the account without needing to log in again.
- **Password and Email**: Captures these credentials on login or whenever a password change occurs.

### 4. System Information Extraction:
The tool can gather detailed information about the user's system, which can assist in targeted attacks or monitoring:

- **User Information**: Retrieves the username and other system-level user data.
- **System Data**: Gathers details such as the operating system, device type, and version.
- **Disk Information**: Captures information about the user's disk storage, potentially identifying files and directories of interest.
- **Network Data**: Collects information about the network connection, including IP address and connected networks.
- **WiFi Information**: Can access saved WiFi networks, including passwords.
- **Screenshots**: Takes periodic screenshots of the active session to capture any visible sensitive data or actions.

### 5. Anti-Debugging Measures:
- **Sandbox Detection**: The program includes measures to detect if it’s being run in an environment designed to analyze or monitor it (e.g., VirusTotal sandbox). This ensures the tool operates without being flagged or disrupted during execution.

### 6. Startup Persistence:
The tool ensures that it remains active on the system by:

- **AppData Installation**: The program places its components in the AppData directory to maintain persistence and remain hidden from the user.
- **Startup Registry Entries**: Adds entries to the system's startup registry to ensure the program runs automatically every time the system restarts.
- **Installation of Necessary Components**: Ensures that the necessary files are installed for continued operation, even if the user tries to delete them.

## Critical Functionality - Discord Token Extraction:
The main goal of Row Image Grabber is to extract the Discord token, which is a unique key that allows unauthorized access to a Discord account. The program achieves this by utilizing image-based or element-based triggers. Here's how it works:

- **Image-based Triggering**: The tool may monitor certain visual cues, like a specific image or notification in the Discord environment. Once the image or trigger is detected, the program begins its extraction process.
- **Token Extraction Process**: The program silently collects the Discord authentication token, which is the most sensitive piece of information required to hijack a Discord account. This token can be used to bypass the login page, gaining full access to the account without needing any credentials.

## Important Legal and Ethical Considerations:
- **Privacy Violation**: Using such a tool without permission is illegal and a violation of privacy laws. It can lead to criminal charges, account bans, and other legal consequences.
- **Use for Testing Only**: This tool is for educational purposes and should only be used in authorized environments. Unauthorized use can cause harm, including identity theft, financial fraud, and data breaches.

## Disclaimer:
The described tool is intended for security research and educational purposes. Using it in any malicious manner or without consent is illegal and unethical. Always respect privacy and adhere to ethical guidelines when dealing with sensitive data.

---

## System Requirements:

- Ensure **Python 3.10 or above** is installed on your system. If Python is not installed, download it from the official Python website and complete the installation before proceeding.
- A stable **internet connection** is required for the program to function correctly.
- Temporarily **disable your antivirus** or **Windows Defender**, as these programs may incorrectly identify and delete important files required for the application.

## Running the Program:
Locate and double-click on **"Row Image Grabber.exe"** to launch the program. During the first launch, you will be prompted to enter the password.

**Password**:  
<span style="color:red;">RowBeta132</span>

This program is in its Beta version and is available for **Discord use only**. Each user is allowed to use the program for a maximum of **2 days** from the date they first run it. After this period, access will be restricted.

---

## Important Notes:

- Ensure all requirements are met to avoid any issues during installation or usage.
- Contact support if you encounter any errors or need assistance.

---

**Disclaimer:** As a Beta program, some features may still be under development. Feedback is appreciated to improve the final release.
