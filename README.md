# Questoes Koltin

## Questão 1 

```Kotlin

fun main() {
    
    var entrada_celsius = 30
	var F = entrada_celsius * 9 / 5 + 32
    print(F)
}

## Questão 2

fun main() {

    var entrada_f = 86
    
    var C = (entrada_f - 32) * 5 / 9
    print(C)
}

```

## Questão 3

```Kotlin


fun main() {
    val PI = 3.14
    var raio = 5
    var altura = 10
    var volume = PI * raio*raio * altura
    print(volume)
}

```

## Questão 4

```Kotlin

fun main() {
  val distancia = 360
  val consumo = 12
  val litros = distancia / consumo
  print(litros)
}

## Questão 5

fun main() {
    var valor_original = 1500
    
    var taxa_juros = 1
    
    var meses_atrasados = 5
    
    var valor = valor_original * ( 1 + (taxa_juros / 100) * meses_atrasados)
    
    print(valor)
}

```

## Questão 6

```Kotlin

fun main() {
   var A = 10
   var B = 5
   var temp: Int
    
   temp = A
   A = B
   B = temp
    
   println("A = $A")
   println("B = $B")
}

```

## Questão 7

```Kotlin

fun main() {
  var comprimento = 5
  var largura = 3
  var altura = 2
    
  var volume = comprimento * altura * largura
  print(volume)
}

```

## Questão 8

```Kotlin

fun main() {
 var num = -5
 var quadrado = num * num 
 print(quadrado)
}

```

## Questão 9

```Kotlin

fun main() {
 var num1 = 5
 var num2 = 10
 var diferenca = num1 - num2 
 print(diferenca)
}

```

## Questão 10

```Kotlin

fun main(){
    var valor_em_dolar = 10
    var cotacao_do_dolar = 5.26
    var valor_em_real = valor_em_dolar * cotacao_do_dolar
    print(valor_em_real)
}

```

## Questão 11

```Kotlin

fun main(){
    var valor_em_real = 2000
    var cotacao_do_dolar = 5.26
    var valor_em_dolar = valor_em_real / cotacao_do_dolar
    print(valor_em_dolar)
}

```

## Questão 12

```Kotlin

fun main(){
    var num1 = 5
    var num2 = 10
    var num3 = 20
    
    var soma = (num1 * num1) + (num2 * num2) + (num3 * num3)
    print(soma)
}

```

## Questão 13

```Kotlin

fun main(){
   var num1 = 5
   var num2 = 10
   var num3 = 20
   var soma = num1 + num2 + num3
   var quadrado = soma * soma
   print(quadrado)
}

```

## Questão 14

```Kotlin

fun main(){
   var num1 = 5
   var num2 = 10
   var num3 = 20
   var num4 = 30
   var produto = num1 * num3
   var soma = num2 + num4
   print("Produto:" + produto + ", Soma:" + soma)
}

```

## Questão 15

```Kotlin

fun main() {
 var salario = 1500
 var aumento_porcentagem = 10
 var aumento = salario * (aumento_porcentagem / 100.0)
 var novo_salario = salario + aumento
 print(novo_salario)
}

```

## Questão 16

```Kotlin

fun main() {
	var raio = 5
    var area = 3.14159 * raio * raio
    print(area)
}

```

## Questão 17

```Kotlin

fun main() {
    var num1 = 10
    var num2 = 5
    var adicao = num1 + num2
    var subtracao = num1 - num2
    var multiplicacao = num1 * num2
    var divisao = num1 / num2
    
    print("Adição" + adicao + ", Subtração:" + subtracao + ", Multiplicação:" + multiplicacao + ", Divisão: " + divisao)
}

```

## Questão 18

```Kotlin

fun main() {
   var distancia_km = 10
   var tempo_horas = 2
   var velocidade_ms = distancia_km / tempo_horas / 3.6
   print(velocidade_ms)
}

```

## Questão 19

```Kotlin

import kotlin.math.pow

fun main() {
	var base = 2.0
    var expoente = 4.0
    var potencia = base.pow(expoente)
    print(potencia)
}

```

## Questão 20

```Kotlin

import kotlin.math.pow

fun main() {
  var raio = 5.0
  var pi = 3.14
    
  var formula = (4.0/3.0) * pi * raio.pow(3)
  print(formula)
}

```

## Questão 21

```Kotlin

import kotlin.math.pow

fun main() {
    val pes = 10
    val metros = pes * 0.3048
    print(metros)
} 

```

## Questão 22

```Kotlin

import kotlin.math.pow

fun main() {
    val base = 16.0
    val indice = 2.0
    var raiz = base.pow((1.0/indice))
    print(raiz)
}

```

## Questão 23

```Kotlin

import kotlin.math.pow

fun main() {
   val numero = 5
   var antecessor = numero - 1
   var sucessor = numero + 1
   print("o numero é " + numero + ", Seu sucessor é: " + sucessor + ", Seu antecessor é: " + antecessor)
}

```

## Questões 24

```Kotlin

import kotlin.math.pow

fun main() {
 val num1 = 15
 val num2 = 3
 var resultado_divisao = num1 / num2
 var resultado_quadrado = resultado_divisao * resultado_divisao
 print(resultado_quadrado)
}

```

## Questão 25

```Kotlin

import kotlin.math.pow

fun main() {
	 val num1 = 5
     val num2 = 10
    
    if(num1 > num2) {
        print(num1 - num2)
    
    }else{
        print(num2 - num1)
    }
}

```

## Questão 26

```Kotlin

import kotlin.math.pow

fun main() {
	 val num1 = 5
    
    
    if(num1 > 0) {
        print("esse numero é positivo")
    
    }else if (num1 < 0){
        print("esse numero e negativo")
    }else {
		print("esse numero é neutro = (0)")
    }
}

```

## Questão 27

```Kotlin

import kotlin.math.pow

fun main() {
	val nota1 = 10
    val nota2 = 5
    val nota3 = 7 
    val nota4 = 6
    var media = (nota1 + nota2 + nota3 + nota4) / 4
    if(media >= 5){
        print("Você passou!!!, sua media é: " + media)
    }else{
        print("Você nao passou, sua media é: " + media)
    }
}

```

## Questão 28

```Kotlin

import kotlin.math.pow

fun main() {
	val nota1 = 3
    val nota2 = 5
    val nota3 = 7 
    val nota4 = 6
    var media = (nota1 + nota2 + nota3 + nota4) / 4
    if(media > 7){
        print("Você passou!!!, sua media é: " + media)
    }else if (media >= 5){
        print( "sua media é: " + media + " - Exame")
    }else{
        print("Sua media é: " + media + "  - reprovado")
    }
}

```

## Questão 29

```Kotlin

import kotlin.math.pow

fun main() {
	val valor = 1
    if (valor <= 3) {
        print(valor)
    }else{
        print("nao segue os parametros")
    }
    
    
}

```

## Questão 30

```Kotlin

fun main() {
    val num1 = 10
    val num2 = 20
    val num3 = 3

    var menor_valor = num1
    var maior_valor = num1

    if (num2 > maior_valor) {
        maior_valor = num2
    }
    if (num2 < menor_valor) {
        menor_valor = num2
    }

    if (num3 > maior_valor) {
        maior_valor = num3
    }
    if (num3 < menor_valor) {
        menor_valor = num3
    }

    print("Maior valor é:" + maior_valor +", e menor valor é:" + menor_valor)
}

```

