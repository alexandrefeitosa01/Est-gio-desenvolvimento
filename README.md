# Est-gio-desenvolvimento
1° 
fun main() {
    var INDICE = 13
    var SOMA = 0
    var K = 0

    while (K < INDICE) {
        K = K + 1
        SOMA = SOMA + K
    }

    println(SOMA) = 91 

    2°
    fun main() {
    val numero = readLine()!!.toInt()

    if (verificarFibonacci(numero)) {
        println("O número $numero pertence à sequência de Fibonacci.")
    } else {
        println("O número $numero não pertence à sequência de Fibonacci.")
    }
}

fun verificarFibonacci(n: Int): Boolean {
    var a = 0
    var b = 1
    while (b < n) {
        val temp = b
        b += a
        a = temp
    }
    return b == n
}

3°
a) 1, 3, 5, 7, 9

b) 2, 4, 8, 16, 32, 64, 128

c) 0, 1, 4, 9, 16, 25, 36, 49

d) 4, 16, 36, 64, 100

e) 1, 1, 2, 3, 5, 8, 13

f) 2, 10, 12, 16, 17, 18, 19, 23

4°
Ligue o primeiro interruptor por alguns minutos e depois desligue-o.
Ligue o segundo interruptor.
Vá para a sala das lâmpadas.
A lâmpada que estiver acesa é controlada pelo segundo interruptor.
A lâmpada que estiver apagada e ainda estiver fria é controlada pelo primeiro interruptor.
A lâmpada restante que estiver apagada e quente é controlada pelo terceiro interruptor.
Este método requer apenas duas idas a uma das salas das lâmpadas e lhe permite identificar qual interruptor controla cada lâmpada.

5°
fun main() {
    val inputString = "Olá, mundo!"
    val invertedString = inverterString(inputString)
    println("String original: $inputString")
    println("String invertida: $invertedString")
}

fun inverterString(input: String): String {
    var inverted = ""
    for (i in input.length - 1 downTo 0) {
        inverted += input[i]
    }
    return inverted
}
