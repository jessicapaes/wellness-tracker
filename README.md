# Wellness Tracker

A comprehensive daily wellness tracking application built with Streamlit. Track your mental health, physical wellness, menstrual cycles, trauma responses, and more through an intuitive web interface.

## Features

- **Daily Check-ins**: Track mood, safety levels, energy, sleep, and daily wins
- **Comprehensive Health Tracking**: Physical symptoms, emotional responses, menstrual cycles
- **Trauma-Informed Design**: Gentle language and trauma-aware features
- **Calendar View**: Visual monthly overview of your wellness patterns
- **Analytics Dashboard**: Trend analysis and correlation insights
- **Data Export**: Download your data as CSV files
- **Australian Resources**: Crisis support contacts for Australian users

## Quick Start

### Local Development

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run wellness_tracker_complete.py
   ```
4. Open your browser to `http://localhost:8501`

### Online Access

Access the live app: [Your Streamlit Cloud URL]

## Requirements

- Python 3.7+
- Streamlit
- Pandas
- NumPy
- Plotly

## Database

The app uses SQLite to store your wellness data locally. Your data file (`wellness_tracker.db`) is created automatically and contains all your tracking history.

## Privacy & Data

- All data is stored locally on your device
- No data is transmitted to external servers (except for the hosting platform)
- You can export your data at any time
- Delete the `.db` file to remove all data

## Usage

1. **Daily Check-in**: Complete your wellness check-in each day
2. **Calendar View**: Review patterns and trends over time
3. **Analytics**: Explore correlations and insights in your data
4. **Export**: Download your data for backup or external analysis

## Support

If you're experiencing a mental health crisis, please reach out:

**Emergency (Australia)**: 000

**Mental Health Crisis**:
- Lifeline: 13 11 14
- Suicide Call Back Service: 1300 659 467
- Beyond Blue: beyondblue.org.au

## Technical Notes

- Built with Streamlit framework
- Uses SQLite for data persistence
- Responsive design for mobile and desktop
- Australian English spelling throughout

## Contributing

This is a personal wellness tool. If you'd like to suggest improvements:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## Disclaimer

This app is for personal wellness tracking only and is not a substitute for professional medical or mental health care. Always consult healthcare professionals for medical concerns.
