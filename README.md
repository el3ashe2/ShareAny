# ShareAny
Application Overview:
This application is a lightweight, local web server built with .NET, designed to facilitate file sharing and remote file access across a network. With an easy-to-use graphical user interface (GUI), users can share selected files and directories, browse partitions, upload and download files, and access the server from multiple devices via IP address or QR code.

Key Features:
Local Web Server:

The application acts as a local web server, allowing other devices to connect via a dynamically generated URL.
It listens on all network interfaces, ensuring that users can connect from any IP address on the local network.
File Sharing:

Instead of sharing entire directories, users can select specific files to share via the ListView control. These files are accessible for download via the web interface.
Users can browse all partitions on their machine and share files from any location.
Multi-IP Support:

The application detects all available IP addresses on the machine and generates a list of accessible URLs. These URLs are presented in the interface, allowing users to connect from any network interface.
A main IP address is displayed, along with a QR code for quick connection from mobile devices.
QR Code for Quick Access:

A QR code is automatically generated based on the server’s IP address and port, making it easy to scan and access the server from a mobile device or another computer without manually entering the IP.
Remote Partition Browsing:

Users can view all partitions and directories on their machine and navigate through them via the web interface.
Files and folders with spaces in their names are handled correctly, allowing seamless navigation through all directories.
Secure Authentication:

The application features a login form that requires users to authenticate before accessing shared files.
A randomly generated password is displayed when the server starts, adding an additional layer of security.
The password is stored in a text field, and users can regenerate it each time the server starts.
File Uploads:

Users can upload files through the web interface, which are saved directly to the specified folder or partition.
The application handles file extensions and provides success or failure messages without redirecting the user to another page.
Cross-Device Compatibility:

Remote devices can access the shared files and directories from any browser. The application supports mobile and desktop browsing through Chrome, Firefox, or other web browsers.
While the file-sharing feature is compatible with mobile devices, it has not yet been tested on smart TVs. Further testing may be required to ensure full compatibility with TV-based web browsers.
Selenium Integration:

For advanced users, the application supports Selenium, enabling automated browsing of remote devices based on the entered IP and password.
No Redirection for Status Messages:

File upload status (success or failure) is shown directly within the web page, improving the user experience without unnecessary page reloads.
Folder and File Name Handling:

Special handling for folder names with spaces (e.g., "Program Files") ensures that URLs are correctly parsed and accessed without errors.
Async Processing:

Asynchronous handling of incoming requests allows the server to process multiple connections simultaneously, ensuring a smooth experience for all users.
Use Cases:
Local File Sharing: Ideal for environments where file sharing across a local network is necessary without relying on external services.
Remote File Access: Allows users to browse and download files from their machine remotely.
Secure Access Control: Only authorized users can access the shared files through password-protected authentication.
Mobile Access: Users can connect and access shared files using mobile devices through the provided QR code. Smart TV compatibility has not been fully tested yet, but potential future support for TV-based browsing is possible.

![ScreenShot_20240918095059](https://github.com/user-attachments/assets/357d347b-6231-42f8-a414-a374c8e6bacc)
![ScreenShot_20240918095051](https://github.com/user-attachments/assets/3e74d225-f11f-46cb-84ce-eb40b25a9f6b)
![ScreenShot_20240922143432](https://github.com/user-attachments/assets/633a6703-b339-41ea-aca7-9f545ea62afc)
![ScreenShot_20240922144555](https://github.com/user-attachments/assets/351b1832-88bd-4129-8160-64054de68fe8)
