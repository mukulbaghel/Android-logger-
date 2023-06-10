# OS-PROJECT-LOGGER
ANDROID LOGGER USING DROPBOX
To run the program download all programs and store in a folder, open that folder in vs code and run terminal using 'npm run dev' key to execute localhost program
Then open html file and logger is listening to that portal
Then opening any application will get updated in sample.txt file which is intergrated to dropbox.


## Features

- Log Android device events and data to a Dropbox account.
- Store logs in a structured format for easy organization and retrieval.
- View and manage logs through a web-based interface.

## Prerequisites

To set up and run this project, you'll need the following:

- Android device or emulator running Android 5.0 (Lollipop) or later.
- Node.js installed on your machine.
- A Dropbox account.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/android-logger.git
   ```

2. Install the required Node.js dependencies:

   ```bash
   cd android-logger
   npm install
   ```

3. Configure Dropbox API credentials:

   - Create a new Dropbox app in the [Dropbox Developer Console](https://www.dropbox.com/developers/apps).
   - Generate an access token for your app.
   - Copy the access token.

4. Configure the application:

   - Rename the `.env.example` file to `.env`.
   - Open the `.env` file and replace the `DROPBOX_ACCESS_TOKEN` placeholder with your Dropbox app access token.

5. Start the Node.js server:

   ```bash
   npm start
   ```

6. On your Android device, install the `AndroidLogger` app located in the `android-logger` directory.
7. Launch the `AndroidLogger` app and provide the necessary permissions.
8. Start logging events on your Android device.

## Usage

Once the server is running and the AndroidLogger app is logging events, you can access the web interface by visiting `http://localhost:3000` in your browser. The interface will display a list of available logs, allowing you to view and manage them.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.


## Acknowledgments

This project utilizes the following open-source libraries:

- [Express](https://expressjs.com) - Fast, unopinionated, minimalist web framework for Node.js.
- [Dropbox API](https://www.dropbox.com/developers/documentation) - Official Dropbox API library for Node.js.

## Contact

For further information or inquiries, feel free to contact the project maintainer at [montybaghel1513@gmail.com](mailto:montybaghel1513@gmail.com).
