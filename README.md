# Ulesanne 1
#nimi=input("Mis on sinu nimi?: ")
#vanus=int(input("Kui vana sa oled?: "))

#print(f"Tere, maailm! Tervitan sind {Anora} Sa oled {20} aastat vana.")
#print("Tere, maailm! Tervitan sind",nimi,"Sa oled",vanus,"aastat vana.")
#print("Tere, maailm! Tervitan sind"+nimi+"\nSa oled"+str(vanus)+"aastat vana.")

# #Ülesanne 2
#vanus = 18
#eesnimi = "Jaak"
#pikkus = 16.5
#kas_käib_koolis = True
#print(f"Muutuja {20} on {type(vanus)} tüübi")
#print(f"Muutuja {Anora} on {type(eesnimi)} tüübi")

# Ülesanne 3
kommidearv=randint(1,100)
print(f"Laual on {kommidearv} komme")
kommidvõtmud=int(input("Mitu kommi tahad ära võtta?"))
onjäänud=kommidearv-kommidvõtmud
print(f"Laual on jäänud {onjäänud} komme")

# Ülesanne 4
# Kasutaja sisendi küsimine
umbermood = float(input("Sisesta puu ümbermõõt (sentimeetrites): "))
# Arvutame puu läbimõõdu
diameter = umbermood / 3.1415926535  # Läbimõõt = ümbermõõt / pi
# Kuvame tulemuse
print(f"Puu läbimõõt on {diameter:.2f} sentimeetrit.")

# Ülesanne 5
import math
# Kasutajalt mõõdud küsida
N = float(input("Sisesta ristküliku pikkus (m): "))
M = float(input("Sisesta ristküliku laius (m): "))
# Arvutame diagonaali pikkuse Pythagorase teoreemi järgi
diagonaal = math.sqrt(N**2 + M**2)
# Kuvame tulemuse
print(f"Ristkülikukujulise maatüki diagonaal on {diagonaal:.2f} meetrit.")

# Ülesanne 6
aeg = float(input("Mitu tundi kulus sõiduks? "))
teepikkus = float(input("Mitu kilomeetrit sõitsid? "))
kiirus = teepikkus / aeg  # Õige valem: kiirus = teepikkus / aeg
print("Sinu kiirus oli " + str(kiirus) + " km/h")

# Ulesanne 7
a1=randint(0,100)
a2=randint(0,100)
a3=randint(0,100)
a4=randint(0,100)
a5=randint(0,100)
keskmine=(a1+a2+a3+a4+a5)/5
print(f"Arvud olid: {a1}, {a2}, {a3}, {a4}, {a5}. Nende keskmine on {keskmine}. ")

#Ülesanne 8
#1
tekst="""   
    @..@
   (----)
  ( \__/ )
  ^^ "" ^^  """
print(tekst)
#2
print("    @..@")
print("   (----)")
print("  ( \__/ )")
print("""  ^^ "" ^^  """)

#Ülesanne 9
a=randint(1,100)
b=randint(1,100)
c=randint(1,100)
P=a+b+c
print(f"a={a}, b={b}, c={c}, P={P}")

# Ulesanne 10
# Pitsa hind ja jootraha protsent
pitsa_hind = 12.90
jootraha_protsent = 0.10  # 10%
# Kasutaja sisend: mitu inimest
P = int(input("Mitu inimest söövad pitsat? "))
# Arvutame jootraha
jootraha = pitsa_hind * jootraha_protsent
# Arvutame kogu summa (pitsa hind + jootraha)
kogusumma = pitsa_hind + jootraha
# Arvutame, kui palju igaüks peab maksma
maks = kogusumma / P
# Kuvame tulemuse
print(f"Igaüks peab maksma: {maks:.2f} €.")

