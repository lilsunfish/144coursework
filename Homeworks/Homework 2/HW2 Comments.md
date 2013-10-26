# Comments on HW2

Author: Oliver  
Date: 2013-10-24

#### Overall

This is very good work. The main thing holding it back is the relative simplicity of the answers in problem 7. You two are doing great with this stuff, so be careful not to take the easy path!

#### Correctness

The conceptual section is excellent. Problem 7, however, passes the tests in letter only; all three functions should reference the dictionary, in order to avoid the whims of our orthography. Also, the method for searching for vowels leads to some anomalies, as indicated in my specific comments.

#### Readability

The code is very readable. The one exception is the otherwise clever substring reversal trick, which is difficult to read compared to other options like the reversed() method Pranav mentioned in class. (That's not a complaint, just a note for the future.)

#### Documentation

Very clear. Nicely done.

#### Efficiency

Overall this is quite efficient. See my specific comment about Problem 3, where there are ways to avoid duplicating the anonymous function (or in the earlier version, the return statement).