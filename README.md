# Contact-Trigger-with-future-annotation-asynchronous-apex

Create a field called No of contacts in the account object. When we add the contacts the field will populate in account detail pag. When we delete , undelete contacts it should be updated.

Future methods only support primitive data types or collections and do not support sObjects as arguments.

sObject can’t be passed as arguments to future methods because the sObject might change between the time we call the method and the time it executes

So, instead of passing sObject List in the parameter, passed list of Account Ids in the parameter.
