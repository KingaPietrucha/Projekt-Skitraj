# Test Plan

## Opis Projektu

Krotki opis projektu zawierajacy inforamcje:
- glowne przeznaczenie projektu
- zakres terytorialny
- platformy na jakich powinien dzialac
- uzyte technologie

![image.png](/.attachments/image-d131afa0-a8ac-40ab-84f0-ed489dd6904f.png)

## Srodowiska

Informacje zwiazane ze srodowiskamy zawierajacy: 
- link i nazwe sroowiska np. 
  [Developerskie](https://dev.skitraj.pl)
  [API]
  [Swagger]

Mozna zastosowac tabele np:

|Srodowisko| Link | Opis |
|--|--|--|
| Dev | https://dev.skitraj.pl | Web |
| Dev | https://dev.skitraj.pl/docs/#/ | API |
| All | https://dev.skitraj.pl | Figma |

## Konfiguracje

W tym miejscu wkazujemy zdefiniowane konfguracje, dobrze jest odniesc sie do wymagan lub analizy, ktora doprowdzila do powstana takich konfiguracji np. link do [statcounter](https://gs.statcounter.com/)

- link do stefiniowanych setow

### Przegladarki
- chrome
- opera
- edge
- firefox

### Rozdzielczosci

Tu warto wskazac czy uzywsamy fizycznych narzeczi, czy emulacji oraz jakie sa to rozdiezlczosci np. odnoszac sie do przygotowanych w devTool


## Zakres

Zawieramy tu inforamcje o zakresie testow, ktory moze byc referencja do wymagan lub lista funkcjonalnosci, 
warto wskazac rowniez obszary czy techniki testow, ktore sa po za zakresem np.

### Link do wymagan

### Poza zakresem

- Analiza UX - rozwiazanie zostalo zaprojektowane zgodnie z wytycznymi 
- Security - testy bezpieczenstwa beda wykonywane przez zewnetrzny zespol

## Techniki testowania

### Exploracja

Warto opisac pewne przyjete zalozenia np. podzial na jednostki czasowe oraz zdefiniowac co znaczy ta jednostka.
Dobrym przykladem bedzie wskazanie kilku podpowiedzi w zakresje jego przeprowadzania np. orentacja na sciezce pozytywnej, potem negatywnej, sposob rejestracji bledow itp. 

- Jednostki czasu wyrazane jako wielkosc 1eh (godzina exploracji) moze przyjmowac jej wielokrotnosc lub podzial przy zalozeniu ze najwieksza ilosc jednorazowo to 1eh a najmniejszy podzielnik to 0.25eh (15minut)

Limk do podsekcji [Testowanie Exploracyjne](/Narzędzia-wspomagające-proces-testowania)


### Testowanie Statyczne

Obejmuje analize wymagan pod katem ich spojnosci i testowalnosci uwzgledniajac cechy user story:
(tu wypisujemy ich cechy)

### Testowanie oparte o ryzyko

Skierowane w obszary, krytyczne, bledogenne 

### Zgadywanie bledow

Technika, w ktorej wykorzystujac baze wiedzy zarejestrowanych bledow (tu link do wszystkioch bledow, moze screenshot do wkazania ich ilosci i lepszej wizualizacji) szukamy bledow, podobnych np.:
- bledy walidacji formularza nieodpornosc na biale znaki - moze wystapic we wszystkich formularzach 
- logika wymagalnosci dostepna jest tylko po stronie kliekta, moze powodowac ze testy API ujawnia bledy wymagalnosci jako niezaimplementowane po stronie serwera

### Testowanie oparte o wymagania

Tu warto wkazac o sposobie ich przeprowadzania, glowne zalozenia np.
- Wymaganie musi zostac pokryte przez przynajmniej jeden przypadek testowy z uwzglednieniem ogolnej zasady dowodzenia dzialania np. jako potwierdzony user moge sie zalogowac, ale jako nie potwierdzony nie moge

## Struktura repozytorium testow

### Konwencja nazewnicza

#### Test Suite

Np. oparta na slowach kliczowych przyklad: logowanie, rejestracja

#### Test Case

Np. wykorzystanie BDD

#### Test Procedude

Np. wykorzystanie BDD

## Raprotowanie bledow

## KPI Dashboardy

## Narzedzia
 
### Nagrywanie i zrzut ekranu
- [Screenrec](https://screenrec.com/)
- [Test & Feedback](https://chrome.google.com/webstore/detail/test-feedback/gnldpbnocfnlkkicnaplmkaphfdnlplb)
- PSR

### API
- Postman
- ThunderClient

### IDE
- Visual Studio Code


