## Arbitrary order attribute writing with ElementTreeOriginally published: 2008-07-31 21:34:00 
Last updated: 2008-08-01 19:24:34 
Author: Orri Ganel 
 
Modified version of ElementTree with two additional parameters to the write() method: "sortflag" and "sortcmp".  "sortflag" defaults to "default", which results in unmodified behavior.  "sortcmp" defaults to None, which results in unmodified behavior.  See discussion for usage and justification.  Changes made begin on line 655.