# rarff

Rarff - Ruby ARFF Library

Rarff is a Ruby library for dealing with Attribute-Relation File Format (ARFF) files. ARFF files are used to specify data sets for data mining and machine learning.


## License

Copyright (c) 2006-2012 Andy Payne
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

	* Redistributions of source code must retain the above copyright notice,
        this list of conditions and the following disclaimer.
	* Redistributions in binary form must reproduce the above copyright notice,
        this list of conditions and the following disclaimer in the
        documentation and/or other materials provided with the distribution.
	* Neither the name of the COPYRIGHT OWNER nor the names of its contributors
        may be used to endorse or promote products derived from this software
        without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


## Todo

* Spaces or quotes in nominal types
* Commas in quoted attributes or in nominal types
* Add error checking/validation
* Creation of sparse ARFF files
* Missing values - '?'
* Dates - do some work to create, translate, and interpret date format strings.


## Weka

Weka is "a collection of machine learning algorithms for data mining tasks."
(http://www.cs.waikato.ac.nz/ml/weka/)  Weka accompanies the following book:

Ian H. Witten and Eibe Frank (2005) "Data Mining: Practical machine learning
tools and techniques", 2nd Edition, Morgan Kaufmann, San Francisco, 2005.


## ARFF Information

ARFF files are similar to CSV files, but are strongly-typed, have a pre-defined
set of data types, and include a sparse representation.

Links to documentation:

* http://www.cs.waikato.ac.nz/~ml/weka/arff.html
* http://sourceforge.net/projects/weka/files/



