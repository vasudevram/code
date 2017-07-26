## Object snoop - experiment with Python special methodsOriginally published: 2010-09-05 16:46:48 
Last updated: 2010-09-05 17:54:50 
Author: Wai Yip Tung 
 
In Python, classes can define their own behavior with respect to language operators. For example, if a class defines __getitem__(), then x[i], where x is an instance of the clas, will be execute by a call to x.__getitem__(i).