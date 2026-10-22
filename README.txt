Afnan Shahzad Dawakhana - Updated Version 2

Features:
- Daily token sequence starts from 001 on each new date.
- Manual Reset button resets today's counter to 001 on next patient without deleting patient records.
- Multiple patient selection and batch reprinting.
- Print Preview window with print/close controls.
- Disease/Problem remains in software and Excel export, but is not printed on slips.
- Date filtering and Excel (.xlsx) / CSV export.
- Clinic name, address, phone and hours can be changed from Settings.
- Patient database remains local at %LOCALAPPDATA%\AfnanDawakhana\afnan_dawakhana.db.

To rebuild on GitHub:
1. Replace main.py in repository with this main.py.
2. Replace .github/workflows/build-windows.yml with build-windows.yml from this folder.
3. Commit changes, open Actions, wait for success, download artifact AfnanDawakhana-Windows-v2.
4. Extract ZIP to get AfnanDawakhana.exe.

IMPORTANT DATABASE NOTE:
The updated application uses the same local database path and retains existing patient records.
Before first use, it is wise to make a backup copy of afnan_dawakhana.db from:
%LOCALAPPDATA%\AfnanDawakhana\
