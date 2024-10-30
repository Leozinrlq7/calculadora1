programa {
 
    inteiro op 
    real n1, n2
    caracter voltar
 
 funcao menu(){

    escreva ("Escolha a opção abaixo\n\n")
    escreva ("1-Somar|2-Subtrair|3-Multiplicar| 4-Dividir| 5-Sair|   \n")
    leia(op)

    escolha(op){
caso 1: soma() pare 
caso 2: subtrair() pare 
caso 3: multiplicar() pare 
caso 4: dividir() pare 
caso 5: pare 
caso contrario: escreva("Opção inválida\n\n")
    } 


 }
 
 
 
funcao inicio() {

   menu()    

}

funcao soma(){

limpa()
    escreva("Digite o primeiro número: ")
    leia(n1)
    escreva("Digite o segundo número: ")
    leia(n2)
    limpa()

    escreva("Seu resultado é ", n1 + n2, "\n")

    escreva("deseja voltar? s|n\n")
    leia(voltar)
    enquanto(voltar != 's')
  
    limpa()
    menu()


   

}

funcao subtrair(){

 limpa()
    escreva("Digite o primeiro número: ")
    leia(n1)
    escreva("Digite o segundo número: ")
    leia(n2)
    limpa()

    escreva("Seu resultado é ", n1 - n2, "\n")

  escreva("deseja voltar? s|n\n")
    leia(voltar)
    enquanto(voltar != 's')
    
    limpa()
    menu()

}

funcao multiplicar(){

limpa()
    escreva("Digite o primeiro número: ")
    leia(n1)
    escreva("Digite o segundo número: ")
    leia(n2)
    limpa()

    escreva("Seu resultado é ", n1 * n2, "\n")

    escreva("deseja voltar? s|n\n")
    leia(voltar)

    enquanto(voltar != 's')
     limpa()
     menu()
}
  funcao dividir(){
    
    limpa()
    escreva("Digite o primeiro número: ")
    leia(n1)
    escreva("Digite o segundo número: ")
    leia(n2)
    limpa()

    escreva("Seu resultado é ", n1 / n2, "\n")
    escreva("deseja voltar? s|n\n")
    leia(voltar)
    enquanto(voltar != 's')
    
    limpa()
    menu()

    }
    
}
