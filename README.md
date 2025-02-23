# Program 5: MPLS Dog Management System
**Programs 5 and 6 will be similar in functionality.**

The MPLS Dog Boarding company would like for you to create an application that allows for a care attendant to be able 
to create, retrieve and update dog records from the system. MPLS Dog Boarding can only have 12 dogs in their care at a time. When you select the option to **create** a dog record.  You will 
enter the dog's id, dog's name, weight and dog's age.  Once information is entered for a dog, the program will display
entered information and reprompt the care attendent to select an option to exit, display, create or update dog record.  

When the **update** option is selected the care attendant will be presented with option to enter the dog's id number and reassign information
pertaining to dog.  

When the **retrieve** option is selected, the user will be able to enter the dog's id and be presented
with dog information.

**Hints**
- Consider the use of parallel arrays to store dog Data.  **Declare your arrays at the class level and not in the main method.**
- Consider commenting your code and writing the code in the main method before modularizing the program.

Your program should operate similarly to the program shown in the .gif below The .gif below show three iterations of running the program

![Alt text](https://instructorc.github.io/site/slides/java/images/methods/sample_output_prog5.gif "Program 5 Execution Example")



#### Listed below is a detailed explanation of the requirements needed to complete the dog management system.  

## Requirement 1 (5 Points) 
Variables are properly declared and initialized; Use of Scanner Object to read input from console. Make use of constant final variables. 
Whenever possible, make sure to declare all variables that will hold data along with declaring final variables that will not change during runtime.
Proper structure used for allowing the end-user to continously select menu option until a sentinel value is entered.

## Requirement 2 (5 Points) 
Input/Output of all necessary information for each item entry; Program properly makes use of arrays to structure data;
Program only accepts dog id numbers that have been entered.

## Requirement 3 (5 Points) 
The program should consist of a minimum of 5 methods.  
    1. A welcome method that describes the program.  *Already provided via starter code
    2. A method to display the selection prompt *Already provided via starter code
    3. A method that allows the care attendant to enter a record.  
    4. A method that allows the care attendant to update a record and 
    5. A method that allows the care attendant to retrieve an existent record.

## Requirement 4 (5 Points) 
Style - Proper use of comments, spacing, in program; use of descriptive variable names

## Requirement 5 (5 Points) 
Program is submitted by the due date listed and pushed to assigned GitHub Repository; Repository contains a minimum of three commits.

## Extra Credit (2 Points)
Add a new menu number option that allows the end-user to temporarily display the current list of dogs with age in human years. 
 - The list calls a method that recursively iterates through the list and displays the name of the dog and the dog’s age in human years.  Let’s assume that 1 dog year equals 15 human years.
    - Consider what will be the base case when making the recursive call.

## Submission Instructions for Program 5
For Program 5, you will need to submit two items:

1. **The GitHub URL to your Repository.**
   - Your code should be reflected in the assigned GitHub repository provided to you by the instructor.  In Sakai, you will need to submit the link to your repository by the due date and time listed in the write-up. Make sure you receive confirmation from Sakai that your assignment has been submitted.

2. **A recording of you explaining each line of your code.**
   - You can use any recording tool of your choice, or opt for a free resource like [RecordScreen.io](https://recordscreen.io).
   - The video doesn't need to be lengthy; just briefly walk through each line of your code.
   - Save the recorded file to your computer and, for convenience, upload it to your school-issued Office 365 OneDrive account at [office.com](https://www.office.com).
   - Paste the link to your recording in the assignment comments.

