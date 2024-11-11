import random 

karakterler = "+-/*!&$#?=@<>abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

uzunluk = int(input("Şifre Uzunluğu kaç Karakter OLsun?: "))

sifre = ""


for i in range(uzunluk):
    sifre += random.choice(karakterler)

print(sifre)