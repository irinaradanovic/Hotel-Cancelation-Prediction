# Hotel-Cancelation-Prediction

Ovaj projekat se bavi predikcijom otkazivanja hotelskih rezervacija pomoću modela mašinskog učenja i veštačkih neuronskih mreža:

- Logistic Regression
- Random Forest
- MLP (Multi-Layer Perceptron)

Celokupan proces je implementiran u okviru Jupyter Notebook (`.ipynb`) datoteka koje su unapred pokrenute, tako da su svi grafikoni, metrike i rezultati odmah vidljivi.

---

# 1. Struktura projekta

```text
data/
│── hotel_booking.csv                 # Skup podataka 


prediction.ipynb                     # Jupyter sveska sa eksplorativnom analizom podataka, pripremom podataka, treningom i evaluacijom modela


requirements.txt              # Spisak svih neophodnih Python biblioteka
```

---

# 2. Priprema okruženja

Kako bi se obezbedilo izolovano okruženje, preporučuje se kreiranje virtuelnog okruženja.

## Korak 1: Kreiranje virtuelnog okruženja

U korenu projekta otvorite terminal i unesite sledeću komandu:

```bash
python -m venv venv
```

---

## Korak 2: Aktivacija virtuelnog okruženja

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

---

## Korak 3: Instalacija potrebnih biblioteka

Pokrenite sledeću komandu u terminalu:

```bash
pip install -r requirements.txt
```

---

# 3. Pokretanje i pregled projekta

Projekat je podeljen u logičke celine koje se mogu pokretati i pregledati kroz razvojna okruženja poput:

- Jupyter Notebook
- JupyterLab
- VS Code

---

## Opcija A: Pregled već pokrenutog koda

Pošto su sve ćelije unutar datotele `prediction.ipynb` izvršene pre čuvanja, dovoljno je otvoriti datoteku u željenom razvojnom okruženju.

Svi grafikoni, metrike i rezultati biće odmah vidljivi.

---

## Opcija B: Ponovno izvršavanje projekta od početka

Ukoliko želite da ponovo pokrenete projekat ili izvršite izmene:

1. Otvorite Jupyter svesku.
2. Pokrenite sve ćelije klikom na **Run All**.
3. Alternativno, možete selektovati pojedinačnu ćeliju i kliknuti na dugme **Play** pored ćelije.

---

## Napomena za VS Code

Nakon otvaranja sveske:

1. U gornjem desnom uglu kliknite na dugme **Select Kernel**.
2. Sa liste izaberite Python interpretator iz kreiranog virtuelnog okruženja (`venv`).
