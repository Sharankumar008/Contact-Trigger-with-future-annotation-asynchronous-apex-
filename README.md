# Contact-Trigger-with-future-annotation-asynchronous-apex-

Future methods only support primitive data types or collections and do not support sObjects as arguments.

sObject can’t be passed as arguments to future methods because the sObject might change between the time we call the method and the time it executes

So, instead of passing sObject List in the parameter, passed list of Account Ids in the parameter.
