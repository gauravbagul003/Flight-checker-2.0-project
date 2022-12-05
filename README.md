# Flight-checker-2.0-project
Now that our program is working as expected, all that's left to do is to notify our customers when there is a good deal!

1. Create a method in the NotificationManager called send_emails() . Use what you have learnt about smtplib and sending emails to send all our customers in the users sheet from Google Sheets the message that contains the flight deal.

NOTE: when sending emails, it won't like the "£" symbol, you might get an error

You can solve this by encoding the message with UTF-8 e.g. https://stackoverflow.com/questions/9942594/unicodeencodeerror-ascii-codec-cant-encode-character-u-xa0-in-position-20#answer-9942885

2. You can generate a Google Flight link with all the information pre-populated so that users can book the flights by clicking on the link in the email.

e.g. This is the Google flight link for a flight from STN to SXF from 2020-08-25 to 2020-09-08.

https://www.google.co.uk/flights?hl=en#flt=STN.SXF.2020-08-25*SXF.STN.2020-09-08

Figure out which part of the URL needs to be replaced and construct a URL when for any cheap flights. Send this URL along with the message when you email your customers.

