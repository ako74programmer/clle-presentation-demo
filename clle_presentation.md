---
marp: true
title: Przykładowa Prezentacja
theme: gaia
paginate: true
backgroundColor: #f0f0f0
backgroundImage: url('https://source.unsplash.com/random/1920x1080?nature')
---

### **Wprowadzenie do Control Language**

Dziś skupimy się na programowaniu w języku Control Language.

Przeanalizujemy, czym jest program CL, jak jest zbudowany, oraz nauczymy się go *kodować*, *kompilować* i *uruchamiać*.

Na przykładach, krok po kroku chcemy wskazać Wam, jak ułatwić sobie życie pisząc proste programy CL.

---

### **Control Language – podstawy**
- CL to język, który pozwala kontrolować wykonywanie programów na IBM i.
- W odróżnieniu od innych systemów, gdzie skrypty nie są kompilowane, skrypty CL są kompilowane i dzięki temu można je debugować.
- CL pozwala automatyzować operacje, które wcześniej były wykonywane ręcznie.
- Jest używany do tworzenia logiki aplikacji, automatyzacji procesów i zarządzania środowiskiem pracy.

---
 
### **Struktura programu CL**

Program CL składa się z kilku kluczowych elementów. Zawsze zaczyna się od `PGM` i kończy na `ENDPGM`. W środku znajdują się trzy główne sekcje:

1. Deklaracje – tutaj definiujemy zmienne.
2. Logika programu – tu odbywa się cała operacja.
3. Przekazywanie sterowania – wywołujemy inne programy lub procedury.

---

 #### Ogólne założenia programu CL ####

- Nazwy zmiennych zaczynają się od `&`.
- Znaki specjalne:
  - `:` oddziela etykietę od polecenia.
  - `/*` i `*/` otaczają komentarze.
  - `'` – otacza ciągi znaków.
- Wartości predefiniowane zaczynają się od `*` (np. `*ALL`).
- Dopuszczalne są nazwy generyczne (np. `PAY*`).
- Możemy kontynuować kod na nowej linii, używając `+` lub `-`.

---

### **Demo**

Programy CL **[democl7.clle](https://github.com/ako74programmer/cl-option-processor)**:

- Analiza struktury i praktyczne zastosowanie.

---

### **[Tworzenie Programu CLLE na IBM i - ćwiczenia](https://github.com/ako74programmer/clle-prezentacja/blob/main/demo-prezentacja.md)**

- Tworzenie bibliotek i plików źródłowych.
- Przykład prostego programu CLLE.
- Kompilacja oraz uruchomienie programu na IBM i.
 

---
 
### **Podsumowanie**

Podsumowując:
- Programy CL to podstawa automatyzacji na IBM i.
- Dają możliwość sterowania pracą aplikacji, personalizacji środowiska i uproszczenia codziennych zadań.
- Nauczyliśmy się podstawowej struktury programu, zasad kodowania oraz używania zmiennych i logiki.
 
---

 

### **Pytania do grupy:**

1. Jak CL upraszcza operacje na IBM i?
2. W jakich sytuacjach użyjecie CL w pracy administratora?

 
#### **Zachęta:**

Eksperymentujcie z pisaniem programów CL – to droga do efektywnego zarządzania systemem IBM i.

 ---

 ### **Materiały dodatkowe**

- Slajdy z prezentacji.
- Przykładowe kody do ćwiczeń.
- Linki do dokumentacji IBM i oraz przewodników po CL.
