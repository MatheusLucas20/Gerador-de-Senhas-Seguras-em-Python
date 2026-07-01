import secrets
import string

CARACTERES = string.ascii_letters + string.digits + string.punctuation

while True:
    try:
        tamanho_senha = int(input("Digite tamanho da senha: "))
        if tamanho_senha <= 0:
            print("Digite um número maior que 0.\n")
            continue
        break
        
    except ValueError:
        print("Somente números!!!\n")
senha = ''.join(secrets.choice(CARACTERES) for _ in range(tamanho_senha))
print(f"\nSua senha é: {senha}")
