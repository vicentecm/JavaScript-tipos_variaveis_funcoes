iniciando novo curso em 28/07/2022<br>
NOME DOS ARQUIVOS POR ORDEM DO CURSO:<br>


type number<br>
type string<br>
type boolean<br>
script ( var, let, const )<br>
truthy falsy<br>
conversoes de tipos<br>

resumo modulo 1 <br>
var tem um escopo global, então funciona em qualquer parte do código, o que pode gerar possíveis problemas em relação à lógica da aplicação.<br>
let e const têm escopo local, sendo assim, não podem ser acessadas em outros escopos, e const não pode ter seu valor alterado depois de definido.<br>
O JavaScript considera alguns valores como false durante comparações, como com null, undefined, 0, NaN e Strings vazias.<br>
null é usado quando não queremos dar um valor para uma variável, mas também não queremos deixá-lo como undefined (não definido).<br>
null é um objeto no JavaScript, diferente de undefined, que tem seu próprio tipo, e isso pode causar problemas se não tomarmos cuidado ao utilizá-lo.<br>
O JavaScript converte automaticamente entre tipos de valores, como números para texto e para booleanos, porém não é interessante deixá-lo fazer isso automaticamente, pois podem ocorrer erros.<br>
Temos como forçar uma mudança de tipo utilizando os métodos Number() e String(), onde Number() converte as variáveis para números ou NaN caso tenha algum erro na conversão, e String() converte as variáveis para texto.<br>