creddump is a python tool to extract various credentials and secrets from Windows registry hives. It currently extracts:
  * LM and NT hashes (SYSKEY protected)
  * Cached domain passwords
  * LSA secrets

It essentially performs all the functions that bkhive/samdump2, cachedump, and lsadump2 do, but in a platform-independent way.

It is also the first tool that does all of these things in an offline way (actually, Cain & Abel does, but is not open source and is only available on Windows).