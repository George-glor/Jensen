1. Variabler och datatyper (5 övningar)
Övning 1.1
Skapa tre variabler:

Ett heltal (int) med ditt ålder

Ett flyttal (float) med din längd i meter

En sträng (str) med ditt förnamn
Skriv ut alla tre med print().

Övning 1.2
Vad skrivs ut?

python
x = 10
y = "20"
z = x + int(y)
print(z)
Övning 1.3
Skapa en variabel pris = 99.90 och antal = 3. Beräkna totalsumman och skriv ut "Totalt: 299.7 kr".

Övning 1.4
Konvertera strängen "3.14" till float och multiplicera med 2. Skriv ut resultatet.

Övning 1.5
Vad är skillnaden mellan int(), float() och str()? Ge ett exempel på varje.

2. Listor (5 övningar)
Övning 2.1
Skapa en lista med 5 städer. Skriv ut den tredje staden med index.

Övning 2.2
Skapa en tom lista. Lägg till tre djur med append(). Skriv ut hela listan.

Övning 2.3
Skapa en lista [10, 20, 30, 40, 50]. Ändra det tredje elementet till 99. Skriv ut listan.

Övning 2.4
Skapa en lista med 3 böcker. Använd len() för att skriva ut hur många böcker som finns.

Övning 2.5
Skapa en lista med 4 färger. Ta bort den andra färgen med pop(). Skriv ut listan.

3. print() och input() (5 övningar)
Övning 3.1
Skriv ett program som frågar efter användarens stad och skriver ut "Du bor i [stad]".

Övning 3.2
Använd input() för att fråga efter två tal. Skriv ut summan.

Övning 3.3
Vad är skillnaden mellan print("Hej", "världen") och print("Hej" + "världen")?

Övning 3.4
Skriv ett program som frågar efter namn och ålder. Skriv ut "Hej [namn], du är [ålder] år."

Övning 3.5
Använd input() för att fråga efter ett tal. Multiplicera med 5 och skriv ut resultatet.

4. Villkorssatser (5 övningar)
Övning 4.1
Skriv ett program som frågar efter ett tal. Skriv ut "Stort!" om talet är större än 10.

Övning 4.2
Skriv ett program som frågar efter ålder. Skriv ut "Myndig" om ålder >= 18, annars "Ej myndig".

Övning 4.3
Skriv ett program som frågar efter ett betyg (0-100). Skriv ut:

"A" om >= 90

"B" om >= 80

"C" om >= 70

"F" om < 70

Övning 4.4
Skriv ett program som frågar efter ett tal. Skriv ut "Jämnt" om talet är jämnt, annars "Udda".

Övning 4.5
Skriv ett program som frågar efter användarnamn och lösenord. Skriv ut "Inloggad" om användarnamn är "admin" och lösenord är "1234", annars "Fel".

5. Loopar (5 övningar)
Övning 5.1
Skriv en for-loop som skriver ut talen 1 till 10.

Övning 5.2
Skriv en while-loop som skriver ut talen 5, 4, 3, 2, 1.

Övning 5.3
Skriv en for-loop som loopar igenom listan ["apelsin", "äpple", "banan"] och skriver ut varje frukt.

Övning 5.4
Skriv en while-loop som frågar efter ett tal. Loopen fortsätter tills användaren skriver "0".

Övning 5.5
Skriv en for-loop som räknar summan av talen 1 till 100. Skriv ut summan.

6. Funktioner (5 övningar)
Övning 6.1
Skapa en funktion halsa() som skriver ut "Hej!" och anropa den.

Övning 6.2
Skapa en funktion kvadrat(tal) som returnerar talet i kvadrat. Anropa med 5.

Övning 6.3
Skapa en funktion summa(a, b) som returnerar summan av två tal. Anropa med 3 och 7.

Övning 6.4
Skapa en funktion ar_myndig(ålder) som returnerar True om ålder >= 18, annars False.

Övning 6.5
Skapa en funktion celsius_till_fahrenheit(c) som returnerar grader i Fahrenheit. Formel: (c * 9/5) + 32.

7. Analys och förbättring (5 övningar)
Övning 7.1 – Matematikprogram

python
tal = input("Ange ett tal: ")
print(tal * 2)
a) Nämn två brister.
b) Förbättra med felhantering.
c) Reflektera.

Övning 7.2 – Namnhanterare

python
namn = []
while True:
    val = input("1. Lägg till 2. Visa 3. Avsluta: ")
    if val == "1":
        namn.append(input("Namn: "))
    elif val == "2":
        print(namn)
    elif val == "3":
        break
a) Nämn två brister.
b) Förbättra med validering och feedback.
c) Reflektera.

Övning 7.3 – Produktkatalog

python
produkter = ["mjölk", "bröd", "ägg"]
val = input("Vilken produkt? ")
if val in produkter:
    print("Finns i lager")
a) Nämn två brister.
b) Förbättra med loop och felhantering.
c) Reflektera.

Övning 7.4 – Gissningslek

python
hemligt = 7
gissning = input("Gissa ett tal: ")
if gissning == hemligt:
    print("Rätt!")
else:
    print("Fel!")
a) Nämn två brister.
b) Förbättra med loop och felhantering.
c) Reflektera.

Övning 7.5 – Temperaturomvandlare

python
c = input("Ange Celsius: ")
f = (c * 9/5) + 32
print(f)
a) Nämn två brister.
b) Förbättra med felhantering och tydlig feedback.
c) Reflektera.
