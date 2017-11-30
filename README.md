# training
#socks

pricesocks = 3
moneyonsocks = 50.0
pairsbought = moneyonsocks / pricesocks
print(pairsbought)

ostpairsbought = moneyonsocks%pricesocks
print(ostpairsbought)

debetmoney = moneyonsocks - ostpairsbought
print(debetmoney)

# shirts

priceshirt = 7
moneyonshirt = 50.0
pairsbought1 = moneyonshirt / priceshirt
print(pairsbought1)

ostpairsbought1 = moneyonshirt%priceshirt
print(ostpairsbought1)

debetmoneyshirt = moneyonshirt - ostpairsbought1
print(debetmoneyshirt)

# cigarret

pricecigarret = 0.55
moneycigarret = 50.0
pairsbought2 = moneycigarret / pricecigarret
print(pairsbought2)

ostpairsbought2 = moneycigarret%pricecigarret
print(ostpairsbought2)

debetmoneycigarret = moneycigarret - ostpairsbought2
print(debetmoneycigarret)

# debet money cash

debetmoneycash = ostpairsbought + ostpairsbought1 + ostpairsbought2
print(debetmoneycash)
