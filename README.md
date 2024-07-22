
# Ephemeris Generation Tool

## Overview

This tool generates ephemeris data for celestial objects using the JPL Horizons system. It converts the data into the VLT (PAF) format and can save it to a file or print it to the console. The tool is designed to be used with the INO (International Observatory) coordinates.

## Features

- Generates ephemeris data for specified celestial objects.
- Converts ephemeris data to VLT (PAF) format.
- Saves ephemeris data to a file.
- Prints ephemeris data to the console.

## Dependencies

- `astroquery`: For querying the JPL Horizons system.
- `datetime`: For handling date and time operations.

You can install `astroquery` using the following command:

```sh
pip install astroquery
```

## Usage

1. Clone the repository:

```sh
git clone https://github.com/yourusername/ephemeris-generation-tool.git
cd ephemeris-generation-tool
```

2. Run the script:

```sh
python main.py
```

3. Enter the required information when prompted:

- Object ID (e.g., 499 for Mars)
- Start epoch (in the format YYYY-MM-DD HH:MM:SS)
- End epoch (in the format YYYY-MM-DD HH:MM:SS)
- Step size in seconds
- Position angle in degrees

## Example

```
Enter the object ID (e.g., 499 for Mars): 499
Enter the start epoch (YYYY-MM-DD HH:MM:SS): 2024-07-23 00:00:00
Enter the end epoch (YYYY-MM-DD HH:MM:SS): 2024-07-24 00:00:00
Enter the step size in seconds: 3600
Enter the position angle in degrees: 45
```

## How It Works

### Generating Ephemeris Data

The `generate_ephemeris` function generates ephemeris data for a specified object and time range using the JPL Horizons system.

### Converting to VLT Format

The `convert_to_vlt_format` function converts the ephemeris data into the VLT (PAF) format.

### Saving Ephemeris Data

The `save_ephemeris_to_file` function saves the converted ephemeris data to a file.

### Printing Ephemeris Data

The `print_ephemeris` function prints the ephemeris data to the console.

## INO Coordinates

 Here is our lovely INO (International Observatory) coordinates by default:

- Latitude: 33.587 degrees
- Longitude: 51.382 degrees
- Altitude: 3.6 kilometers

## License

This project is for INO(Iran National Observatory).
