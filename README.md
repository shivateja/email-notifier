#EMail Notifier

A simple python scripts that checks your gmail for new emails and shoots a GNOME notification if any unread mails are
found.
Add it to cron so that it checks your mail periodially. Make sure to add the environment variable of display for the
notification to show on the right screen. For ex. add "*/5 * * * * env DISPLAY=:0.0 /path/to/file/email.py"  to cron to run the script every 5 minutes.