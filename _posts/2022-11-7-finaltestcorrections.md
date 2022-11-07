---
toc: true
comments: true
layout: post
title: Trimester 1 Final Test Corrections
tags: true
categories: [markdown,Week10]
---

## Overall score
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/be442d8ab82dce33df918c279086d8aa9180e0f7/images/tri1finalscore.PNG?raw=true">

## Test Corrections

Question 1:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/78b5ee26903e51809da4ffce1d7a33a90d13adda/images/question1csp.PNG?raw=true">
What I answered: A, The code segment displays the value of  2(5×3)  by initializing result to 2 and then multiplying result by 3 a total of five times.
The correct answer: D, The code segment displays the value of  2(53)  by initializing result to 2 and then multiplying result by 5 a total of three times. The code segment initializes result to 2, then repeatedly multiplies result by 5 inside a loop. The loop iterates three times, so result is assigned the value of 2(53).

Question 5:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/3b97525ee0db2784c0a6a897082acc197d71702a/images/question5csp.PNG?raw=true">
What I answered: C, II and III only. Information about which restaurants Brandon and Cynthia have visited in the past is not needed. Restaurants are recommended based on whether they can accommodate all allergies and dietary restrictions, not based on whether group members have been there before.
The correct answer: B, III only. Brandon’s contact list is not needed. Alejandra is organizing the meal, so the group members are selected from her contact list, not Brandon’s. Information about which restaurants Brandon and Cynthia have visited in the past is not needed. Restaurants are recommended based on whether they can accommodate all allergies and dietary restrictions, not based on whether group members have been there before. Information about which food allergies and dietary restrictions can be accommodated at nearby restaurants is needed so that a restaurant can be recommended for the group.

Question 14:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/3b97525ee0db2784c0a6a897082acc197d71702a/images/question14csp.PNG?raw=true">
What I answered: 6 and 7. 6 is correct, but 7 is not because when numCorrect is 7, the condition numCorrect > 7 evaluates to false. Therefore "check" is displayed as intended.
The correct answer: 6 and 8. When numCorrect is 6, the condition numCorrect > 7 evaluates to false. Therefore "check" is displayed instead of the intended "check minus". When numCorrect is 8, the condition numCorrect > 7 evaluates to true and the condition numCorrect ≥ 9 evaluates to false. Therefore "check minus" is displayed instead of the intended "check plus".

Question 16:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/3b97525ee0db2784c0a6a897082acc197d71702a/images/question16csp.PNG?raw=true">
What I answered: A, The message is broken into packets that are transmitted in a specified order. Each packet must be received in the order it was sent for the message to be correctly reassembled by the recipient’s device. Messages are broken into packets, but they can be received in any order and still be reassembled.
The correct answer: B, The message is broken into packets. The packets can be received in any order and still be reassembled by the recipient’s device. Messages are broken into packets. Each packet contains data to be transmitted, as well as metadata for routing and reassembling the data upon receipt. This allows the packets to be received in any order and still be reassembled correctly.

Question 23:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/3b97525ee0db2784c0a6a897082acc197d71702a/images/question23csp.PNG?raw=true">
What I answered: A, The position of the runner is determined by calculating the time difference between the start and the end of the race and making an estimation based on the runner’s average speed. While a runner’s position could be estimated using the runner’s average speed, a more accurate representation of the position over time can be achieved using a sampling technique.
The correct answer: D, The position of the runner is sampled at regular intervals to approximate the real-word position, and a sequence of bits is used to represent each sample. Analog data, like the runner’s position, have values that change smoothly, rather than in discrete intervals. Analog data can be approximated digitally by measuring values of the analog signal at regular intervals called samples. The samples are represented digitally as sequences of bits.

Question 26:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/3b97525ee0db2784c0a6a897082acc197d71702a/images/question26csp.PNG?raw=true">
What I answered: C, string. A string could be used to indicate whether a store is open (for example, by letting "open" represent open and "closed" represent closed).
The correct answer: A, Boolean. The status of whether a store is open can be represented using only the values true and false, so a Boolean variable is most appropriate.

