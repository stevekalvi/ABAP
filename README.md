# ABAP OBJECTS
These are generic ZCL pricing classes that I created in ABAP, to find the given price based on an access sequence.  This requires determining the correct ATABLE(S) to use dynamically, based on arbitrary interspersed keys provided by an internal table. These classes are important in that they use pointers and field symbols for dynamic table and key determination. This includes reads consisting from one to thirteen keys on ATABLE(S) using the access sequence for pricing determination.  The reads occur once the ATABLE(S) are determined dynamically based on the key fields provided by the arbitrary internal table. This is a REAL WORLD example of how to use ABAP objects to its fullest extent. It is a deep dive using two classes, pointers, and field symbols. The ZCL_ATABLE_HELPER class PDF shows an five examples of how the the class is used in a program, each example containing different key fields.  This is shown at the very beginning of the class document, therefore you will need to click next (>) through a few pages before the class code begins. Since I no longer have access to the SAP platform I have added these objects as PDFs.

I created these generic pricing classes when encountering the same problem nearly a year earlier:
https://community.sap.com/t5/application-development-discussions/find-a-tables-for-a-particular-condition-type/m-p/7239344#M1526066

I have attached the above forum conversation as a PDF labeled Solved in this repository
