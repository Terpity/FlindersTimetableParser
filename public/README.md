# Flinders Timetable Parser

## Overview
Flinders Timetable Parser is a web-based tool designed to help students at Flinders University convert their timetable JSON file into an iCal format. This allows easy import into calendar applications like Google Calendar, Outlook, or Apple Calendar.

## Features
- Generate a single calendar for all classes or separate calendars for each topic.
- Optionally add semester weeks, including mid-semester breaks, SWOTVAC, and exam periods.
- Fully client-side processing ensures privacy—no data is sent to external servers.

## Usage
1. Visit [Compass](https://students.flinders.edu.au/compass) and ensure your session is saved in your browser cookies.
2. Download your timetable JSON file from [this link](https://students.flinders.edu.au/flinders-services/student-portal/timetable.json).
3. Open the Flinders Timetable Parser webpage.
4. Upload the JSON file, select your preferences, and click "Generate."
5. Download the generated iCal file and import it into your calendar software.

## Troubleshooting
- If you encounter a 401 error, try clearing cookies on Compass and reloading the timetable API link.
- Ensure you can view your timetable in Compass before attempting to use the parser.

## Disclaimer
This tool runs entirely in your browser. No data is sent to external servers, and you can verify this by monitoring network activity in Developer Tools. If privacy is a concern, you can use the tool offline.

The project is open-source and available on [GitHub](https://github.com/Terpity/FlindersTimetableParser). Feel free to fork and modify it as needed.

## License
This project uses the MIT License. See the source code for details.

