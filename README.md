# M-dias-notas
#Programa que lê notas e médias de um aluno onde ele pode ser aprovado, reprovado ou recuperação

nota1 = float(input('insira a primeira nota: '))
nota2 = float(input('insira a segunda nota: '))
media = (nota1+nota2)/2 

if media >= 7:
    print(f'Aluno aprovado com média {media}!!')
elif media >=5.0 and media <=6.9:
    print(f'Aluno em recuperação com média {media}')
else:
    print(f'Aluno reprovado ficou com média {media} ')

