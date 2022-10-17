This is console application built in .Net Core. 

There is a node class which contains fields and properties. This class has two main methods i.e. Insert and PostOrderTraverse. 
Insert method is used to recursively calls the insert method for the tree until it finds the open slot. 
PostOrderTraverse method is used to display the tree in Postorder Traversal.

There is BinaryTree class which creates an object of Node class, and it calls the methods of Insert and PostOrderTraverse of 
Node class.

UserInput is static class with static method of CheckUserInput. This method validates the user input.

In Program class, user chooses the option for the Console app. There are 2 options in switch block i.e., option 1 is used to run 
the app for string given in technical exercise while option 2 takes the user input at run time. 

This user input needs to pass the validation.

Program can be terminated by entering the option other than "1" and "2".
