# Questoes Koltin

## Questão 1 

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

## Questão 3

fun main() {
    val PI = 3.14
    var raio = 5
    var altura = 10
    var volume = PI * raio*raio * altura
    print(volume)
}

## Questão 4

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

## Questão 6

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

## Questão 7

fun main() {
  var comprimento = 5
  var largura = 3
  var altura = 2
    
  var volume = comprimento * altura * largura
  print(volume)
}

## Questão 8

fun main() {
 var num = -5
 var quadrado = num * num 
 print(quadrado)
}

## Questão 9

fun main() {
 var num1 = 5
 var num2 = 10
 var diferenca = num1 - num2 
 print(diferenca)
}

## Questão 10

fun main(){
    var valor_em_dolar = 10
    var cotacao_do_dolar = 5.26
    var valor_em_real = valor_em_dolar * cotacao_do_dolar
    print(valor_em_real)
}

## Questão 11

fun main(){
    var valor_em_real = 2000
    var cotacao_do_dolar = 5.26
    var valor_em_dolar = valor_em_real / cotacao_do_dolar
    print(valor_em_dolar)
}

## Questão 12

fun main(){
    var num1 = 5
    var num2 = 10
    var num3 = 20
    
    var soma = (num1 * num1) + (num2 * num2) + (num3 * num3)
    print(soma)
}

## Questão 13

fun main(){
   var num1 = 5
   var num2 = 10
   var num3 = 20
   var soma = num1 + num2 + num3
   var quadrado = soma * soma
   print(quadrado)
}

## Questão 14

fun main(){
   var num1 = 5
   var num2 = 10
   var num3 = 20
   var num4 = 30
   var produto = num1 * num3
   var soma = num2 + num4
   print("Produto:" + produto + ", Soma:" + soma)
}

## Questão 15

fun main() {
 var salario = 1500
 var aumento_porcentagem = 10
 var aumento = salario * (aumento_porcentagem / 100.0)
 var novo_salario = salario + aumento
 print(novo_salario)
}

## Questão 16

fun main() {
	var raio = 5
    var area = 3.14159 * raio * raio
    print(area)
}

## Questão 17

fun main() {
    var num1 = 10
    var num2 = 5
    var adicao = num1 + num2
    var subtracao = num1 - num2
    var multiplicacao = num1 * num2
    var divisao = num1 / num2
    
    print("Adição" + adicao + ", Subtração:" + subtracao + ", Multiplicação:" + multiplicacao + ", Divisão: " + divisao)
}

## Questão 18

fun main() {
   var distancia_km = 10
   var tempo_horas = 2
   var velocidade_ms = distancia_km / tempo_horas / 3.6
   print(velocidade_ms)
}

## Questão 19

fun main() {
   var distancia_km = 10
   var tempo_horas = 2
   var velocidade_ms = distancia_km / tempo_horas / 3.6
   print(velocidade_ms)
}

## Questão 20

import kotlin.math.pow

fun main() {
	var base = 2.0
    var expoente = 4.0
    var potencia = base.pow(expoente)
    print(potencia)
}

## Questão 21

import kotlin.math.pow

fun main() {
  var raio = 5.0
  var pi = 3.14
    
  var formula = (4.0/3.0) * pi * raio.pow(3)
  print(formula)
}

## Questão 22

