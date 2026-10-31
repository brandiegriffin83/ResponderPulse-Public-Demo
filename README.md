# ResponderPulse-Public-Demo

Public demonstration of ResponderPulse, a first responder wellness check-in prototype. Fictional test data only.

## Public Demonstration

https://responderpulse-demo.streamlit.app

The public demonstration can be accessed through a web browser on a laptop, desktop computer, tablet, or smartphone.

## Requirements

- Python 3.10 or newer (recommended; clean-install compatibility not yet verified)
- Internet connection for downloading dependencies
- Streamlit
- Requests

## Installation Instructions

1. Download the repository from GitHub using **Code → Download ZIP**.
2. Extract the ZIP file to a folder on your computer.
3. Open Command Prompt or a terminal in that folder.
4. Install the required Python libraries:

   `python -m pip install -r requirements.txt`

5. Start the application:

   `python -m streamlit run ResponderPulse_Public_Test_Safe.py`

6. Open the local address displayed in the terminal, usually `http://localhost:8501`.

## Using ResponderPulse

1. Open Home / Your Profile.
2. Navigate to Wellness Check-In.
3. Enter fictional wellness ratings.
4. Submit the check-in.
5. Open My Results to review the feedback.
6. Explore the Wellness Toolkit, Support Resources, Coordinator Overview, and Presentation Demo.

## Important Limitations

ResponderPulse is a student prototype for demonstration and educational purposes.

The public version uses fictional information and keeps check-in records in Streamlit session state rather than permanently saving historical CSV records.

The public demonstration does not transmit check-in responses to the earlier Google Colab API.

ResponderPulse does not provide medical diagnoses or make fitness-for-duty, disciplinary, or employment decisions.

## Testing Status

The public demonstration has been tested through browser-based use on desktop and mobile devices. A separate clean-environment installation test is still pending.
