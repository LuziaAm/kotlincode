/**
 * You can edit, run, and share this code. 
 * play.kotlinlang.org 
 */
fun sum(a1:Int,a2:Int) = a1.plus(a2)
fun sub(a1:Int,a2:Int) = a1.minus(a2)
fun mult(a1:Int,a2:Int) = a1.times(a2)
fun divi(a1:Int,a2:Int) = a1.div(a2)
//fun resto(a1:Float,a2:Float) = a1.mod(a2)


fun main(){
    
    var num1 = 30
    var num2 = 15
    
    var resultadoSoma:Int = sum(num1, num2)
    var resultadoSub:Int = sub(num1, num2)
    var resultadoMult:Int = mult(num1, num2)
    var resultadoDivi:Int = divi(num1, num2)
    
    print("Soma = $resultadoSoma\n")
    print("Subtração = $resultadoSub\n")
    print("Multiplicação = $resultadoMult\n")
    print("Divisão = $resultadoDivi\n")

}