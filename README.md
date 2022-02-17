# Elton-da-Silva
Questao1 Visualg para Capgemini 
var
n:inteiro

inicio
escreva("Escolha um número de um à seis,digite e veja o resultado da escada na tela:")
leia(n)
se n = 1 entao
   escreval("     *")
senao

   se n = 2 entao
      escreval("     *")
      escreval("    **")
   senao

      se n = 3 entao
         escreval("     *")
         escreval("    **")
         escreval("   ***")
      senao

         se n = 4 entao
            escreval("     *")
            escreval("    **")
            escreval("   ***")
            escreval("  ****")
         senao

            se n = 5 entao
               escreval("     *")
               escreval("    **")
               escreval("   ***")
               escreval("  ****")
               escreval(" *****")
            senao

               se n = 6 entao
                  escreval("     *")
                  escreval("    **")
                  escreval("   ***")
                  escreval("  ****")
                  escreval(" *****")
                  escreval("******")
               fimse
            fimse
         fimse
      fimse
   fimse
fimse
fimalgoritmo


Questao2 Visualg para Capgemini
var
nome,senha:caractere
comprimento:inteiro
inicio
escreval("Digite o nome:")
leia(nome)
repita
   escreval("Digite sua senha:")
   leia(senha)
   comprimento <- compr (senha)
   limpatela
   escreval("A sua senha contem",comprimento," caracteres")

   se comprimento <= 5 entao
      escreval("Senha fraca,digite seis caracteres no mínimo!")
   senao
      se comprimento >= 6 entao
         escreval("Senha forte!")
      fimse
   fimse
ate comprimento >= 6
fimalgoritmo



