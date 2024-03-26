# Instagram Content Downloader

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pakmingc/instagram-downloader/blob/main/instagram_downloader.ipynb)

This Python script allows you to download content (photos, videos, and text) from a specified Instagram user's profile. Designed to run on Google Colab, it provides a user-friendly interface for entering Instagram credentials, selecting the target user, and specifying the desired content to download.

## Features

- Download photos, videos, and text from a specified Instagram user's profile.
- Choose the number of recent posts to download.
- Automatically handle login, including two-factor authentication.
- Retry login attempts in case of connection errors.
- Save downloaded content to Google Drive for easy access.

## Prerequisites

- Python 3.x
- Google account (for accessing Google Colab and Google Drive)

## Installation

1. Clone this repository to your local machine or download the ZIP file and extract its contents.
2. Open the Google Colab website in your web browser.
3. Click on the "Upload" tab and select the `instagram_content_downloader.ipynb` file from the cloned/extracted repository.
4. The Colab notebook will open, and you can proceed with running the script.

## Usage

1. In the Colab notebook, click on the "Runtime" menu and select "Run all" to execute the script.
2. The script will prompt you to enter your Instagram username and password. Enter your credentials and press Enter. _Note: Your Instagram credentials are not stored or shared anywhere. They are only used for authentication purposes within the script._
3. If two-factor authentication is enabled for your Instagram account, you will be prompted to enter the authentication code. Enter the code and press Enter.
4. The script will then ask for the Instagram username of the target user whose content you want to download. Enter the username and press Enter.
5. Next, you will be asked to select the type of content you want to download. Enter the corresponding letter(s) for the desired content type(s):
   - A: Photos
   - B: Videos
   - C: Text
   - D: All
6. You will be prompted to specify the number of recent posts you want to download. Enter the desired number or leave it blank to download all available posts.
7. The script will start downloading the selected content from the target user's profile. The downloaded files will be saved in your Google Drive under the `instagram_downloads/{target_username}` directory.
8. Once the download is complete, the script will display the number of items downloaded and provide a download link to access the downloaded content in your Google Drive.

## Troubleshooting

- If you encounter any connection errors during the login process, the script will prompt you to retry the login. Enter 'y' to retry or 'n' to abort the login process.
- If you experience any other issues or errors, please check your internet connection, ensure that your Instagram credentials are correct, and verify that you have the necessary permissions to access and download content from the target user's profile.

## Disclaimer

Please note that this script is provided for educational and informational purposes only. Downloading content from Instagram may be subject to Instagram's terms of service and copyright policies. Make sure you have the necessary permissions and rights to download and use the content before proceeding. The script authors and contributors are not responsible for any misuse or violation of Instagram's policies.

## License

This project is licensed under the MIT License.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

If you have any questions or need further assistance, please feel free to contact the project maintainer at pakmingc2@gmail.com

