# aula 7 Python 
produtos= {'Jeep renegade':'R$90.000', 'Jeep compass':'R$150.000',
           'troller':['R$200.000',2020] }
print(produtos)
print(produtos['Jeep renegade'])
print(produtos['troller'])
produtos['Jeep renegade'] = 'R$180.000'
print(produtos['Jeep renegade'])

produtos['audi'] = 'R$250.000'
print(produtos)

print('audi' in produtos)
print('bmw' in produtos)
