km = float(input('Digite Km/h: '))
m = (km - 80)* 7.50
if km>80:
    print('Sua multa é de {}'.format(m))
else:
    print('Não há multa a pagar')
