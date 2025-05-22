#Tarefa: script da calculadora

#!/bin/bash

#Definir entradas e saídas

echo "Calculadora."
echo "Digite o primeiro número: "
read num1
echo "Digite o segundo número: "
read num2

#Definir funções lógicas da calculadora

soma=$(($num1 + $num2))
subtracao=$(($num1 - $num2))
multiplicacao=$(($num1 * $num2))
divisao=$(($num1 / $num2))

#Definir a saída com os resultados das operações

echo "Soma: $soma"
echo "Subtração: $subtracao"
echo "Multiplicação: $multiplicacao"
echo "Divisão: $divisao"


