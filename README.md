# ip-regex
This regex matches IPv4 and IPv6 format (compatible with IPv6 short format)

_`DISCLAIMER: USE AT YOUR OWN RISK. DO NOT USE THIS REGEX FOR SECURITY APPLICATIONS UNTIL YOU HAVE TESTED IT MULTIPLE TIMES. ERRORS CAN OCCUR.`_


### How to use ? 
1.  Copy and paste the content in the `regex.txt` file.
2.  If you want to check an input, just use it like this (don't forget to sanitize and trim the text input before).
3.  To search multiple IPs in a text file, remove the "`^`" at the beginning and the "`$`" at the end.
  
### Features: 
- Supports general IPv4 formats shortened shapes.
- Supports general IPv6 formats shortened shapes.

### Testing:
1. Go to https://regex101.com/
2. Paste the `regex.txt` content in the regular expression field.
3. Paste the `ip-samples.txt` content in the text string.
4. Try with your own IPs.

### Notes and improvements:

This regex was tested with more than 1,000 IPs with Python and was working.
However, there are also thousands of IP formats. \
`This is why many of the IP regex patterns found online are BAD and easily breakable !` \
This one does not except the rule. So if an IP doesn’t match this regex, or a field that appears valid even though it’s not a valid IP, please correct the regex and share it! 
