# py-myopl-code

All code for my "Make your own programming language in Python" tutorial series on YouTube: https://www.youtube.com/playlist?list=PLZQftyCk7_SdoVexSmwy_tBgs7P0b97yD

This code is an interpreter for a BASIC-like language written in Python 3.

#Our syntax rules:

Basic: 

All strings are between charcter ``. 
All lines end with ;
Comments start with # or //
cooment area between <#   comments    #> 

1. Vars
	1.1 All vars start with small letters.
	1.2 Vars can be string or int or array.
	1.3 vars can use counting actions. +-/*()^
	1.4 Vars samples:
		text = 123;
		text = 2+2;
		text = 2+(2*2);
		text = `abc`;
	1.5 Sub var. samples
		text.1 = `abc`;
		text.aaaa = `bbb`;
	1.6 var use with vars and functions:
		text = 2 + numa; #befor declared numa=2;
		text = text,numa,other_var,`some text`;
	1.7 var commands. we using some commands of vars. need to pass this command into the function we will write.
		sample:
		var.Add(123);
		var.Mix();
	
2. Commands.
	2.1 All commands start with big letter. alwasy pass to command the value inside ().
		Sample of simple command:
		Print(text);
	2.2 Command with sub commands.
		Sample:
		Print.Json(text);
	2.3 Commands with many parameters
		Sample:
		Add(text)to(var2);
		
		#can have many commands per line.

3. Functions declaration;
	3.1 Function always start with big letter. with (vars) and = [];
		sample:
		Multiply(numa.numb)=[ result = numa * numb; return result;];
	3.1 use break inside.
4. call to function. same like Command.
	call to function class like call to sub command.
5. loop sample:
	Loop(var)as(key)and(value)until(a=7)limit(6)[content of loop];

