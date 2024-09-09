# LinkedIn Network Expander

## ⚠️ Disclaimer

This repository contains a script designed to automate the process of sending connection requests on LinkedIn. Please be aware that using this script may violate LinkedIn's User Agreement, particularly their policies against automated interactions. Use of this script could potentially lead to account restrictions or bans.

**Use this script at your own risk. The author(s) of this repository are not responsible for any consequences resulting from the use of this script.**

## Purpose

The purpose of this script is to demonstrate how browser automation can be applied to social networking platforms. It is intended for educational purposes only, to illustrate concepts of web scraping and automation.

## Features

- Automatically scrolls through LinkedIn search results
- Sends connection requests to profiles matching your search criteria
- Optionally adds a personalized note to each connection request
- Includes configurable delays between actions to mimic human behavior

## Usage

1. Clone this repository
2. Open LinkedIn in your web browser and log in
3. Navigate to the search results page for the people you want to connect with
4. Open your browser's developer console
5. Copy the entire content of `index.js`
6. Paste the script into the console and press Enter to run it

## Configuration

You can modify the following parameters in the `config` object at the top of the script:

- `scrollDelay`: Time (in ms) between scrolling actions
- `actionDelay`: Time (in ms) between main actions (clicking buttons, etc.)
- `nextPageDelay`: Time (in ms) before moving to the next page of results
- `maxRequests`: Maximum number of connection requests to send
- `addNote`: Whether to add a personalized note to requests
- `note`: Template for the personalized note (uses `{{name}}` as a placeholder)

## Ethical Considerations

While this script demonstrates interesting programming concepts, it's important to consider the ethical implications of its use. Automated interactions on social platforms can be seen as inauthentic and may negatively impact the experience of other users. We strongly encourage building your professional network through genuine, personal interactions.

## Contributing

This project is not actively maintained and we do not encourage its use on live LinkedIn accounts. However, if you have suggestions for improving the educational aspects of this code, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
