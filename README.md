# BTreeParser
Parser for data.bt file for CS110 Final Project on B-Trees. © Del Rio, Lim 2018

## Instructions
1. Compile using `javac BTreeParser.java`.
2. Make sure that the `data.bt` file you want to decode is in the same folder as `BTreeParser.java  .
3. Run using `java BTreeParser [name of data.bt file]`.
4. Parsed file is named `parsedDataBt.txt`. If you want to change this, you can edit line 9 which is `PrintWriter parsed = new PrintWriter("[customized file name]", "UTF-8");`

## Issues
The parser prints an extra NodeID at the end. Ignore this. Suggestions for improvement would be highly appreciated!
