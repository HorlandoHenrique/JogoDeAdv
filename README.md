# JogoDeAdv
numeroSecreto = 7
tentativas = 0
limiteTentativas = 3

while tentativas < limiteTentativas:
    palpite = int(input("Tente adivinhar o número (entre 1 e 10): "))
    tentativas += 1

    if palpite == numeroSecreto:
        print("Parabéns! Você acertou o número!")
        break
else:
    print(f"Você usou todas as tentativas. O número era: {numeroSecreto}")
