
--Preguntas de la 35 a la 45--                              
Pregunta 35. "\t\n" => "\t\n"
    '\t\n' => "\\t\\n"
Pregunta 36 y 37. %q es como si pusieramos comillas simples y %Q es como si pusieramos c>
           %q{hello world\n} => "hello world\\n"
           %Q{hello world\n} => "hello world\n"
           %q{'a' 'b' 'c'} => "'a' 'b' 'c'"
           %Q{"a" "b" "c"} =>  "\"a\" \"b\" \"c\""
Pregunta 38.  "--4--\n--2--\n"
Pregunta 39.  "--\#{a}--\n--\#{b}--\n"
Pregunta 40. "he" "o" "hello"
Pregunta 41. "hello world"
Pregunta 42. "..."
Pregunta 43. "2 2 2 "
Pregunta 44. Es un array separando las palabras por espacios  ["this", "is", "a", "test"] 
Pregunta 45. genera un array y lo de dentro lo pone como si fueran comillas simples ["\\t", "\\n"]
