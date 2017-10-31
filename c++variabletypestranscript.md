### C++ Variable Types Transcript
Greetings, my fellow human beings, and welcome back to another C++ tutorial video! My name is SupremeLeaderAlbert, and what I will be covering in this video is the different variable types in C++, and really, in any other programming language. If you already have experience coding, then stop watching this and go to the next tutorial video in my playlist, because this video is for the people who have never written a single line of code before. I'm going to walk you through the very basics of programming in this video. So, first of all, what is a variable? A variable stores information that the programmer can make use of later in the program, by using the variable's identifying name. The information that a variable holds can be an integer, a real number, a single characters, a string (which is an array of characters), and a boolean which is either true or false. Let me show you what I mean. At the top of my main program here, I will write "int integerThingy". Then I'll add a semicolon at the end. The semicolon lets the program know that that is all for that line. And it is required. Now, I didn't have to name it "integerThingy". I can name it pretty much whatever I want. This is how we declare an integer variable in C++. We can now assign an integer value to it using the equals sign. So, after the variable name and before the semicolon, I'll write "= 5". This assigns the integerThingy variable a value of 5. Another thing that we can do is leave it as "int integerThingy;" and write "integerThingy = 5;" here. It does the same thing as before: it just assigns a value of 5 to the integer. But I prefer to do it all in one line of code, so we'll put that back. Now, I said that int variables can hold integer values, so you may be wondering about decimals and real numbers. Well, you can't hold a decimal value in an int variable, so here's what I'll do. I'm going to declare another variable here, called decimalThingy, but instead of using "int", I will use "float". "float" means that the variable can hold any real number value. So we'll assign it a value of 6.843. I just chose that number randomly, but really, it can be any real number with seven or less significant digits. The next variable type is a char variable. These hold a single character, which can be a letter, a number, or any ASCII value. I'll give you an example: we can declare "char letterThingy" and assign it the letter 'a'. Be sure to use the single quotation marks when using characters. I'm not going to talk about booleans in this video because I don't feel like it, so we'll finish off with string variables. Now, a string is just an array of characters. It can hold multiple letters and numbers. When using strings, you have to type "#include<string>" at the top of your program. Otherwise, it won't work, and I'll explain why in the next video.