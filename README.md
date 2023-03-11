# Logica-de-programa-
oAlgoritmo "IdadeEmDias"

var
anos, meses, dias, IdadeEmDias : inteiro

inicio

escreva("Digite a idade em anos: ")
leia(anos)

escreva("Digite a idade em meses: ")
leia(meses)

escreva("Digite a idade em dias: ")
leia(dias)


IdadeEmDias <- (anos * 365) + (meses * 30) + dias


escreva("A idade em dias é: ", IdadeEmDias)

FimAlgoritmo
