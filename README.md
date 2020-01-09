# UnICOrN
Unique Isoform CDNA Orthogonalization Network

***********************************************************************
Unique Isoform CDNA Orthogonalization Network (Version 1.11)
Copyright (C) 2015 Luke Burks
***********************************************************************

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

***********************************************************************

1.Setup
	-For UnICOrN to run, the computer being used must have Java installed.
		If Java is not installed, the installation link can be found here <http://www.java.com/en/download/>. 
	 
	-Ensure that any RNA sequence files are in the same local directory folder as the UnICOrN.jar file.
	
2. Basic Instructions
	-Input the name of the main file. This file will be searched for unique sequences. 
		Main files should be formatted like the included "exampleMain.txt". 
		Main files must be .txt format.
		When you input the name it is not necessary to append .txt to the end. You can, but you don't have to. 
		Please ensure that the file actually exists in the local folder, or the program will assume you are 
		not intellectually qualified to use it and may call you mean names. 
		
	-Input the comparison files. These files will be searched to verify unique sequences in the main file. 
		Type the name of the file in the provided box. 
		Comparison files should be formatted like the included "exampleComparison.txt". 
		Comparison files should be in .txt format. 
		Click the "Add Comparison File" button, the file will be added to a list and the box cleared for the next file. 
		Once again, it is not necessary to append .txt to the file name.
		You can add as many comparison files as you'd like. 
		Once again, please ensure that the file actually exists in the local folder, or the program will assume you are 
		not intellectually qualified to use it and may call you mean names.  
	
	-Ensure the minimum and maximum sequence numbers are set properly. 
		These numbers each range from 3 to 20 and can be set with the adjoining sets of arrows. 
		Please ensure the minimum number is lower than the maximum number, otherwise the program
		will assume you are not intellectually qualified to use it and may call you mean names. 
		
	-Input the name of the output file. This file will be used to store the resulting unique sequences. 
	
	-Press the "Run UnICOrN" button.
	
	-The unique sequences will be output to the specified text file in order of length. 
		Next to each sequence will be its character location in the main file. 
	
3.Version Change Log
	-1.1
		Removed programs tendancy to call the user mean names
		Added automatic error checking for .txt files format
		Added a magenta background
		
	-1.11
		Fixed a read issue in the comparison file parser
		

		
