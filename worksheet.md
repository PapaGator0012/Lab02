
# Computer Science I 
## Lab 2.0 Worksheet

Name(s) and Login(s):



1. Dennis Ritchie, the creator of the C programming language,
was born on September 9th, 1941.  If he were still alive,
how old would he be today?  Find out by running the `birthday`
program on the appropriate inputs and enter your solution here.

Today is 2023/10/22
Your birthday was 1941/09/09
Hello, DennisRitchie.  You are 0 years, 0 weeks, and 0 days old today



2. Bjarne Stroustrup, the creator of the C++ programming
language, the object-oriented extension of C, was born on
December 30th, 1950.  How old is he today?

Today is 2023/10/22
Your birthday was 1950/12/30
Hello, BjarneStroustrup.  You are 0 years, 0 weeks, and 0 days old today


3. Software testing often involves testing code with known
"bad" input in an attempt to break it (sometimes this is
referred to as *fuzzing*).  Try breaking the `birthday_cli`
program by giving it "bad" input and observe the consequences.
Give at least two examples of potentially bad input and the
results you observe.




4. Complete all the size and range entries below.

* `char`
  size: 1 byte
  range: -128 to 127
* `short int`
  size: 2 byte 
  range: -32,768 tp 32,767
* `int`
  size: 4 bytes 
  range: -2,147,483,648 to 2,147,483,647
* `long int`
  size: 4 byte 
  range: -2,147,483,648 to 2,147,483,647
* `float`
  size: 4 bytes 
  range: 7 digits of accuracy
* `double`
  size: 8 bytes 
  range: 15 digits of accuracy


5. Use your working currency conversion to determine
the exchange amounts for the following inputs:

  a) $250.25 
   177.927750 GBP
  28749.971250 JPY     // output copied from compiler

  b) $1,000.52
  711.369720 GBP
  114944.740200 JPY   

  c) $968,410.12



6. Suppose that you had used only `int` types
in your conversion program.  Would you be able
to use it to convert the US national debt
(which as of 2020 was \$26,009,754,625,487)?
Why or why not?




7. Mixed types

a) Run the `area` program with 3 and 4 as inputs.  
What value do you get?  Is this result correct?

   The area is 0.000000 square units.
    it is incorrect

b) Execute the program again with inputs 3 and 5.
Does the program give correct results?  Why not?

  The area is 0.000000 square units.

c) Fix the program by editing the `area.c` source
code so that the program produces correct results.
  
  area=1/2*(base*height)
  printf("%lf,area)