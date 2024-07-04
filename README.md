# OOP
h1 dokumentation 
objektorienteret programmering:

Objektorienteret Programmering (OOP): Definitionen på klasser og objekter, Indkapsling, Properties, Metoder, Overførsel, anvendelser af parametre, Returnering af datatyper fra metoder, Konstruktører, Overloading, Nedarvning og Polymorfism.
Principperne bag objektorienteret programmering
•	Klasser
•	Objekter
•	Indkapsling
•	Access Modifiers
•	Introduktion til nedarving
•	Polymorfisme
•	Properties
•	Hændelser (events)
•	Metoder
•	Parametre
•	Anvendelse af return-statment
Definitionen af et objekt:
Et objekt er en instans af en klasse. En klasse definerer objektets struktur og adfærd via felter og metoder.
~~~c#
lass Dog {
    public string Name;
    public int Age;

    public void Bark() {
        Console.WriteLine("Woof!");
    }
}

Dog myDog = new Dog();
myDog.Name = "Rex";
myDog.Age = 5;
myDog.Bark(); // Output: Woof!
~~~
Brugen af arrays:
Et array er en datastruktur, der indeholder en samling af elementer (af samme type), der er langt i sammenhængende hukommelsesområder.
~~~c#
int[] numbers = new int[5]; // Deklarerer et array af integers med 5 elementer.
numbers[0] = 1;
numbers[1] = 2;
numbers[2] = 3;
numbers[3] = 4;
numbers[4] = 5;

// Alternativ deklaration og initialisering
int[] otherNumbers = { 1, 2, 3, 4, 5 };
~~~
Debugging-værktøjer
Debugging-værktøjer hjælper programmører med at finde og rette fejl (bugs) i deres kode. Nogle almindelige debugging-værktøjer inkluderer:

•	Breakpoints:
 Tillader at pause eksekvering af programmet på bestemte linjer.
•	Watch-vinduer: 
Tillader at overvåge værdierne af variabler under kørsel.
•	Call Stack: 
Viser den aktuelle kaldsstak, så man kan se, hvilke metoder der blev kaldt, og i hvilken rækkefølge.
•	Stepping: 
Muliggør trinvis eksekvering af koden (Step Into, Step Over, Step Out).
•	Eksempel i Visual Studio:
Sæt et breakpoint ved at klikke i margen ved siden af linjen med koden, hvor du vil stoppe.
Kør programmet, og det vil stoppe ved breakpointet, hvor du kan inspicere variabler og anvende stepping-funktionerne.
Og meget andet/mere
Der er mange flere begreber og teknikker inden for grundlæggende og objektorienteret programmering, herunder:
•	Encapsulation: Indkapsling af data ved hjælp af adgangsmodifikatorer (public, private, protected).
•	Inheritance: Nedarvning, hvor en klasse kan arve felter og metoder fra en anden klasse.
•	Polymorphism: Evnen for objekter af forskellige klasser at blive behandlet som objekter af en fælles superklasse, ofte ved hjælp af metoder med samme navn.
