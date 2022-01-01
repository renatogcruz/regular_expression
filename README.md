# regular expression

* [regexpal](https://www.regexpal.com/)

## Capítulo 1

**Regular Expression**

* expressão para todos os números de 0 a 9 
* `[0-9]`

* expressão para todos os números do telefone 
* `[012789]`

* expressão para todos os números de 0 a 9 mais hifens literal 
* `[0-9][0-9][0-9]-[0-9][0-9][0-9]-[0-9][0-9][0-9][0-9]`

* expressão para todos os números de 0 a 9 (`\d`) mais hifens literal utilizando shorthand de caracteres 
* `\d\d\d-\d\d\d-\d\d\d\d`

* expressão para todos os números de 0 a 9 (`\d`) mais qualquer caractere que não seja um dígito (`\D`) utilizando shorthand de caracteres 
* `\d\d\d\D\d\d\d\D\d\d\d\d`

* expressão para todos os números de 0 a 9 (`\d`) mais qualquer caractere (`.`) utilizando shorthand de caracteres 
* `\d\d\d.\d\d\d.\d\d\d\d`

**Test String**

`707-827-7019`

pág. 22
