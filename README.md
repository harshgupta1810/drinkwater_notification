# Water Reminder

This is a simple Python script that reminds you to drink water at regular intervals. It uses the `win10toast` library to display a notification on your Windows desktop, reminding you to drink water.

## Table of Contents

1. [Badges](#badges)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Documentation](#documentation)

## Badges

[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

## Installation

1. Ensure you have Python installed on your system. You can download Python from the official website: [Python.org](https://www.python.org/downloads/)

2. Install the required `win10toast` library. Open the terminal/command prompt and run the following command:

   ```
   pip install win10toast
   ```

3. Download the `water_reminder.py` script and place it in your desired directory.

## Usage

1. Run the Python script `water_reminder.py` in a Python environment.

2. The script will prompt you to enter the time interval in hours, minutes, and seconds between reminders. For example, if you enter 1 hour, 30 minutes, and 0 seconds, the script will remind you to drink water every 1 hour and 30 minutes.

3. After entering the time interval, the script will start running and will remind you to drink water at the specified intervals.

4. When the notification appears, take a break and drink water!

## Configuration

You can customize the time interval between reminders by changing the values in the `getTimeInput()` function. Simply modify the `hour`, `minutes`, and `seconds` variables to set your desired interval.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to open a pull request or create an issue on the GitHub repository.

## License

This project is open-source and licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code, but please provide proper attribution to the original creator, Harsh Gupta (Desparete Enuf).

## Acknowledgments

The Water Reminder was created by Harsh Gupta (Desparete Enuf) to encourage healthy habits of drinking water regularly. The code is provided here for reference and learning purposes.

## Documentation

The script uses the following concepts:

1. **User Input**: The script takes user input to set the time interval between reminders for drinking water.

2. **Time and Date**: The script uses the `time` and `datetime` modules to manage time intervals and log the reminder times.

3. **Notification**: The script uses the `win10toast` library to display desktop notifications, reminding the user to drink water.

4. **File Handling**: The script appends a log message to the `log.txt` file each time a reminder is shown, to keep track of when the reminders were triggered.

Feel free to use this Water Reminder script to maintain healthy hydration habits or use it as a basis for creating other notification-based reminder scripts. Stay hydrated and happy coding!
