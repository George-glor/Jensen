## Övningsuppgifter för Programming 1

---

## ÖVNING 1 – Variabler och datatyper

**a)** Skapa en variabel `namn` som innehåller ditt namn (str). Skapa en variabel `ålder` som innehåller din ålder (int). Skapa en variabel `längd` som innehåller din längd i meter (float). Skriv ut alla med `print()`.

**b)** Skapa en variabel `stad` och tilldela den en sträng. Skriv ut: "Jag bor i [stad]".

**c)** Konvertera strängen "123" till ett heltal och spara i en variabel. Skriv ut typen med `type()`.

**d)** Skapa en variabel `summa` som är summan av två heltal. Skriv ut resultatet.

**e)** Skapa en variabel som innehåller ett decimaltal. Avrunda det med `round()` och skriv ut.

**f)** Skapa en variabel `är_student` som är `True` eller `False` (bool). Skriv ut.

---

## ÖVNING 2 – Listor

**a)** Skapa en lista med 5 olika djur.

**b)** Hämta och skriv ut det tredje djuret i listan.

**c)** Lägg till ett nytt djur med `append()`.

**d)** Ta bort det sista djuret med `pop()`.

**e)** Ändra det första djuret till något annat.

**f)** Skriv ut hela listan med en `for`-loop.

**g)** Kolla om "hund" finns i listan med `in`.

**h)** Räkna hur många element listan har med `len()`.

---

## ÖVNING 3 – print() och input()

**a)** Skriv ett program som frågar användaren om deras favoritfärg och skriver ut: "Din favoritfärg är [färg]".

**b)** Fråga efter två tal och skriv ut summan.

**c)** Fråga efter namn och ålder. Skriv ut: "Hej [namn], du är [ålder] år gammal."

**d)** Fråga efter en stad och ett land. Skriv ut: "[stad] ligger i [land]".

**e)** Fråga efter ett tal och skriv ut talet gånger 2.

**f)** Fråga efter användarens hobby och skriv ut: "Kul att du gillar [hobby]!"

---

## ÖVNING 4 – Villkorssatser (if/elif/else)

**a)** Skriv ett program som frågar efter ett tal och skriver ut om talet är jämnt eller udda.

**b)** Fråga efter ålder. Skriv ut "Barn" (0-12), "Tonåring" (13-19), "Vuxen" (20+).

**c)** Fråga efter ett betyg (0-100). Skriv ut A (90+), B (80-89), C (70-79), D (60-69), E (50-59), F (<50).

**d)** Fråga efter ett tal. Skriv ut om talet är positivt, negativt eller noll.

**e)** Fråga efter användarnamn och lösenord. Skriv ut "Välkommen" om rätt, annars "Fel".

**f)** Fråga efter temperatur. Skriv ut "Kallt" (<10), "Milt" (10-20), "Varmt" (>20).

---

## ÖVNING 5 – Loopar (for och while)

**a)** Använd en `for`-loop för att skriva ut siffrorna 1-10.

**b)** Använd en `while`-loop för att skriva ut siffrorna 1-10.

**c)** Använd en `for`-loop för att skriva ut varje bokstav i ditt namn.

**d)** Använd en `while`-loop som frågar efter ett tal tills användaren skriver "0".

**e)** Använd en `for`-loop för att skriva ut alla element i en lista med frukter.

**f)** Använd en `while`-loop för att skriva ut jämna tal från 2 till 20.

**g)** Använd en `for`-loop med `range()` för att skriva ut 5, 10, 15, 20.

**h)** Använd en `while`-loop som räknar ner från 10 till 1.

---

## ÖVNING 6 – Funktioner

**a)** Skapa en funktion `hälsa()` som skriver ut "Hej!".

**b)** Skapa en funktion `hälsa_person(namn)` som skriver ut "Hej [namn]!".

**c)** Skapa en funktion `addera(a, b)` som returnerar summan av a och b.

**d)** Skapa en funktion `multiplicera(a, b)` som returnerar produkten.

**e)** Skapa en funktion `är_jämnt(tal)` som returnerar `True` om talet är jämnt.

**f)** Skapa en funktion `största(a, b, c)` som returnerar det största talet.

**g)** Skapa en funktion `omvänd(text)` som returnerar texten baklänges.

**h)** Skapa en funktion `medelvärde(lista)` som returnerar medelvärdet av alla tal i en lista.

---

## ÖVNING 7 – Analys och förbättring av program (förberedelse för fråga 7)

### Övning 7a – Enkel att-göra-lista

```python
tasks = []
while True:
    choice = input("1. Add 2. Show 3. Exit: ")
    if choice == "1":
        task = input("Task: ")
        tasks.append(task)
    elif choice == "2":
        print(tasks)
    elif choice == "3":
        break
```

**Uppgift:**
1. Nämn **två** brister.
2. Lägg till att uppgiften inte får vara tom.
3. Lägg till bekräftelse när uppgift läggs till.

---

### Övning 7b – Gissningsspel

```python
hemligt = 7
while True:
    gissning = input("Gissa ett tal 1-10: ")
    if gissning == hemligt:
        print("Rätt!")
        break
    else:
        print("Fel!")
```

