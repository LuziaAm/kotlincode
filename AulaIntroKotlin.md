/**
 * You can edit, run, and share this code. 
 * play.kotlinlang.org 
 */
const val MIN_AGE = 16
const val MAX_AGE = 68
const val MORE = 1
const val EQUAL = 0
const val LESS = -1

fun main() {
    println("Hello, world!!!")
    println(Int.MAX_VALUE)
    println(Long.MAX_VALUE)
    println(Float.MAX_VALUE)
    println(Double.MAX_VALUE)
    println(Byte.MAX_VALUE)
    println(Int.MAX_VALUE)
    

    var currentAge: Int
    currentAge = 90
    
    println(MAX_AGE)
    
    var currentYear = "que ano hein?"
    	currentYear = 2021.toString() + " vai ser melhor"
    
    	println(currentYear)
    
    val count = 10
    val times = 9
    val r = times + count
    	println(r)
        println(count.plus(times))
        
    val count2 = 10
    var times2 = 9
    
    times2 += count2
    	println(times2)
        println(count2.plus(times2))
        
    var texto1 = "Olá, "
    var texto2 = "mundo "
    texto2 +=texto2
    println(texto1 + texto2)
    
    //comparação
    //
    
    val d = 22
    val t = 90
    
    	println(d > t)
        println(d.compareTo(t))
        println(d.compareTo(t) <= MORE)
        println(d.equals(t))
        
     // In e range
     // 
     val bingo = listOf(8,6,2,13)
     var number = (1..34).random()
     
     var age = (10..100).random()
     
     println(age)
     println(age in bingo)
     
     println(age)
     println ("idade " + (age in MIN_AGE..MAX_AGE))
     println(age >= MIN_AGE &&  age <= MAX_AGE)
    
    //STRING
    //
    val name = "Luzia"
    val s = "Oiii "
    
    	println("$name, ${s.capitalize()}!")
        println("$name, ${s.toUpperCase()}!")
        println("$name, ${s.trimEnd()}!")
        
     //Empty X Blank
     //
    val empty = ""
    val blank = "  "
    println(empty.length)
    println(blank.length)
    println(blank.isEmpty() && blank.isBlank())
    
    //Funçoes
    //
    
    /*private fun getFullName(name:String, lastName:String):String{
        val fullName = "$name $lastName"
        return fullName
    }*/
    
    fun getFullName(name:String, lastName:String) = "$name $lastName"


​    
​    
    //Fun Ordem Superior
    
    //val x:Int
    /*val z:Int
    
    z = calculate(34, 90, ::sum)
    	println(z)*/
    
    //Estrutura de cintrole
    //
    var a = 9
    var b = 8
    
    if(a>b){
        println("$a é maior que $b")
    }else{
        println("$a é menor $b")
    }


​    
​    
​    
​    
}

/*fun sum(n1:Int,n2:Int)

fun calculate(n1:Int,n2:Int,operation:(Int,Int)->Int):Int
    val result = operation(n1,n2)
    return result
}*/

//When, Elvis operation

/**
 * You can edit, run, and share this code. 
 * play.kotlinlang.org 
 */

fun main(){
    
    /*val grade = (0..12).random()
    	println(grade.getStudentStatus())*/
    
    var x:Int
    var y:Int? = null
    var	z:Int? = null
    var t = z?:y ?:-1
    
    println(t)


​        
​    
}

fun Int.getStudentStatus():String{
    
    println("nota $this")
    return when (this){
        in 0..4 -> "Reprovado"
        in 5..7 -> "Mediano"
        in 8..9 -> "Bom"
        10 -> "Excelente"
        else -> "Indefindo"
    }
//FOR

}fun main(){
    

    
        
        for(i in 0..10 step 2){
            print("$i ")
        }
        print("|")
        for(i in 0 until 10){
            print("$i ")
        }
        print("|")
        for(i in 10 downTo 0){
            print("$i ")
        }
        print("Terminou  ")
        
        var letra = "Kotlin"
        for (letter in letra){
            print(letter + " ")
        }
        

}

