# ADI will be done in C++, NOT Java

# Time and Space Complexity

Strings:

String S1 = "CPP";\
String S2 = "CPP";\
Sout(S1 == S2); //Returns true\
Sout(S1.equals(S2)); //Returns true\
String S3 = new String("CPP");\
Sout(S1 == S3); //Returns false\
Sout(S1.equals(S3)) //Returns true\

This is because when you use New you create a brand new object, which otherwise would be a pointer to the same value.


Collection/Collections:

Collection - Collection framework\
Collections - Utility class

Collection sub-parts\
List, Set, Queue\
List - Array, Linked, Vector, Stack\
Set - Hash, Linked Hash etc.\

