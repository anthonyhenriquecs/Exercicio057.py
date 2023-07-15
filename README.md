# Exercicio057.py

sexo = str(input('Informe seu sexo: [M/F]')).strip().upper()[0]
print(sexo)
while sexo not in 'mMfF':
    sexo = str(input('Dados invalidos, por favor informe novamente:')).strip().upper()[0]
print('Sexo {} digitado com sucesso'.format(sexo))
