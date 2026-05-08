# 📅 Cycle Calendar Generator (iCalendar Format)

This Python project is a specialized utility designed to predict and export health-related cycles into a standard calendar format. It was developed as a practical exercise for the **Digital and Computer Sciences (NSI)** French Baccalaureate.

## Overview
The application calculates future dates for a 28-day cycle and generates a file compatible with the **iCalendar (RFC 5545)** standard. This allows users to import their data directly into digital calendars like Google Calendar, Outlook, or Apple Calendar.

## Key Features
- **Date Arithmetic Engine**: A custom implementation to handle date additions, accurately managing:
  - Transition between months of different lengths (30 vs 31 days).
  - Leap year calculations for February (28 vs 29 days).
  - Year-end transitions.
- **Cycle Prediction**: Automatically generates recurring events for a 100-day period based on an initial date.
- **iCalendar Export**: Formats data into the `VCALENDAR` standard, including `VEVENT` blocks for seamless integration.
- **Validation Suite**: Includes unit tests using `assert` and integration testing with the `ics` library to ensure data validity.

## Technical Stack
- **Language**: Python 3.x
- **Libraries**: `calendar` (for leap year logic), `ics` (for validation).
- **Key Concepts**: Logic Gates, While-Loop Iteration, Tuple Unpacking, String Formatting, and Data Serialization.
