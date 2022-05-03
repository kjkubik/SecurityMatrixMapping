# SecurityPositionalMatrixMapping
This is a way to mask data needing to be kept secure within a company and also be able to undo the mapping if necessary. 

## Positional Matrix Mapping Introduction
If a entity needs to keep a particular data field secure and ultimately untracable, I have figured out a way to do so that I would like to share with you.

Say you wanted to successfully scrabble a data field within a database table. Here are the steps you would take.

1. Extract the data field's value from each record into an object.
2. Create a matrix assigning each character its own unique character within a position. 
3. Run the social security numbers through an algorithm using the positional matrix mapping you have just created, assigning each character another character dependant on its position.  
4. Wa-la you have a masked data field. Now all that must be done is updating the table with the masked field.

Note: To unscrabble the data field to check for validity, you would use the transverse of the original matrix.

## Conclusion
There are several ways of creating the algorithm above. No two solutions must be the same. I do leave you with example code so that you have an example of how complete masking can be done; however, I urge you to only copy the parts of my code you need. Every organization should contain their own unique set of matrices to mask their data. Furthermore, I also recommend coming up with a solution so that these matrices can be changed on a regular bases. 

