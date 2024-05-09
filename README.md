# ABAP
SAP ABAP Objects ->
These are generic pricing classes that I created in ABAP, to find the given price based on an access sequence.  This requires determining the correct ATABLE to use dynamically, based on the keys provided by an arbitrary internal table. Since I no longer have access to the SAP platform I have added these objects as PDFs.  These classes are important in that they use pointers for dynamic reads of up to 13 keys in ATABLES using the access sequence for pricing determination, once the appropriate ATABLE is determined dynamically based on the key fields provided. This is a REAL WORLD example of how to use ABAP objects to its fullest extent.  The ZCL_ATABLE_HELPER class PDF shows an example of how the the class is used in a program.  This is shown at the very beginning of the class document, therefore you will need to click next (>) through a few pages before the class code begins.

I created these generic pricing classes to when encountering the same exact problem:
https://community.sap.com/t5/application-development-discussions/find-a-tables-for-a-particular-condition-type/m-p/7239344#M1526066
