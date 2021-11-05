
--Preguntas de la 35 a la 45--                              
Pregunta 35. 
`
"\t\n" => "\t\n"
    '\t\n' => "\\t\\n"
`

Pregunta 36 y 37.
` 
	%q es como si pusieramos comillas simples y %Q es como si pusieramos c>
           %q{hello world\n} => "hello world\\n"
           %Q{hello world\n} => "hello world\n"
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


--Pregunta de la 46 a 55--


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
 [1, 2, 3], [1, 2, 3, 4, 5], [1, 2, 3, 4, 5, [6, 7, 8]], error se tiene que usar el RANGE o guardarlo n una varibale y luego to_s
`


Pregunta 54.
`
 ["a", "b", "c", "b", "a"], ["a", "a"]
`


Pregunta 55.
`
 [0, 0, 0, 0, 0, 0, 0, 0]
`


--Pregunta de la 56 a 67--


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
 [1, 2, 3, 4, 5, 6, 7, 8, 9, 10], [1, 2, 3, 4, 5, 6, 7, 8, 9], false, true,1 3 5 7 9  => 1...10 ,>
`


Pregunta 59.
` 
true, true, true
`


Pregunta 60.
`
 TrueClass, FalseClass, hello, nil, (irb):73: warning: string literal in condition hello
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


