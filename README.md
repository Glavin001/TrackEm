TrackEm
=======

Node.js server for tracking email read receipts via images requests with unique identifiers. 

## How it works
Add the unique external image to your email and when the email is read their Email Client will request the image resource from your server. Each image has a unique identifier and can be tracked for when it was requested -- this logging the read date of your email -- and can also track other importation from the request headers, such as Operating System and potentially location. 
