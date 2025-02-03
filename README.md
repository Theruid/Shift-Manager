# Shift Manager

A web-based application for managing and scheduling support specialist shifts efficiently.

## Features

- Automated shift scheduling for support specialists
- Holiday management and tracking
- Excel export functionality
- Shift conflict detection and resolution
- User-friendly web interface
- Configuration management
- Monthly shift distribution optimization

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Theruid/Shift-Manager.git
cd Shift-Manager
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure

- `/app.py` - Main application file containing the Flask server and core logic
- `/static/` - Static files (CSS, JavaScript)
- `/templates/` - HTML templates
- `/shifts/` - Directory for storing shift data
- `/config.json` - Application configuration
- `/holidays.json` - Holiday data storage

## Usage

1. Start the application:
```bash
python app.py
```

2. Access the web interface at `http://localhost:8080`

3. Upload specialist schedule data and configure shift parameters

4. Generate and manage shifts through the web interface

## Configuration

The application can be configured through the web interface or by editing `config.json` directly. Configuration options include:
- Shift timing preferences
- Specialist availability rules
- Holiday settings
- Export format preferences

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is proprietary software. All rights reserved.
