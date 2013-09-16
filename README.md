Conditional 'state' selector for shipping forms
====================

When creating your own int'l shipping form, certain countries will require a 'state' selection, for most other countries the 'state' field is either optional or not required.

Based on my research, the following counties require a 'state' in their shipping address:

 * USA
 * Canada
 * Australia
 * China (PRC)
 * Mexico
 * Malaysia
 * Italy

Here's a simple jQuery powered form that offers a textfield for 'state' by default and swaps it for a dropdown if any of the above countries are selected. 

Country codes defined by ISO 3166-1.

