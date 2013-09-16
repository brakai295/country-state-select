Conditional 'state' selector for shipping forms
====================

When creating your own int'l shipping form, certain countries will require a 'state' selection field, while for most other countries the 'state' field is either optional or not required.

Based on my research, the following countries must have a 'state' in their shipping address:

 * USA
 * Canada
 * Australia
 * China (PRC)
 * Mexico
 * Malaysia
 * Italy

Here's a simple jQuery-powered form that offers a dropdown with prepopulated states/provinces if one of the above countries is selected (and a simple freeform fallback for all others).

[View example here](http://jsfiddle.net/WJFSd/).

Country codes based on ISO 3166-1.
