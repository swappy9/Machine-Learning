
Came up with my own technique to handle high-dimensional categorical variables (haven't found anything related to it, but I am not sure if there is any written paper about it):

Step1: If the categories are numerical, convert it to the binary form of the number and if categories are textual, first convert it to a number using LabelEncoder in python and then to the binary form of it.

Step2: Convert each digit of the binary number to a column with values '0' and '1'

Step3: Treat these newly created variables as usual binary categorical variable

Pros:
- Simple
- Memory-Efficient
- Fast

Cons:
- Somewhat less accurate
- Pain to convert it to binary -> individual column
