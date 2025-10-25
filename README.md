# Car Management System

## 📝 Aufgabenstellung

Dieses Programm wurde als Übungsaufgabe für die Vorlesung **Objektorientierte Programmierung** entwickelt. Ziel war es, zentrale Techniken der objektorientierten Entwicklung in einem praktikablen Projekt umzusetzen.

## 🛠️ Verwendete Techniken

- **Kapselung**: Private Membervariablen in der Klasse `car_t`  
- **Konstruktoren**: Standard- und parametrisierter Konstruktor  
- **Initializer List**: Effiziente Initialisierung der Membervariablen  
- **Statische Factory-Methode**: Benutzerinteraktion und Objekterzeugung über `fromUserInput()`  
- **const-Methoden**: z. B. `void print() const` für sichere Ausgabe  
- **`std::vector`**: Dynamische Datenstruktur für Sammlung beliebig vieler Fahrzeuge  
- **Range-based for-loop mit `const auto&`**  
- **Richtige Pufferverwaltung mit `std::cin.ignore()`** zur sicheren Benutzereingabe  

## 🏃‍♂️ Was macht das Programm?

Nach dem Start bietet das CLI-Menü folgende Optionen:

- (1) Fahrzeug anlegen und ans Ende der Liste hinzufügen
- (2) Liste aller Fahrzeuge anzeigen
- (3) Alle Fahrzeuge löschen
- (q) Beenden

Jeder Eintrag besteht aus Name, Alter sowie Einzelhandelspreis. Alle Objekte werden in einem Vektor verwaltet und können beliebig angelegt, ausgelesen und gelöscht werden.

## 🧑‍💻 Kompilierung und Ausführung

**Voraussetzungen:**  

- g++ Compiler (C++17 oder neuer)

**Kompilieren:**

g++ -std=c++17 -Wall -Wextra -o car-program Car-Program.cpp

**Ausführen:**

./car-program

## 🏆 Lernziele

- Anwendung grundlegender objektorientierter Konzepte in C++
- Nutzung von Standardcontainern (`std::vector`)
- Sichere Benutzereingaben und Pufferbehandlung
- Dynamische Objekterzeugung und -verwaltung im CLI

---

Erstellt als Beispielprojekt für das Thema *Objektorientierte Programmierung (OOP)*.

