# WebChangeNotifier
Scripts that monitor websites for changes in certain values and send E-mail (and potentially text) alerts.

# To Do:
- [ ] Set up parameter file that accepts:
  1. The URL to check
  2. The frequency with which to check it.
  3. The E-Mail (or phone number?) to send notifications to.
  4. Which contact method is preferred (or both)
- [ ] Write script that goes and checks an easy to check value given URL in specified in 1.i. Perhaps a grocery list item?
  1. Go get HTML of page based on URL in 1.i.
  2. Create filter function specific to specified field of interest.
  3. Check a stored version of the field's last know value for comparison.
  4. Send notification if different based on 1.iii & 1.iv.
- [ ] Set up script that loops this behaviour based on 1.ii.
