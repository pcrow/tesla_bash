# tesla_bash
Bash script using the Tesla Owner API to monitor your vehicle's location

This script uses the Tesla Owner API to talk to your Tesla vehicles.
It uses ANSI escape codes to draw buttons and accept mouse clicks.
All Tesla credentials are store locally.  Saving the password is optional.
This is not intended to implement every possible feature, though it may be
expanded in the future.

The most useful feature for me is setting a home address, which it then uses
Google Maps to find how long it would take to drive home from the car's current
location.  Using that, it can set alerts to tell you when the car is almost home.
This means I can get the tea kettle on and with hot water just in time when my
wife gets home!
