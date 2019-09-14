# BigNbClust
:exclamation: This is my attempt at adapting  NbClust to work with large matrices. The original project's homepage: https://sites.google.com/site/malikacharrad/research/nbclust-package  

In using the NbClust function, I found that with larger matrices, R tended to run out of memory or crash. I have attempted to remedy this by replacing several of the most resource hungary functions called (`eigen`, `var`, and `hclust`) with faster alternatives. I have only tested this with a few matrices so far, so do not use it unless you know what you are doing and have checked that I haven't messed anything up. In which case please let me know (as you should if you notice any problems or have ideas about how it could be improved further).