**Uppgift:**
1. Nämn **två** brister.
2. Lägg till felhantering så programmet inte kraschar om användaren skriver bokstäver.
3. Ge ledtrådar ("För högt" / "För lågt").

---

### Övning 7c – Räknare

```python
tal = 0
while True:
    val = input("1. Öka 2. Minska 3. Visa 4. Avsluta: ")
    if val == "1":
        tal = tal + 1
    elif val == "2":
        tal = tal - 1
    elif val == "3":
        print(tal)
    elif val == "4":
        break
```

**Uppgift:**
1. Nämn **två** brister.
2. Lägg till att användaren själv får välja hur mycket att öka/minska.
3. Lägg till bekräftelse vid varje ändring.

---

### Övning 7d – Namnlista

```python
namn = []
while True:
    val = input("1. Lägg till 2. Ta bort 3. Visa 4. Avsluta: ")
    if val == "1":
        n = input("Namn: ")
        namn.append(n)
    elif val == "2":
        n = input("Namn att ta bort: ")
        namn.remove(n)
    elif val == "3":
        for n in namn:
            print(n)
    elif val == "4":
        break
```

**Uppgift:**
1. Nämn **tre** brister.
2. Lägg till felhantering vid borttagning (om namnet inte finns).
3. Visa listan med numrering.
4. Tillåt inte tomma namn.

---

### Övning 7e – Att-göra-lista med status

```python
todo = []
while True:
    print("1. Lägg till")
    print("2. Visa")
    print("3. Markera klar")
    print("4. Avsluta")
    val = input("Välj: ")
    
    if val == "1":
        uppgift = input("Uppgift: ")
        todo.append([uppgift, "Ej klar"])
    elif val == "2":
        print(todo)
    elif val == "3":
        nr = int(input("Nummer att markera klar: "))
        todo[nr-1][1] = "Klar"
    elif val == "4":
        break
```

**Uppgift:**
1. Nämn **tre** brister.
2. Lägg till felhantering vid markering (ogiltigt nummer).
3. Visa listan snyggt med numrering och status.
4. Lägg till möjlighet att ta bort uppgifter.

---

### Övning 7f – Enkel butik

```python
varor = []
priser = []
while True:
    val = input("1. Lägg till vara 2. Visa 3. Summa 4. Avsluta: ")
    if val == "1":
        vara = input("Vara: ")
        pris = float(input("Pris: "))
        varor.append(vara)
        priser.append(pris)
    elif val == "2":
        for i in range(len(varor)):
            print(varor[i], priser[i])
    elif val == "3":
        print(sum(priser))
    elif val == "4":
        break
```

**Uppgift:**
1. Nämn **tre** brister.
2. Lägg till felhantering vid pris (om användaren skriver bokstäver).
3. Visa varor med numrering och totalsumma.
4. Lägg till funktioner.

---

### Övning 7g – Quiz

```python
poäng = 0
svar1 = input("Vad är 2+2? ")
if svar1 == "4":
    poäng += 1
svar2 = input("Vad är huvudstaden i Sverige? ")
if svar2 == "Stockholm":
    poäng += 1
print("Du fick", poäng, "poäng")
```

**Uppgift:**
1. Nämn **två** brister.
2. Lägg till fler frågor med en loop.
3. Gör så att programmet inte kraschar vid tomma svar.
4. Visa rätt svar om användaren svarar fel.

---

### Övning 7h – Veckodagar

```python
while True:
    nr = input("Ange nummer 1-7 för veckodag: ")
    dagar = ["Måndag", "Tisdag", "Onsdag", "Torsdag", "Fredag", "Lördag", "Söndag"]
    print(dagar[int(nr)-1])
    fortsätt = input("Fortsätta? (j/n): ")
    if fortsätt == "n":
        break
```

**Uppgift:**
1. Nämn **två** brister.
2. Lägg till felhantering vid felaktig inmatning.
3. Skriv ut veckodagens namn istället för nummer.
4. Avsluta med "j" eller "n".

---

### Övning 7i – Betygsräknare

```python
betyg = []
while True:
    val = input("1. Lägg till betyg 2. Visa 3. Medel 4. Avsluta: ")
    if val == "1":
        b = int(input("Ange betyg 0-100: "))
        betyg.append(b)
    elif val == "2":
        print(betyg)
    elif val == "3":
        print(sum(betyg) / len(betyg))
    elif val == "4":
        break
```

**Uppgift:**
1. Nämn **tre** brister.
2. Lägg till felhantering (bokstäver, fel värden).
3. Visa betygen med bokstavsbetyg (A-F).
4. Tillåt inte betyg under 0 eller över 100.

---

### Övning 7j – Baklängesord

```python
while True:
    ord = input("Ange ett ord (eller 'stop' för att avsluta): ")
    if ord == "stop":
        break
    print(ord[::-1])
```

**Uppgift:**
1. Nämn **två** brister.
2. Lägg till så att programmet inte kraschar vid tomt ord.
3. Skriv ut hur många bokstäver ordet har.
4. Kolla om ordet är en palindrom (t.ex. "anna" blir samma baklänges).