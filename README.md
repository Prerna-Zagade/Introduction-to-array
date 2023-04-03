# Introduction-to-array

Array Introduction

Arrays are used to store multiple values of same datatype in a single variable, instead of declaring separate variables for each value. To create an array, define the data type (like int,char) and specify the name of the array followed by square brackets []. Within the square brackets mention the number of elements to be stored.

Example :

int numbers[5]; char name[20]; image Access the Elements of an Array To access an array element, refer to its index number. The indexing of an array starts from 0 and ends at value one less than the length or total number of elements in the array. Syntax: array_name[index_number];

Example:

numbers[3] ---> Access to the element stored at third index position of the array 'numbers'. Loop Through an Array You can loop through the array elements with the for loop.

Example:

for(i=0;i<length_of_array-1;i++) { printf("%d\n",numbers[i]); //Prints all the elements in array 'numbers'. }

![Screenshot 2023-04-02 045830](https://user-images.githubusercontent.com/124857711/229418645-0441e857-1e15-4051-9222-99a786555a12.png)
