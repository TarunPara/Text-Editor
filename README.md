# Text Editor Starter Code

# Text Editor PWA

This project is a Progressive Web Application (PWA) text editor that allows users to create notes or code snippets with or without an internet connection. It leverages various modern web technologies to provide a robust and offline-capable text editing experience.

## Features

- **PWA**: Fully functional as a Progressive Web Application.
- **Offline Functionality**: Edit and save your notes or code snippets even without an internet connection.
- **Data Persistence**: Uses IndexedDB for data persistence to ensure that your data is saved and retrievable across sessions.
- **Installable**: Can be installed on your desktop or mobile device as a standalone application.

## Deployed
This application is deployed to
https://justanotherte.herokuapp.com/ 

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://your-repository-url.git
cd text-editor-pwa
```

2. Install dependencies:

```bash
npm install
```

3. Start the application:

```bash
npm run start
```

The application should now be running on `http://localhost:8080`.

## Usage

- Open the application in your browser.
- Start typing in the text editor to create your notes or code snippets.
- Your data will be automatically saved to IndexedDB as you type.
- You can close the browser or go offline, and your data will persist for the next time you open the application.
- Use the "Install" button to add the application to your desktop or home screen for easy access.

## Technologies Used

- HTML
- CSS
- JavaScript
- Webpack
- Babel
- Workbox
- IndexedDB

## Contributing

Contributions are welcome! Please feel free to submit a pull request or create an issue for any bugs or feature requests.

## License

This project is licensed under the [MIT License](LICENSE.md).
