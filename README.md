real valorproduto

    escreva("Digite o valor do produto:  ")
    leia(valorproduto)

    se(valorproduto <=100){
      escreva("Não tem desconto!!!")
    }
       
       senao  se(valorproduto<=200){
        escreva("10% de desconto! \n")
        valorproduto = valorproduto *  0.9
        escreva("Valor  do produto com desconto:", valorproduto)
    }
    senao  se(valorproduto<=500){
        escreva("10% de desconto! \n")
        valorproduto = valorproduto *  0.8
        escreva("Valor  do produto com desconto:", valorproduto)
    }
  }
