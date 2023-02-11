---
layout: default
title: "Lab02a: Web Applications II Lab Sign-Off"
---

Tests for Web Applications II Lab (Lab02a) Sign-Off
===============
 1) Pull up **Lab02a** in Eclipse: Verify that the lab has been correctly renamed: **"lab02"** is replaced with **"lab02a\_xxxx"**, where "xxxx" is the student's YCP username

 2) Pull up the **Index page**, then go to **Add Numbers** from the **Index page**: The **AddNumbers** page appears, with three number fields

 3) Enter **three numbers**: Get correct result
 
 4) Delete the **third number**: Get correct error message: **"Please enter 3 numbers"**, with all fields still filled with the submitted values (this could be difficult to implement)
 
 5) Replace the **third number** with **"abc"**: Get correct error message: **"Invalid double"**, with all fields still filled with the submitted values (this could be difficult to implement)

 6) Go back to the **Index Page**

 7) Go to **Multiply Numbers** from the **Index page**: The **MultiplyNumbers** page appears, with two number fields
 
 8) Enter **two numbers**: Get correct result
 
 9) Delete the **first number**: Get correct error message: **"Please enter 2 numbers"**, with all fields still filled with the submitted values (this could be difficult to implement)

10) Replace **first number** with **"abc"**: Get correct error message: **"Invalid double"**, with all fields still filled with the submitted values  (this could be difficult to implement)

11) Go back to the **Index Page**

12) Go to **Guessing Game** from the **Index page**: The **GuessingGame** page appears, with **"Start Game"** displayed

13) Use **33** as the number trying to be guessed: Press the correct buttons for each guess, eventually guesses 33
Correct sequence of guesses: **50** -> **25** -> **37** -> **31** -> **34** -> **32** -> **33**

14) Pull up **Numbers.java**: Verify that it exists

15) Pull up **NumbersController.java**: verify that it has **add()** and **multiply()** methods, and that **AddNumbersServlet** calls the **add** method, and **MultiplyServlet** calls the **multiply** method

16) Pull up **addNumbers.JSP**: Verify that it is pulling data for the fields directly from the **Numbers.java** model, and **NOT** using just the values passed in as named parameters through the Servlet (except for the **Numbers.java** model reference)

17) Run test cases for **NumbersController.java** controller and **Numbers.java** model: Test cases exist and pass