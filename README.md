# tummy-trials-analyses-python

To use the scripts:

`$ persodump  your-user-identity  account-to-dump > account.json`

`Password: password of your-user-identity`

Unless you know the password of a CouchDB admin user, you'll probably end up using the same user for both:

`$ persodump jeffsco jeffsco > jeffsco.json`



`$ activity account.json id-of-trial > activity.json`

If you don't give a trial id, the script will list the trials in the DB.
