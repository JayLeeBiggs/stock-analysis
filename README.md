# stock-analysis

•	Results
o	The analysis is well described with screenshots and code (4 pt).
•	Summary
o	There is a detailed statement on the advantages and disadvantages of refactoring code in general (3 pt).
o	There is a detailed statement on the advantages and disadvantages of the original and refactored VBA script (3 pt).
#Title
Analysis of re-factoring stock VBS script and output

#Overview
The stock analysis VBS (Visual Basic Script) was initially created to analyze only a single stock. It organically morphed upon
request to cover twelve stocks in total. Due to the organic growth of the content, a decision was made to refactor the VBS - to 
clean up the code and make it easier to read, and, hopefully, the cleaned up code would run faster.

#Results
The refactoring did make the code easier to read. It removed and cleaned up extraneous code by condensing the code into a cohesive
and compact nested loop structure. However, it did not reduce run time.



#Summary
In general, refactoring code would appear to have the advantage of allowing for: 
  1. A review of the code for accuracy
  2. Cleaning up the old code and condensing it to a simpler structure
  3. Checking for fit or purpose of the code to the desired output
  4. Allow for more appropriate commenting for later users.

The disadvantages of refactoring code would appear to be:
  1. The possible deviation of original intent and losing the needed output due to refactoring
  2. The time involved in refactoring - especially as the code body gets larger and larger
  3. A failure to achieve performance enhancement after the time invested in refactoring.
