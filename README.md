

# Python

Python was invented by Guido Van Rossum.



## Introduction
  Python is a High-level,general - purpose programming language.
  Its design philosophy emphasizes code readibility with the use of significant indentation.
## Basic Python

## DATATYPES
 
In Python we use mainly three datatypes:

• Integer(int) datatype stores whole numbers.
  Ex: 1,2,3

• Float-float datatype stores decimal values.
  Ex: 22.22,4.32

• String- (str) Anything Written in b/w quotes('',"",)known as 
     string.
  Ex: "aswini" 

## Variables

•  Variables saved on temporary memory (RAM) not in permanent 
   memory.
  
•  int and float datatypes occupies 4 bytes of memory.

•  string datatype occupies 1 bytes for each character and space 
   in  between the string is also a character for example 'python' 
   is a string which has 6 characters and each character holds
   the  1 byte memory.

•  we can find the address of an variable by using the id
   (variable) function. 

•  we can find a type of a variable by using the type(a) function.
## Rules to create a variable

• Variable should not start with a number if you want to use 
  number as a variable use underscore(_) in starting.

• Variable should be a single word or a character if you want to 
  use multiple words use(_) in between them.

• Python variables are completely casesensitive.

• Don't use the below punctuations as a variable like !,@,#,$,%,<,>
   ,&,*,(,).

  

 
## print statements in python

•   we have 4 types for print in python.

• TYPE 1 :
         
         °  Using comma(,)we can add one datatype inside the print
            with another datatype and the comma (,) will provide 
            the one tab space.

• TYPE 2 :

         °  Using + operator 
         °  In this type it adds only two string variables and
            doesnot add anythong like string to int.
         °  In case of any variable in int or float datatype,we 
             have to convert it into string datatype to add with 
             another variable.
         °  It is most leastly used in the realtime.

• TYPE 3 :

        °  In this type we use the identifiers to print the 
           varibale.
        °  for int datatype we use %d.
        °  for float datatype we use %f.
        °  for string datatype we use the %s.

• TYPE 4 :
        
        °  Using f function and {}
        °  It is mostly used in the realtime.
        °  example: print(f'my name is {variable}')
          
          
## OPERATORS

• Addition (+) :
    
          °  This operator used for adding the two variables.
          °  we cannot add any datatype with the string until 
             it converted into the string.
          
• Subtraction or difference (-) :

           °  This operator is used to find the difference b/w
              the two variables.
          
• Multiplication (*) :

           °  This operator gives the product as a output for a 
               given outputs.

• Division (/) :

           °  Division operator make operation unil we get the 
              remainder as 0 and give quotient as a output.

• Floor Division (//) : 

           °  Floor division make operation and gives the int 
              value only that man eliminate the float values from
              the point.

• Modulo operator (%) :

           °  Modulo function gives the final remainder as a
              input.

• Square :

           °  Finds the square value of a given number and the 
              number should be in a int or float datatype.

• Cube :
 
           °  finds the cube value of a given number and the 
              number should be in aint or float datatype.

• power (pow) :

           °  finds the power value of a given number and the 
              number should be in a int or float datatype.
           °  syntax : pow(a,b) here a is the base value 
                       and  b  is the power value     
           °  syntax : pow(a,b,c) here a is the base value and b 
                       is the power value and the result is     
                       divided by c and gives the remainder as
                       a output.

• Equal operator (=) :

           °   assain left side variable of = to the right side 
               variable.

• is equal to (==) :

           °   checks the LHS and RHS equal or not and give the 
               boolean as a output.

• greaterthan (>>) :

           °   checks the LHS is greaterthan RHS or not.

• greaterthan or equal to (>=) :

           °   checks the LHS is greaterthan or equal to RHS
                or not.

• lessthan (<) :

           °  checks the LHS is lessthan RHS or not.

• lessthan or equal to (<=) :

           °  checks the LHS is lessthan or equal to RHS or not.

• and operator :

           °   if both the conditions are then it will give 
               true as a output.

• or operator :
    
           °   if anyone of the condition is true then it
               will print the true as a output



## String

• In python,strings can be created by enclosing the character or 
  the sequence of characters in the quotes.

• Python allows us to use single quotes,double quotes,or triple
   quotes to create strings.
EX : a = "datascience"
 
 
## Concepts in strings

 • Indexing :

          ° The indexing of python strings starts from 0.
          EX: a = "hello"
          str[0] = h
          str[2] = l
          str[4] = 0

 • Slicing :
          
          ° slicing in strings specify the start index and the end
            index,seperated by a colon,to return a part of the 
            string.
            Ex: a = "datascience"
                print(a[2:5])

 • Skipping :

          ° skipping in strings specify the start index and the 
            end index,and the skip value ,to return part of the 
            string.
          Ex: a = "datascience"
              print(a[::2])

 • Is string mutable or immutable:

          ° trying to add in the memory:
               a = "kiran"
               a[5] = j
               print(a)
         # It gives Error
          ° trying to delete the value in the memory:
               a = "kiran"
               del a[2]
               print(a)
         # It gives Error 
         # from this,string is immutable.
          
         
          
## String Builtin Functions:
   
  •  len() : To know the no of values in string.
     
      Ex: a = 'anu'
          print(len(a))

  • capitalize() : It will capitalize the starting letter.
     
      Ex: a = 'python is very powerfull language'
          print(a.capitalize())

  • title() : It will capitalize each word starting letter into 
              capital.
   
    Ex: a = 'python is easy language'
        print(a.title())

  • lower() : It will returns all characters of given    
                 string in lowercase.
   
    Ex: a = 'America'
        print(a.lower())

  • upper() : It will returns all characters of given string 
              in uppercase.

    Ex: a = 'America'
        print(a.upper())

  • islower() : islower() method returns True if all characters 
                in the string  are in lowercase.It returns False 
                if not in lowercase.

    Ex: a = 'America'
        print(a.islower())

  • isupper() : isupper() method returns True if all characters 
                in the string are in upperacse.It returns False
                 if not in uppercase.

    Ex: a = 'America'
        print(a.isupper())

  • isalpha() : isalpha() method returns True if all are alphabets
                in the string else it returns False.

    Ex: a = 'america123'
        print(a.isalpha())

  • isnumeric() : In python,isnumeric() method checks whether all 
                  the characters of the string are numeric
                   characters or not.It returns True if all the 
                   characters are numeric,otherwise returns False.
                 
    Ex: a = 'python1322'
    print(a.isnumeric())

  • isalnum() : isalnum() method checks whether the all 
                   characters of the string is alphanumeric or 
                   not.

    Ex: a = 'python1233'
        print(a.isalnum())

  • starts with() : whether the string starting with our input or 
                    not.

    Ex: a = 'deep learning'
        print(a.startswith('d'))

  • ends with() : whether the string ending with our input or not.

    Ex: a = 'deep learning'
        print(a.endswith('g'))

  • replace() : replace() method replaces the old sequences of 
                characters with the new sequence.

    Ex: a = 'kiran'
        print(a.replace('r','j'))

  • count() : count() method is used to count the number of times 
              the given character repeating.

    Ex: a = 'data science'
        print(a.count('i'))

  • split() : split() method splits the string into a comma 
              seperated list.
              

  Ex : a = 'I love my country'
       b = a.split()
       print(b)

  • join() : join() method used to join the strings.


  Ex: a = ['usa','uk','paris','canada']
      b = ''.join(a)
      print(b)


  
  



  


              


