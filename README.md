# Hedwig -- Real-Time File Transfer Web Application

## Overview

Hedwig is a real-time file transfer web application that allows users to easily share files with each other. It leverages Socket.IO to provide seamless and efficient file transfer capabilities.

![Demo](/assets/Demo.gif)

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Application Structure](#application-structure)
- [Getting Started](#getting-started)
- [Development](#development)
- [Conclusion](#conclusion)

## Features

- **Real-Time File Transfer:** Users can send and receive files in real-time without the need for manual refresh.

- **User-Friendly Interface:** A simple and intuitive user interface that enables users to quickly understand and use the application.

- **Drag-and-Drop File Upload:** Users can drag and drop files onto the application to initiate the file transfer process.

- **Progress Indicators:** Visual indicators for file upload and download progress, ensuring users are aware of the transfer status.

- **File Previews:** Thumbnail previews or icons for common file formats, allowing users to identify files at a glance.

## Tech Stack

- **Socket.IO:** Real-time communication between the client and server, facilitating instant file transfer updates.

- **JavaScript:** Client-side scripting to handle interactions, file uploads, and dynamic updates.

- **HTML:** The structure and layout of the application's web pages.

- **CSS:** Styling and visual design of the application for an appealing user interface.

## Application Structure

```bash
hedwig/
├── public/
│   ├── code.js
│   ├── receiver.js
│   ├── index.html
│   ├── receiver.html
│   ├── styles.css
├── server.js
```

- **server.js:** The server file containing the server-side code for the application.

- **public:** Folder containing the client-side code and resources for the application.

- **code.js:** The JavaScript file for the sender side code.

- **receiver.js:** The JavaScript file for the receiver side code.

- **index.html:** The main HTML file containing the application's layout and structure.

- **receiver.html:** The HTML file for the receiver page, which is displayed on receivers' devices.

- **styles.css:** Cascading Style Sheets for styling the application's visual elements.

## Getting Started

1. Clone the Hedwig repository:

```bash
git clone https://github.com/amaan14999/Hedwig.git
```

2. cd into the project directory and install the required dependencies:

```bash
cd hedwig
npm install
```

3. Start the server:

```bash
node server.js
```

3. Click or drag and drop files onto the application to initiate real-time file transfers.

## Development

To contribute to Hedwig's development:

1. Set up a Node.js server using `server.js` in the `server` folder (not shown here).

2. Modify `index.html`, `styles.css`, and `script.js` to enhance and customize the application.

3. Use Socket.IO to establish real-time communication between the client and server.

4. Test the application thoroughly to ensure seamless file transfer functionality.

## Conclusion

Hedwig is a powerful real-time file transfer web application that leverages HTML, JavaScript, CSS, and Socket.IO to provide users with an efficient and user-friendly experience for sharing files. Its intuitive interface, drag-and-drop functionality, and secure transfer mechanisms make it a valuable tool for various file-sharing needs.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
