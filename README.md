# sorteio_numero
Sorteio random de um número no android/kotlin


## Programa - MainActivity

Criar a função 

    fun sortear(view: View){
        val numero = Random().nextInt(11)
        val textoResultado = findViewById<TextView>(R.id.text_resultado)
        textoResultado.setText("número gerado $numero")
    }

## Tela - activity_main

![image](https://github.com/andreamatos/sorteio-numero/assets/42948627/278ae353-726f-4a1f-8595-ae8494ad8c8b)


## Resultado Final

![image](https://github.com/andreamatos/sorteio-numero/assets/42948627/c0833da0-0849-4ddd-96af-6a77a478123f)
