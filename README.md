#calculadora
operacao = input("Digite a operação desejada (soma, subtração, multiplicação, divisão): ")
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))
if operacao.lower() == "soma":
    resultado = num1 + num2
    print(f"O resultado da soma é: {resultado}")
elif operacao.lower()   == "subtracao":
    resultado = num1 - num2
    print(f"O resultado da subtração é: {resultado}")
elif operacao.lower() == "multiplicacao":
    resultado = num1 * num2
    print(f"O resultado da multiplicação é: {resultado}")
elif operacao.lower()   == "divisao":
    resultado = num1 / num2
    print(f"O resultado da divisão é: {resultado}")
else:
    print("Operação inválida. Por favor, escolha entre soma, subtração, multiplicação ou divisão.")
    
