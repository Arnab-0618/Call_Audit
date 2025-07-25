# Call Audit

Call Audit is a Python-based project for analyzing and auditing call audio data. It leverages audio processing, data management, and scheduling utilities to extract insights from call recordings.

## Features
- Audio preprocessing and feature extraction
- Data management and storage
- Scheduler for automated tasks
- Integration with OpenSMILE for audio analysis
- Secure credential management

## Project Structure
```
create_tables.py           # Script to create database tables
main.py                   # Main entry point for the application
myaudio.wav               # Example audio file
opensmile_output.csv      # Output from OpenSMILE
output.csv                # General output file
requirements.txt          # Python dependencies
scheduler.py              # Task scheduler
scheduler.log             # Scheduler logs
token_manager.py          # Token management utility
credentials/              # API keys and secrets
src/                      # Source code
  └── utils/              # Utility scripts
  └── config/             # Configuration files
  └── database/           # Database models and scripts
  └── models/             # Data models
  └── routes/             # API routes
  └── schemas/            # Data schemas
logs/                     # Application logs
data/                     # Audio and processed data
```

## Getting Started
1. Clone the repository:
   ```powershell
   git clone https://github.com/gunjankhullar15/Call-audit.git
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Run the main application:
   ```powershell
   python main.py
   ```

## Requirements
- Python 3.10+
- See `requirements.txt` for all dependencies

## Usage
- Place your audio files in the `data/` directory.
- Configure credentials in the `credentials/` folder.
- Use the provided scripts for preprocessing, analysis, and scheduling.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.
