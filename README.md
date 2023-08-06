# Microsoft Teams Meeting Auto Joiner

Automate the process of joining Microsoft Teams meetings using Selenium WebDriver and Python.

## Overview

This Python script automates the process of logging into a Microsoft Teams account, navigating through the Teams interface, and joining meetings based on specified criteria. The script uses the Selenium WebDriver library to interact with the Teams web application.

## Features

- Log into a Microsoft Teams account.
- Join scheduled channel meetings.
- Join calendar meetings.
- Handle leave thresholds and automatic hangup.
- Customizable configuration options.
- ...

## Getting Started

### Prerequisites

- Python 3.x installed
- Web browser (Google Chrome or Microsoft Edge) installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/microsoft-teams-auto-joiner.git
   cd microsoft-teams-auto-joiner
   ```
2. Install the required Python packages:

```bash
pip install -r requirements.txt
  ```
3. Configure the config.json file:

Modify the `config.json` file to provide your Microsoft Teams email and password, adjust automation settings, and set other preferences

## Usage
1. Run the script:
  ```bash
  python auto_join_teams_meetings.py
```
2. The script will log in to your Microsoft Teams account, navigate through Teams and Calendar tabs, and automatically join meetings based on the specified criteria.

## Configuration
The config.json file contains various settings that can be adjusted to customize the behavior of the script. Some of the key configuration options include:

- email: Your Microsoft Teams email.
- password: Your Microsoft Teams password.
- meeting_mode: Choose the meeting discovery mode (1: Both Teams and Calendar, 2: Only Calendar, 3: Only Teams).
- leave_threshold_number: Specify the minimum number of attendees to leave a meeting.
- leave_threshold_percentage: Specify the minimum percentage of attendees to leave a meeting.
- etc...

  ## Notes
- This script interacts with the Microsoft Teams web application using the Selenium WebDriver library. Ensure that you have the correct browser driver installed and compatible with your browser version.
- Be aware of the terms of use of Microsoft Teams and ensure that you use this script responsibly.

## License
This project is licensed under the _MIT License_. See the LICENSE file for details.

## Acknowledgments
The script is inspired by the need to automate the process of joining Microsoft Teams meetings.

Feel free to customize the README file with additional information, badges, screenshots, or any other relevant details about your project. 
