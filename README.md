# Tag-Predictor

## MACHINE LEARNING PROJECT
Ravi is a student who is new to Machine learning.He want to do a machine learning project.He
found out an interesting problem. He found out some questions and each question has id,title and
body. By seeing these,he wants to predict the tag for that question.
Data Field Explanation:
### Id - Unique identifier for each question

### Title - The question’s title
### Body - The body of the question
### Tags - The tags associated with the question in a space-separated format
### Example Data point
### Id : 1
### Title​: How to print Hello World in C language?
### Body ​:
    #include<stdio.h>
    Int main()
    {
    printf(“Hello World”);
    Return 0;
    }
### Tags ​: C
### Task - 1 : Data Preprocessing
    ➢ Remove Duplicate entries
    ➢ Separate out code-snippets from Body
    ➢ Remove stop words (Except 'C')
    ➢ Remove HTML Tags
    ➢ Convert all the characters into small letters
    ➢ Use SnowballStemmer to stem the words
### Task - 2 : Analysis of Tags
    ➢ Total number of unique tags
    ➢ Maximum number of tags per question
    ➢ Minimum number of tags per question
    ➢ Avg. number of tags per question
    ➢ Most Frequent Tags
### Task - 3 : Apply suitable model
    ➢ Split the data into test and train(80:20)
    ➢ Performance Metrics is F1-Score


#CSV Data Link : https://bit.ly/2w8eUd

