##  Floating-point talks and a patent  
Ugh, due to recent progress in floating point encodings much of my work is obsolete  

### 1972 Optimal floating point format  
Observation that short floats can be zero extended by putting the exponent and mantissa signs in the middle  
Later observed that bit reversing the mantissa and intermixing it with the exponent zero extension is only needed on the most significant end  

### 1977 Variable length data formats 
At the time was collection computer instruction sets and made a list of floating point formats  
Matt Quinn saw it and put it into his conference paper, it seems that NASA was very concerned with floating point consistency (see 2023 Floating point-n-patent)  

### 1995 fltg-patent US589697A  
IEEE 754 sub-normals are difficult to handle in pipelined hardware  
And leading zeros counting and shifting the mantissa takes time  
Saw the oportunity to maintain normalization and use the trailling zeros count  

### 2023 Floating point-n-patent  
Patent is expired, was asked to do a talk including my patent  
One of the IEEE members mentioned the dificulties NASA had with floating point  

Incorporated some of their stories along with issues I see with IEEE 754  
John Gustafson's "Every Bit Counts" book does likewise  
