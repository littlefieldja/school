#Simple Markdown and other notes


####Setting up a new git connection
- git clone http://github.com/littlefieldja/"repo name"
	-	ex: git clone http://github.com/littlefieldja/school
	
####how to add files to github from ATK 
 - git add .
 - git commit -m "message here"
 - git push
 
####Other commands 
- git status
	- shows status of modified and stacked docs.
	
	
####Simple things to remember 
- text formatting 
	- this is *italic* text.
	- this is **bold** text. 
	- this is both **_bold and italic_**.
	
- this is a order list 
	1. item 1 
	2. item 2	
	3. item 3
	
- how to format a list 
  1. item 1
   1. nested item 1a
   2. nested item 1b
  2. item 2
   1. nested item 2a
   2. nested item 2b
   
```c++	
	int main (){
	double int1; 
	double int2; 
	std::cout << "Please enter a number";
	std::cin >> int1;
	std::cout << "Please enter another number";
	std::cin >> int2;
	
	std::cout >> "You entered " + int1 + " as the first number and " + int2 + " has the second number";
	}```
	
this is some rubby

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
 
 
