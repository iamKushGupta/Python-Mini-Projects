# Send Emails from CSV File

This project contains a simple bulk email script
which sends the same message to a list of recipients.


## Dependencies

This project only requires the Python standard library
(more specifically, the `csv`, `email`, and `smtplib` modules).


## Running the script

The script requires two configuration files:

* `emails.csv` should contain the email addresses to send the message to.
* `credentials.txt` should contain your SMTP server login credentials,
  with your user name and your password on sepate lines,
  with no additional whitespace or other decorations.


```
python Send_emails.py
```

