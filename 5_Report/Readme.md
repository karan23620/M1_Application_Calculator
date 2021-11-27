#                           !!! <<< Final Report on Calculator Project >>> !!!


# 1. Requirements
  This Calculator required few keys to perform action according to user choice which are given below-
   - digits - 0-9.
   - some operators for performing operation like "+, -, *, /, ^, !".
   - Press 'Q' or 'q' to quit the program.
   - Press 'H' or 'h' for asking to clear screen then press 'C' or 'c' .

## Introduction

  This is very simple calculator. I’m going to create this simple calculator using C programming. So this calculator performs few operation such as addition, subtraction, multiplication, division, modulus, power and factorial. So I create this calculator program in two ways 
  - Using switch case
  - Using Function

## Features
  - Addition
  - Subtraction
  - Multiplication
  - Division
  - Modulus
  - Power
  - Factorial
  
  on the basis of above option user can choose their requirements and get awesome result in few seconds.
  
 ## State of art/Research
 An electronic calculator is typically a portable electronic device used to perform calculations, ranging from basic arithmetic to complex mathematics.
 
The first solid-state electronic calculator was created in the early 1960s. Pocket-sized devices became available in the 1970s, especially after the Intel 4004, the first microprocessor, was developed by Intel for the Japanese calculator company Busicom. 

