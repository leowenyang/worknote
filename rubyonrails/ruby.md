ruby step by step
==============================
data type
-------------------------

ruby only have three data types

- Number
- Boolean
- String

variable
-------------------------

- global var    =>  $var_name
- local var     =>   var_name
- class var     =>  @@var_name
- instance var  =>  @var_name

constant
-------------------------

- constant  => the first letter is caption
- null      => nil

expression
-------------------------

- Math       =>  +; -; *; /; **; %
- relation   => ==; !=; <; <=; >; >=;
- boolean    => &&; ||; !; and; or; not
- assignment => =; +=; -=; *=; /=; ++; --

control flow
-------------------------

- if statement

	if expression 1
        ...
    else expression 2
        ...
    else
        ...
    end

    unless expression 1
        ...
    else
        ...
    end

- loop statement 

    next and break

	while expression 1
        ...
    end

    until expression 1
        ...
    end

    for num in 1...10 
        ...
    end

    loop do
        ...
    end

	object.each {|item| #do something }

    10.times { do something }

- case

function
-------------------------

def function_name
end

class
-------------------------

- define a class : class name start with a capital letter

	class class_name
		def function()
			...
		end
		
		def function2()
			...
		end
	end

- new a object

   object = class_name.new

- use object method

   object.function

- class construct function 
 
    function initialize

- interitance

	class ChildClass < ParentClass
	   ...
	end

- class function scope

1. public

	def public function_name
        ...
    end

2. private
	def private function_name
        ...
    end

comment
-------------------------

- one line comment 

   # this is a comment line

- muli-line comment

   =begin
      ...
   =end

special data structure
-------------------------
- array  => ['a', 'b', 'c']
- hash   => {"foo" => 123, "bar => 456}
