# Crash Data Auto-Load

Place your crash data CSV file in this folder as `crashes.csv` to enable automatic loading.

## Usage

1. Rename your Virginia crash data CSV file to `crashes.csv`
2. Place it in this `data/` folder
3. Refresh the application - data will load automatically

## File Format

The CSV file should follow the Virginia Roads crash data format with columns including:
- Document Nbr
- Crash Year
- Crash Date
- Crash Severity (K/A/B/C/O)
- Route Name
- Collision Type
- Weather
- Light Condition
- X (longitude), Y (latitude)
- And other standard crash data fields

## Notes

- If no `crashes.csv` file is found, the application will display the manual upload interface
- Large files may take a moment to load on startup
- You can still upload different files manually after auto-load
