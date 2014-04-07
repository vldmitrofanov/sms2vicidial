sms2vicidial
============

Openvox g400p SMS spamer and vicidial leads converter

This is a set of bash/php scripts helping you send bunch of SMSes via GSM g400p card 
(something like spam) to generated mobile phone numbers and save those who replied to vicidial

Actully this was made for Philippines, but its possible and easy to convert it to work with other countries


1) We are generating numbers, like 0917-0000000 to 0917-9999999, filtering "gold" numbers and saving them to text files 1000 numbers each

2) Sending SMSes. The script will check spans condition, prefixes, provider availability. If all are ok, will start sendind SMSes in cycle specified amount of files with generated numbers

3) If anyone will reply back by txt -> store them to vicidial_list to cpecified list and their message to "comments" field