Question 28:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/3b97525ee0db2784c0a6a897082acc197d71702a/images/question28csp.PNG?raw=true">
What I answered: D, This code incorrectly charges customers who use more than 25 units of electricity. These customers are charged $7 for each of the first 25 units and $5 for each subsequent unit. For examples, if a customer used 32 units of electricity, they should be charged $5 for the first 25 and $7 for the additional 7 units (32 – 25 = 7 units), for a total charge of $174. This code segment would incorrectly charge the customer 25 * $7 + 7 * $5 = $210 for the 32 units.
The correct answer: C, If the number of units of electricity used is 25 or less, the cost is 5 times the number of units. Otherwise, the cost is 5 times the first 25 units plus 7 times the number of units above 25. For examples, if a customer used 32 units of electricity, they should be charged $5 for the first 25 and $7 for the additional 7 units (32 – 25 = 7 units), for a total charge of $174. 

Question 35:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question35csp.PNG?raw=true">
What I answered: B, The last line in this code segment sets maxPS to 50 regardless of the value of time.
The correct answer: D, This code segment uses the IF statement to set maxPS to 30 when time > 120 and uses the ELSE statement to set maxPS to 50 otherwise.

Question 36:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question36csp.PNG?raw=true">
What I answered: A, APPEND(evenList, i) i  ←  i + 2. This would be the correct solution if i were initialized to 2 instead of 1. This code segment will generate the list [1, 3, 5, 7, 9, 11, 13, 15, 17, 19].
The correct answer: C, APPEND(evenList, 2 * i) i  ←  i + 1. For the first iteration of the loop, twice the value of i, or 2, is appended to evenList, and then i is incremented to 2. For the second iteration of the loop, twice the value of i, or 4, is appended to the list, and then i is incremented to 3. This continues eight more times, appending the next eight even numbers to evenList. This code segment will generate the list [2, 4, 6, 8, 10, 12, 14, 16, 18, 20].

Quesiton 37:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question37csp.PNG?raw=true">
What I answered: B,  This code segment assigns both variables the original value of num1.
The correct answer: D, The first statement assigns the value of num1 to the temporary variable temp. The second statement assigns the value of num2 to num1. The third statement assigns the original value of num1, which is stored in temp, to num2. The original values of num1 to num2 are interchanged.

Question 38:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question38csp.PNG?raw=true">
What I answered: A, temp  ←  word1 word3  ←  word1 word1  ←  temp. This code segment assigns "xylophone" to both word1 and word3.
The correct answer: B, temp  ←  word1 word1  ←  word3 word3  ←  temp. The first statement assigns the value of word1 to the temporary variable temp. The second statement assigns the value of word3 to word1. The third statement assigns the original value of word1, which is stored in temp, to word3. The original values of word1 and word3 are interchanged, which reverses the values of the variables as intended.

Question 42:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question42csp.PNG?raw=true">
What I answered: A, 12. After initially assigning values to the variables, the code segment assigns the value 4 to num3 and assigns the value 8 to num1. 
The correct answer: C, 16. The first three statements assign values to the variables. Since num1 < num2 evaluates to false, the body of the ELSE block is executed and num3 is assigned the value 4. Since num2 ≥ num3 evaluates to true, the body of the second IF block is executed and num1 is assigned the value 8. Lastly, sum is assigned the value of 8 + 4 + 4, or 16.

Question 43:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question43csp.PNG?raw=true">
What I answered: A, 6. This is the value of x after the code segment is executed, not the value of result.
The correct answer: B, 15. The variables x and result are initialized to 0. Inside the loop, result is increased by x and x is increased by 1. The loop terminates when x exceeds 5. Therefore, result is assigned the sum of the integers from 0 to 5, or 15.

Question 46:
<img src= "https://github.com/sarahliu2006/Sarah-Liu/blob/a6a8678d214c455dc4dd872bb54ffc9f9721aa2b/images/question46csp.PNG?raw=true">
What I answered: C, The value of first is false, and the value of second is true. The fourth statement assigns the value of second (which is true) to first.
The correct answer: A, The value of first is true, and the value of second is true. The first two statements assign values to the variables. The third statement assigns the value of first (which is true) to second. The fourth statement assigns the value of second (which is true) to first.
