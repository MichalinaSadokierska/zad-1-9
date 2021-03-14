#Zad1
#Zdefiniuj następujące zbiory, wykorzystując Python comprehension:
#A = {1 - x: x ∈ ∈ < 1, 10 >}
#B = {1, 4, 16,…, 4^7}
#C = {x: x ∈ ∈ B i x jest liczbą podzielną przez 2}

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

new_list = []

for num in numbers:
    new_list.append(num)

print(new_list)

my_list = [num - 4 for num in numbers]
print(my_list)

print("================================")

numbers = [1, 2, 3, 4, 5, 6, 7]

new_list = []

for num in numbers:
    new_list.append(num)

print(new_list)

my_list = [num ** 4 for num in numbers]
print(my_list)

print("================================")

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

new_list = []

for num in numbers:
    new_list.append(num)

print(new_list)

my_list = [num / 2 for num in numbers]
print(my_list)
#Zad2
#Wygeneruj losowo 10 elementów, zapisz je do listy1, następnie wykorzystując
#Python Comprehension zdefiniuj nową listę, która będzie zawierała tylko parzyste elementy.

lista = [(x, "parzysta" if x % 2 == 0 else "nieparzysta") for x in range(5)]

print(lista)
#Zad3
#Utwórz słownik z produktami spożywczymi do kupienia. Klucz to niech będzie nazwa produktu
#a wartość - jednostka w jakiej się je kupuje (np. sztuki, kg itd.). Wykorzystaj Python Comprehension
#do zdefiniowania nowej listy, gdzie będą produkty, których wartość to sztuki.

moj_slownik = {'sztuka': 'kg', 'obraz': 'cena'}

moj_slownik['klucz1'] = 'sztuka'
moj_slownik['klucz2'] = 'cena'

print(moj_slownik)
#Zad4
#Zdefiniuj funkcje, która sprawdzi czy trójkąt jest prostokątny.

a = 8
b = 6
c = 10

if ((a+b>c) and (a+c>b) and (b+c>a)):
    if ((a*a+b*b==c*c) or (a*a+c*c==b*b) or (c*c+b*b==a*a)):
        print("To jest trójkąt prostokątny")
    else:
        print("To nie jest trójkąt prostokątny")
else:
    print("Nie można zbudować trójkąta")
#Zad5
#Zdefiniuj funkcje która policzy pole trapezu. Funkcja ma przyjmować wartości domyślne.

a = input("Podaj pierwszą podstawe: ")

b = input("Podaj drugą podstawe: ")

h = input("Podaj wysokość: ")

pole = (int(a)+int(b))*int(h)/2

print("Pole trapezu wynosi: ", pole )
#Zad6
#Zdefiniuj funkcję która będzie liczyć iloczyn elementów ciągu.
#Parametry funkcji a1 (wartość początkowa), b (wielkość o ile mnożone są kolejne elementy), ile
# (ile elementów ma mnożyć). Ponadto funkcja niech przyjmuje wartości domyślne: a = 1, b = 4, ile = 10.
print("1"*" "* "4")
a = 1
b = 4

print(a*b)
#Zad7
#Napisz funkcje za pomocą operatora *, która wykona te same działanie co w zadaniu 6.
#=======nie rozumiem===========

#Zad8
#Napisz funkcję, która wykorzystuje symbol **. Funkcja ma przyjmować listę zakupów w postaci:
#klucz to nazwa produktu a wartość to jego koszt. Funkcja ma zliczyć ile jest wszystkich produktów
#w ogóle i zwracać całościową wartość tych produktów.

zakupy = ("masło, woda, cukier, mleko, ser, pomidor, rzodkiewka, marchewka, chleb")
postać = int(zakupy) ** int(2)

print(zakupy)
print(postać)
#Zad9
#Stwórz pakiet ciągi. Jeden moduł niech dotyczy działań i wzorów związanych z ciągami arytmetycznymi
#a drugi niech dotyczy działań i wzorów związanych z ciągami geometrycznymi.

a1 = 1 * 5
a2 = 2 * 5
a3 = 3 * 5
