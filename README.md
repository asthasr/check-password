# check-password
Checks a password against the "Pwned Passwords" API. This is provided for the benefit of
the (sensible) people who feel uneasy about entering their passwords into someone else's
web page. The code here is intentionally simple; you can see that it does not send your
password across the Internet.

To use it on a Unix-like OS, you can use it as an executable:

    chmod +x ./check-password
    ./check-password

You will be prompted for the password you want to check.

On other systems, you should be able to run the script using Python 3, although it has
not been tested.
