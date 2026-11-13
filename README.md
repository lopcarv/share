# share
Repositorio para compartilhar


# Exercício 11: Calculadora de Imposto sobre Vendas
# Solicite o valor bruto da nota fiscal, limpe o texto,
# converta para float e calcule 15% de imposto.

valor = input("Digite o valor bruto (Ex: R$ 5.000,00): ")
valor = valor.replace("R$", "").replace(".", "").replace(",", ".").strip()
valor = float(valor)
imposto = valor * 0.15
print(f"Imposto calculado: R$ {imposto:.2f}")
