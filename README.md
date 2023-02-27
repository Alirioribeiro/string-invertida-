# string-invertida-
# Define a string a ser invertida
string = "Hello, world!"

# Inicializa uma string vazia para armazenar a string invertida
string_invertida = ""

# Itera sobre os caracteres da string, de trás para frente
for i in range(len(string) - 1, -1, -1):
    # Adiciona cada caractere da string original na ordem inversa à string invertida
    string_invertida += string[i]

# Imprime a string invertida
print(string_invertida)
