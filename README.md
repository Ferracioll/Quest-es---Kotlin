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

