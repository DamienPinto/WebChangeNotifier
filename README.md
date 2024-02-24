# WebChangeNotifier
Scripts that monitor websites for changes in certain values and send E-mail (and potentially text) alerts.

# To Do:
1. Set up parameter file that accepts:
...a. The URL to check
...b. The frequency with which to check it.
...c. The E-Mail (or phone number?) to send notifications to.
...d. Which contact method is preferred (or both)
2. Write script that goes and checks an easy to check value given URL in specified in 1.a
...Perhaps a grocery list item?
...a. Go get HTML of page based on URL in 1.a.
...b. Create filter function specific to specified field of interest.
...c. Check a stored version of the field's last know value for comparison.
...d. Send notification if different based on 1.c & 1.d.
3. Set up script that loops this behaviour based on 1.b
