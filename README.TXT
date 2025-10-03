TechSupport - the DodgySoft Technical support system, version #2.

This project is part of the material for the book.

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

This project is discussed in Chapter 6.


This project implements a second version of the technical support system 
example. It is an intermediate version intended to demonstrate the first
few changes discussed in this book chapter.


To start this program, create a SupportSystem object and execute the "start" 
method.

Then start describing your problem by typing in the terminal window.

24. This implementationimplements  all of the optional map operations, and permits null values and the null key.
25. K and V are the parameters, K = Key, V= Value 
    Some important methods are put (K Key, V Value) and get (object key).
    Yes, I do think it could be used for both parameters
26. The method size() will return the amount of entries
28. If you add "A" , "1" and "A" , "2" then 2 will overwrite the 1
29. As long as both entries have diffirent names and different keys they won't collide in any way shape or form.
30. You use the containKey() method of the Map interface.
31. it would return as null
32. You can ues the KeySet() method.
34. both store collections of objects.
    HashSet: No duplicates, no order.
    ArrayList: Allows duplicates, keeps order
35. HashSet: Words are unique,oreder is not keep
    ArrayList: Words can repeat, oreder is kept
36. if you split by just a single space, you may get empty strings.

Had problme with SupportSystem Class so will put 37 here
37. For it to work
    In SupportSystem
    import java.util.HashSet;
    
    Hash<String> inputWords = reader.getInput();
    
    if (inputWords.contains("bye")) {
        finished = true;
    }
    in Responder
    String response = responder.generateResponse(inputWords);
    

    
