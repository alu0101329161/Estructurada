
#--Preguntas de la 35 a la 45--                              
Pregunta 35. 
`
    "\t\n" Salida -------------- "\t\n"
    '\t\n' Salidad ------------- "\\t\\n"
`

Pregunta 36
` 
	%q es como si pusieramos comillas simples y %Q es como si pusieramos c>
        %q{hello world\n} Salida ---------------- "hello world\\n"
        %Q{hello world\n} salida ---------------- "hello world\n"
`

Pregunta 37
`
   %q{'a' 'b' 'c'} => "'a' 'b' 'c'"
   %Q{"a" "b" "c"} =>  "\"a\" \"b\" \"c\""
`


Pregunta 38.
`
  "--4--\n--2--\n"
`


Pregunta 39.
`
  "--\#{a}--\n--\#{b}--\n"
`


Pregunta 40.
`
 "he" "o" "hello"
`


Pregunta 41.
`
 "hello world"
`


Pregunta 42.
`
 "..."
`


Pregunta 43.
`
 "2 2 2 "
`


Pregunta 44.
`
 Es un array separando las palabras por espacios  ["this", "is", "a", "test"]
`

 
Pregunta 45.
`
 genera un array y lo de dentro lo pone como si fueran comillas simples ["\\t", "\\n"]
`


#--Pregunta de la 46 a 55--


Pregunta 46.
`
 lo mismo que la 45 pero con comillas dobles
`


Pregunta 47.
`
 [nil, nil, nil]
`


Pregunta 48.
`
 [0, 0, 0]
`


Pregunta 49.
`
 [[1, 2], [3, 4]]
`


Pregunta 50.
`
 [0, 2, 4]
`


Pregunta 51.
`
 ["b"], ["d", "e"], ["a", "b", "c"], ["a"], ["d", "e"]
`


Pregunta 52.
`
 ["A", "B", "c", "d", "e"], ["A", "B", "C", "D", "E"], [1, 2, 3, "A", "B", "C", "D", "E"], [3, "A>
`


Pregunta 53.
`
	2.7.2 :001 >  a = (1...4).to_a
	 => [1, 2, 3] 
	2.7.2 :002 >  a = a + [4, 5]
	 => [1, 2, 3, 4, 5] 
	2.7.2 :003 > a += [[6, 7, 8]]
	 => [1, 2, 3, 4, 5, [6, 7, 8]] 
	2.7.2 :004 > a = a + 9
	Traceback (most recent call last):
        5: from /home/usuario/.rvm/rubies/ruby-2.7.2/bin/irb:23:in `<main>'
        4: from /home/usuario/.rvm/rubies/ruby-2.7.2/bin/irb:23:in `load'
        3: from /home/usuario/.rvm/rubies/ruby-2.7.2/lib/ruby/gems/2.7.0/gems/irb-1.2.6/exe/irb:11:in `<top (required)>'
        2: from (irb):4
        1: from (irb):4:in `+'
	TypeError (no implicit conversion of Integer into Array)
	2.7.2 :005 > 

  error no se puede sumar un entero a un Array  se tiene que usar el RANGE o guardarlo n una varibale y luego to_s
`


Pregunta 54.
`
 ["a", "b", "c", "b", "a"], ["a", "a"]
`


Pregunta 55.
`
 [0, 0, 0, 0, 0, 0, 0, 0]
`


#--Pregunta de la 56 a 67--


Pregunta 56.
`
 [1], [1, 2, 3], [1, 2, 3, [4, 5, 6]], [1, 2, 3, [4, 5, 6], 7, 8]
`


Pregunta 57.
`
 [1, 2, 3, 4, 5], [5, 4, 3, 2, 1], [2, 3, 4], [4, 3, 2]
`


Pregunta 58.
`
 2.7.2 :001 > a = 1..10
 => 1..10 
 2.7.2 :002 > a.class
 => Range 
 2.7.2 :003 > a.to_a
 => [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 
 2.7.2 :004 > b = 1...10
 => 1...10 
 2.7.2 :005 > b.to_a
 => [1, 2, 3, 4, 5, 6, 7, 8, 9] 
 2.7.2 :006 >  b.include? 10
 => false 
 2.7.2 :007 > b.include? 8
 => true 
 2.7.2 :008 > b.step(2) {|x| print "#{x} " }
 1 3 5 7 9  => 1...10 
 2.7.2 :009 > 1..3.to_a
 Traceback (most recent call last):
        4: from /home/usuario/.rvm/rubies/ruby-2.7.2/bin/irb:23:in `<main>'
        3: from /home/usuario/.rvm/rubies/ruby-2.7.2/bin/irb:23:in `load'
        2: from /home/usuario/.rvm/rubies/ruby-2.7.2/lib/ruby/gems/2.7.0/gems/irb-1.2.6/exe/irb:11:in `<top (required)>'
        1: from (irb):9
 NoMethodError (undefined method `to_a' for 3:Integer)
 Did you mean?  to_c
               to_r
               to_f
               to_i
               to_s
 2.7.2 :010 > 
Salta error porque no esta guardando en una variable antes de llamar a to_a 
`


Pregunta 59.
` 
true, true, true
`


Pregunta 60.
`
  2.7.2 :001 > true.class
  => TrueClass 
  2.7.2 :002 > false.class
  => FalseClass 
  2.7.2 :003 > puts"Hello" if 0
  Hello
  => nil
  2.7.2 :006 > puts"Hello" if nil
  => nil 
  2.7.2 :007 > puts"Hello" if ""
  (irb):7: warning: string literal in condition
  Hello
  => nil  
`


Pregunta 61.
`
 Symbol, false, Symbol, true, true
`


Pregunta 62.
`
 "Ruby", "", Rub => nil, "Java", RubJava => nil
`


Pregunta 63.
`
 "3 rubies"
`


Pregunta 64.
`
 [4, 5], 5, [1, 2, 3]
`


Pregunta 65.
`
 [:a, :b], [1, 2], 3, {:a=>1, :b=>2, :c=>3}, {:a=>1, :b=>2, :c=>3}, {:b=>2, :c=>3}, {:a=>1}, {:a=>
`


Pregunta 66.
`
 Las dos funciones hacen los mismo, pero en Hash.new(0) utiliza el metodo new de la clase hash y >
`


Pregunta 67.
`
 ["hello", "world", "hello", "LPP"]
`


