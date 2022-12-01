# Simple-Calculator-in-C-language
Here I have Created a Simple Calculator in C language(as I am a Beginner).
This code is written VS Code so if it not work in other platform see the spacing gaps it might be the problems 
Below is the code 
   ||    ||    ||
       
       
    #include<stdio.h>

    int main()
    {

    float a,b;

    int c;
    
    printf("Welcome to Simple Calculator !\n");
    
    printf("Here we will be doing simple maths with any two numbers!\n");
    
    printf("Please enter the 1st number :\n");
    
    scanf("%f", &a);
    
    printf("Please Enter the 2nd Number:\n");
    
    scanf("%f", &b);
    
    printf("Now we will show the Function availabe to perform!\n");
    
    printf("press the number to perform the functions:\n 1. Addition\t 2. Substraction\n 3. Multiplication \t 4. Division\n 5. Average \n");
    
    scanf("%i", &c);
    
    if ("%i", c == 1){
        printf("Your sum is:%f\n", a=b);
    }
    else if ("%i", c == 2){
        printf("Your Subtracted Value is: %f\n", a-b);
    }
    else if ("%i", c == 3){
        printf("Your Multipled Value is: %f\n", a*b);
    }
    else if ("%i", c == 4){
        printf("Your Divided Value is: %f\n", a/b);
    }
    else if ("%i", c == 5){
        printf("The Average Value is: %f\n", (a=b)/2);
    }
    else{
        printf("Invalid Entry !! Please run the programe again.");
    }
    return 0;
    }
