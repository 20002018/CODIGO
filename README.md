# CODIGO
x=int(input("Ingrese cantidad de dinero:"""))
b50=x//50
r50=x%50
b20=r50//20
r20=r50%20
b10=r20//10
r10=r20%10
m5=r10//5
r5=r10%5
m1=r5//1

print("Cantidad de billestes 50:",b50)
print("Cantidad de billetes 20:",b20)
print("Cantidad de billetes 10:",b10)
print("Cantidad de monedas 5:",m5)
print("Cantidad de monedas 1:",m1)
