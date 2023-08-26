# E-hentai-Downloader1.4

A robust Python script designed to backup your favorite galleries from E-Hentai. Crafted with care by kibasnowpaw.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Important Notes](#important-notes)

## Features

- Fetches gallery metadata using the E-Hentai API.
- Downloads images from each gallery.
- Sanitizes gallery titles to ensure valid filenames.
- Implements a retry mechanism with exponential backoff for reliable downloading.
- Introduces random delays between requests to be server-friendly.

## Prerequisites

- Python 3.x
- `requests` library
- `BeautifulSoup4` library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kibasnowpaw/E-hentai-Downloader1.4.git
   ```

2. Navigate to the project directory:
   ```bash
   cd E-hentai-Downloader1.4
   ```

3. Install the required libraries:
   ```bash
   pip install requests beautifulsoup4
   ```

## Usage

1. Prepare a file named `gallery_ids.txt` in the root directory. Each line should contain a gallery ID and token separated by a comma.

2. Run the script:
   ```bash
   python ehentai_downloader.py
   ```

3. The script will create a `downloads` directory with subdirectories named after each gallery title. Images will be saved in their respective directories.

## Contributing

1. Fork the repository.
2. Create a new branch for your changes.
3. Commit your changes with meaningful commit messages.
4. Open a pull request describing the changes you've made.

## License

This project is licensed under the GPL-3.0 License. See the `LICENSE` file in the repository for details.

## Important Notes

- Using a VPN can make the connection unstable and may result in timeout errors.
- Malwarebytes or similar security software may block some connections it deems unsafe, which can also lead to timeouts.
