# e-hentai Gallery Downloader

![Python version](https://img.shields.io/badge/python-3.6%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Automate the download of images from e-hentai galleries using Python. Fetch gallery metadata, download images, and create .nfo files with metadata.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Fetches gallery metadata using e-hentai API.
- Downloads images and saves them to local directories.
- Creates .nfo files containing metadata for each downloaded image.
- Respectful delay to avoid overloading the server.
- Unicode support for metadata in .nfo files.

## Prerequisites

- Python 3.6 or higher
- Required Python libraries: `requests`, `BeautifulSoup`

## Installation

1. Clone this repository or download the ZIP.
2. Install required libraries: `pip install requests beautifulsoup4`
3. Add your e-hentai gallery IDs and tokens to `gallery_ids.txt`.

## Usage

1. Run the script: `python script.py`
2. The script will fetch metadata, download images, and create .nfo files.
3. Images will be saved in the `downloads` directory.

## Contributing

Contributions are welcome! If you find a bug or want to improve the script, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
