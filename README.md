# Text Editor Application

## Description

This Text Editor is a progressive web application (PWA) that allows users to create, view, and edit text documents or code snippets. The application features offline capabilities, ensuring that users can access and modify their documents without an active internet connection. Changes are saved locally and can be retrieved upon subsequent access.

## Features

- **Offline Functionality**: Utilizes service workers and IndexedDB for seamless offline access and data persistence.
- **Live Editing**: Real-time editing capabilities with a user-friendly interface.
- **Auto-Save**: Automatically saves changes to prevent data loss.
- **Cross-Platform**: Accessible on various devices as a PWA.
- **Lightweight and Fast**: Optimized for performance and ease of use.

## Installation

1. Clone the repository:
    git clone https://github.com/SporeSun/text-editor.git
2. Navigate to the project directory:
    cd text-editor
3. Install dependencies:
    npm install
4. Start the application:
    npm run start


## Usage

After starting the application, navigate to `http://localhost:3000` in your web browser. The text editor interface will be available for creating and editing documents. All changes are auto-saved to IndexedDB, ensuring that your data is preserved even if you go offline or close the browser.

Or browse on `https://sporesun-editor-79620e31ca64.herokuapp.com/`

## Technologies Used

- HTML/CSS/JavaScript
- [CodeMirror](https://codemirror.net/) for the text editor interface
- Service Workers for offline functionality and caching
- IndexedDB for local data storage
- Webpack for asset bundling
- Node.js and Express for the backend server
- Heroku for hosting and deployment

## Contributing

Contributions to the project are welcome! Please follow the standard fork-and-pull request workflow. If you have any suggestions or improvements, feel free to create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or comments, please feel free to reach out to the project maintainer.

https://github.com/SporeSun
sporesun@protonmail.com
