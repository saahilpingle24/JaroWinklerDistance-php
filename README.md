<h1>Jaro Winkler - php</h1>
A crude implementation of the JaroWinker algorithm using php.

<span style="font-size:0.8em"><b>Description:</b></span>
<br>
The code makes use of a threshold value. The threshold value
can be used to determine how similar the input strings are.
    
For example, if the threshold is set at 90 and the two strings 
that are compared return a score of 90 or more, then the similarity level would be high, else it would be low.
  
<span style="font-size:0.8em"><b>Usage:</b></span>
<br>
Include the <code>jaroWinkler.php</code> file, and then make a call to the
jaroWinkler function as - 
        
    jaroWinkler('string 1','string 2','prefix value','threshold value');
    
    The prefix value is standardized to 0.1 as per the Jaro-Winkler algorithm. 
    
    Source: http://en.wikipedia.org/wiki/Jaro%E2%80%93Winkler_distance
    
    