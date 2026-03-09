Basic Server Setup - Windows IIS
Introduction

In this practical task, I set up a local web server using Internet Information Services (IIS) on a Windows computer. A server is a system that provides services or resources to other computers on a network. IIS allows a computer to host websites and deliver web pages to users through a browser.

The objective of this task was to install and configure a simple local server, create a webpage, and verify that the server is running correctly using http://localhost.

1. Server Installation (Windows IIS)

Enabled Internet Information Services (IIS) through Windows Features

Installed the web server components required to host a website locally

Confirmed the installation completed successfully

<img width="1069" height="546" alt="Enable windows IIS" src="https://github.com/user-attachments/assets/bc2f870a-7f4a-4a89-b584-d8fd93363b74" />

<img width="1013" height="561" alt="istallation process" src="https://github.com/user-attachments/assets/88bf72a5-c969-4572-b1ad-598dcc449f5a" />

<img width="1035" height="605" alt="Installation" src="https://github.com/user-attachments/assets/39b6d114-4b5a-4932-bdaf-f880dbdf5f89" />



2. Testing the Local Server

Opened a web browser

Entered http://localhost in the address bar

Verified that the IIS server responded and displayed the default page

<img width="1352" height="765" alt="Capture111" src="https://github.com/user-attachments/assets/8d08c822-e979-4f15-9407-59081316c0f5" />


3. Web Server Directory Structure

Located the default IIS website folder

Directory used by the server:

C:\inetpub\wwwroot

Verified that this folder stores all website files served by the web server

<img width="1027" height="559" alt="wwwroot folder" src="https://github.com/user-attachments/assets/e3686db5-a717-4bcb-b353-1f2fbab064a5" />

<img width="1041" height="505" alt="WEBSITE FOLDER" src="https://github.com/user-attachments/assets/41984924-7979-403a-92ac-8bd8d3d9b25f" />



4. Creating a Webpage

Created a basic HTML file named index.html

Saved the file inside the wwwroot folder

Added simple HTML code to display a message on the webpage

<img width="1035" height="568" alt="file inside wwwroot" src="https://github.com/user-attachments/assets/5d6e1043-6a32-48a7-8904-ac995d0e1ec4" />


5. Viewing the Hosted Webpage

Refreshed the browser page http://localhost

Verified that the custom webpage was displayed correctly from the local server

http://localhost/
<img width="1529" height="551" alt="my website" src="https://github.com/user-attachments/assets/e34a53c8-0d9e-4b08-85c0-42e4bbe2fdf5" />


6. Verifying Server Services

Opened the Windows Services application

Located World Wide Web Publishing Service

Confirmed that the service status shows Running

<img width="1204" height="729" alt="IIS Service" src="https://github.com/user-attachments/assets/eff7d4ff-3426-455a-b848-b9b368aa56e3" />


Conclusion

This task demonstrated how to set up and configure a basic local web server using Internet Information Services (IIS) on Windows. The server was successfully installed, configured, and tested by hosting a simple HTML webpage. The webpage was accessed using http://localhost, confirming that the server was functioning correctly. This practical exercise provided a better understanding of how servers host and deliver web content within a network environment.