![Casio_calculator](https://user-images.githubusercontent.com/49648354/143389132-f23ed0f7-4e5f-4c13-900a-e5b4eeb66791.jpg)

Modern electronic calculators vary from cheap, give-away, credit-card-sized models to sturdy desktop models with built-in printers. They became popular in the mid-1970s as the incorporation of integrated circuits reduced their size and cost. By the end of that decade, prices had dropped to the point where a basic calculator was affordable to most and they became common in schools

![Casio-fx](https://user-images.githubusercontent.com/49648354/143390047-ba51da98-b27a-47ff-9a86-e811708daffa.jpg)

But my calculator is very simple and perform very few tasks and its also not look like electronic or modern electronic calculators. So below you can see some steps to perfom any mathematical tasks-

Step 1: Print the Choice (Addition, Subtraction, multiplication, division, etc.

Step 2: Enter the Choice.

Step 3: Takes two numbers, n1 and n2

Step 4: Switch case jump to an operator selected by the user

Step 5: Store result into res variable.

Step 6: Display the operation result

Step 7: Exit from the program.

![calculator1](https://user-images.githubusercontent.com/49648354/143386912-a13acaed-743f-4250-9f9d-650ae0688474.png)

## 4W's 1-H
### Why
  - It reduce the complexity of solving mathematical problem.
  - I’m making this calculator for human to reduce their mistake in mathematical calculation.
  - It can be used by anyone.
### Where
  - IT can be used in our daily life mathematical problems any where.
  - It is mostly used by humans in study, in shop, in exam etc.
### Who
  - It can be used by anyone.
  - Basically it is frequently used by student, teacher, shopkeeper etc.
### When
  - It can be used any time and any where.
  - It can used for most mathematical calculations.
### How
  - It can used by few steps. 
  - First choose the operation you want to do. 
  - Then type numbers and then hit enter. 
  - you will get the desirable output.Thats it, so simple.

## SWOT Analysis
### Strengths
  - It is user friendly.
  - Easy to use.
  - Save time while doing mathematical problem.
  - Calculate complex arithmetic operational problems in few second.
### Weakness
  - Unable to perfom matrix operation. 
  - Unable to perform boolean operation.
  - Unable to perform binary operation.
  - Unable to perform trigonometric functions operation.
### Opportunities
  - It is the best programing practice to learn new things.
### Threats
  - There are show many advance calculator are already present in the market.

## High Level Requriments
 | ID 	 |           Description                                      |	   Status    |
 |-------|------------------------------------------------------------|--------------|
 | HLR_1 |	User can press 'Q' or 'q' to quit the program	            |  Implemented |
 | HLR_2 |	User can press 'H' or 'h' for display screen clear option	|  Implemented |
 | HLR_3 |	User can press 'C' or 'c' to clear the screen             |  Implemented |
 | HLR_4 |	User can choose operator sign 	                          |  Implemented |
 | HLR_5 |	User can give intput	                                    |  Implemented |
 | HLR_6 |	User will get output	                                    |  Implemented |
 | HLR_7 |	User will end up the program	                            |  Implemented |

## Low Level Requriments
 | ID 	 |           Description                                      |   I/P  |  O/P  |	   Status   |
 |-------|------------------------------------------------------------|--------|-------|--------------|
 | LLR_1 |	Select appropriate option among operators sign            |   +    |       |  successful  |
 | LLR_2 |	Give inputs like n1, n2                                   | 20+30  |  50   |  successful  |     
 | LLR_3 |	Your output                                               |        |  50   |  successful  |
 | LLR_4 |	Claer the Screen if need type c 	                        |  c     |       |  Implemented |
 | LLR_5 |	Exit the program	                                        |        |       |  Implemented |
 
 # 2. Design
   - Structural Diagram
   - Behavioral Diagram

## Structural Diagram

 >                                              !!! This is the Structural Diagram of Simple Calculator !!!

![Structural Diagram](https://user-images.githubusercontent.com/49648354/143519250-9680fcb9-3293-46cf-be1f-766cb47a37b8.png)

## Behavioral Diagram

>                                             !!! This is Behavioral Diagram of Simple Calculator !!!
                                             
![Behavioral Diagram](https://user-images.githubusercontent.com/49648354/143519704-017cc9ce-aeb5-4b09-bd2a-70e7bbf464aa.png)

# Test Plan
  In this module we are going to discuss about two tests plan which are given below-
 - Basic Operational Test Case
 - Functionality Test Case
## Basic Operational Test Cases
   |   ID   |                         Description 	                                | Status |
   |--------|-----------------------------------------------------------------------|--------|
   | BOTC_1 | Check the calculator is working properly or not.                      |  Yes   |
   | BOTC_2 | Check all the operators sign menu showing or not                      |  Yes   |
   | BOTC_3 | Check if the arithmetic operator (+, -, *, /, %, !) are working or not|  Yes   |
   | BOTC_4 | Check if the sin, cos, tan and coT is operational working or not      |  No    |
   | BOTC_5 | Check if the log operation is working or not                          |  No    |
   | BOTC_6 | Check if the factorial key is working or not                          |  Yes   |
   | BOTC_7 | Check if the complex conjugate keys is working or not.                |  No    |
   | BOTC_8 | Check if the square key is working or not.                            |  Yes   |
   | BOTC_9 | Check if all the numbers (0 to 9) are working or not                  |  Yes   |
   | BOTC_10| Check if the backets keys are working or not                          |  Yes   |
   | BOTC_11| Check if sum and equal key is working or not                          |  Yes   |
   | BOTC_12| Check if clear key is working or not                                  |  Yes   |
   | BOTC_13| Check if exit option is working or not                                |  Yes   |

## Functionality Test Cases  
   |   ID   |                                 Description 	                                   | Status |
   |--------|----------------------------------------------------------------------------------|--------|
   | FTC_1  | Check the addition of two integer numbers working or not                         |  Yes   |
   | FTC_2  | Check the addition of two negative numbers working or not                        |  Yes   |
   | FTC_3  | Check the addition of one positive and one negative number working or not        |  Yes   |
   | FTC_4  | Check the subtraction of two integer numbers working or not                      |  Yes   |
   | FTC_5  | Check the subtraction of two negative numbers working or not                     |  Yes   |
   | FTC_6  | Check the subtraction of one negative and one positive number working or not     |  Yes   |
   | FTC_7  | Check the multiplication of two integer numbers working or not                   |  Yes   |
   | FTC_8  | Check the multiplication of two negative numbers working or not                  |  Yes   |
   | FTC_9  | Check the multiplication of one negative and one positive number working or not  |  Yes   |
   | FTC_10 | Check the division of two integer numbers working or not                         |  Yes   |
   | FTC_11 | Check the division of two negative numbers working or not                        |  Yes   |
   | FTC_12 | Check the division of one positive number and one integer number working or not  |  Yes   |
   | FTC_13 | Check the division of a number by zero working or not                            |  Yes   |
   | FTC_14 | Check the division of a number by negative number working or not                 |  Yes   |
   | FTC_15 | Check the division of zero by any number working or not                          |  Yes   |
   
   # Output
   - Below screen is the first interface of the calculator. User can choose the preference according their choice.
   
     ![Output1](https://user-images.githubusercontent.com/49648354/143667772-c9fbb391-8454-4a97-a477-3806ac60d5c9.png)
     
   - Below screen is the output according to user preference.
   
     ![Output2](https://user-images.githubusercontent.com/49648354/143667920-ec79bcf4-039e-4628-acf5-2bf47597d928.png)
     
   - Below screen is the next  output according to user preference.
    
     ![Output3](https://user-images.githubusercontent.com/49648354/143668003-7abf7e5a-8e37-44d0-b352-9e5bc5f339e6.png)




  

