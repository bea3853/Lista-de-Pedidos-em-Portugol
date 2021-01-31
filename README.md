# Lista-de-Pedidos-em-Portugol
Uma lista de pedidos feita em Portugol, com ela é possível somar o total de gastos com os produtos. 
algoritmo "PedidodeCompras"
var
   prod:caracter
   qtd:inteiro
   preco:real
   total:real
   resp:caracter


inicio
  Escreval("Pedido de Compras ")
  escreval("******************")
   total:=0
   enquanto resp <> "n" faca
      escreval("Digite o produto:")
      leia (prod)

      escreval("Digite o preço:")
      leia(preco)

      escreval ("Digite a quantidade:")
      leia(qtd)

      escreval ("Deseja continuar, s/n?")
      leia(resp)
      total:=total+preco
      escreval("---------------------------")

   fimenquanto
   escreval ("Total do Pedido  R$: ", total:1:2)


fimalgoritmo
