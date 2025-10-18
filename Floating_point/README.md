##  Floating-point talks and a patent  
Ugh, due to recent progress in floating point encodings much of my work is obsolete  
The recent developments files have references to the major papers in this area:  
See Floating-point_recent_developments.pdf in this directory for the web links  
The 1999 and later directories are my presentations on floating point  

### 1972 Optimal floating point format  
Observation that short floats can be zero extended by putting the exponent and mantissa signs in the middle  
Later observed that bit reversing the mantissa and intermixing it with the exponent, zero extension is only needed on the most significant end  

### 1977 Variable length data formats 
At the time was collecting computer instruction sets and made a list of floating point formats  
Matt Quinn saw it and put it into his conference paper, it seems that NASA was very concerned with floating point consistency (see 2023 Floating point-n-patent)  

### 1995 fltg-patent US589697A  
IEEE 754 sub-normals are difficult to handle in pipelined hardware  
And leading zeros counting and shifting the mantissa takes time  
Saw the oportunity to maintain normalization and using trailling zeros count  
to adjust the exponent and to offer gradual overflow at no additional cost  
The patent makes for difficult reading.  The terminology is improving, see the HUB references  
Was trying to get a process patent without relying on previously disclosed information  
(see: 2023 Floating-point-n-patent / Correspondence with IEEE 854 committee.pdf)  

### 1999 Case_for_non-IEEE-754_floating-point  
The floating-point advocated in this paper, herein called alt-754, was motivated by certain hardware and  
software complexities of IEEE-754. The process of finding solutions to IEEE-754 complexity illuminates the  
choices faced in floating-point architecture  
A more through examination of the issues in floating-point design shows that some features of IEEE-754 have  
viable (and superior) alternatives. One set of design decisions is shown by alt-754. Alt-754 has a simple  
mathematical model to motivate the design and implementation decisions.  

### 2001 Floating_point_reworked_Austin  
Done before using powerpoint slides, used Microsoft Word and Excel  
Contains taper diagrams and a rounding diagram  
Talk closely based on the 1995 patent  

The floating-point advocated in this paper, herein called Alt-754, was motivated by certain hardware  
and software complexities of IEEE-754. The process of finding solutions to IEEE-754 complexity  
illuminates the choices faced in floating-point architecture  

### 2001 Floating_point_reworked_C16  
Very similar presentation to the Austin talk  
This one given to San Antonio Computer chapter (C16)  
Includes the 1977 Variable_length_data_formats listing and the Austin file:  
An Engineer’s rework of IEEE-754 Floating-Point  

### 2019 Introduction_to_POSIT  
This is a presentation on John Gustafson's POSIT and some of my comments thereon  
It predates recent work: HUB format, PT-FLoat and Takum Aritmetic  
Since the talk, POSITs now typically use es = 2 and limit the regime length (slide 6)  

### 2023 Floating point-n-patent  
Patent is expired, was asked to do a talk on floating point including my patent  
One of the IEEE members mentioned the dificulties NASA had with floating point  

Incorporated some of their stories along with issues I see with IEEE 754  
John Gustafson's "Every Bit Counts" 2024 book does likewise  
He is an authority in these matters, my interests are in cirucit costs and performance  
There is much work in validating the new formats and short formats  

### 2025 Paper in preparation offering terminology improvements  
Half bit (see HUB papers), formal mantissa definition and residue definition  
