⚔️ Battle Legends – A Java Inheritance-Based Mythology Role-Playing Game

📖 About the Project

**Battle Legends** is a console-based role-playing game developed using Java and inspired by Indian mythology. Players enter the Kurukshetra Arena of Legends, choose a mythological hero, and battle against an opponent in multiple rounds.

The game features six legendary characters, each with unique attack and defense abilities inspired by their mythological powers. Randomly generated power values determine the winner of each round, making every battle unpredictable.

This mini-project was developed as part of learning Java Object-Oriented Programming (OOP) concepts during the **3rd semester**.

🎯 Objectives

* Demonstrate inheritance in Java.
* Understand method overriding and abstraction.
* Implement multiple subclasses from a common parent class.
* Develop an interactive, text-based role-playing game.
* Practice user input handling and random number generation.

🦸 Characters

The game includes six mythological heroes:

| Character   | Special Ability                                             |
| ----------- | ----------------------------------------------------------- |
| Arjuna      | Uses the Gandiva bow to shoot arrows                        |
| Karna       | Attacks with celestial arrows and defends with divine armor |
| Krishna     | Uses the Sudarshan Chakra and magical illusions             |
| Bhima       | Relies on immense strength and mace attacks                 |
| Dhanvantari | Uses divine healing powers                                  |
| Hanuman     | Uses mighty strength and divine protection                  |

🛠️ Technologies Used

* **Programming Language:** Java
* **Core Concepts:** Object-Oriented Programming (OOP)
* **Java Classes:** `Scanner`, `Random`
* **Game Type:** Console-based application

💡 Key Java Concepts

1. Inheritance

All six hero classes inherit common properties and behaviors from the abstract `Character` class, promoting code reusability.

2. Abstraction

The abstract `Character` class defines the `attack()` and `defend()` methods that each hero must implement.

3. Method Overriding

Each character provides its own implementation of the inherited `attack()` and `defend()` methods, giving every hero unique abilities.

4. Polymorphism

A `Character` reference can hold objects of different hero subclasses. The appropriate overridden methods are called based on the actual object.

5. Randomization

The `Random` class generates power values for the player and opponent during each round.

6. User Input and Validation

The `Scanner` class collects the player's name and character choices. The game also checks for invalid character selections.

🎮 How to Play

1. Start the game.
2. Enter your hero's name.
3. Choose your hero from the six available characters.
4. Select an opponent.
5. Watch the heroes perform their attack and defense actions.
6. Compare their randomly generated power values to determine the winner of each round.
7. Choose whether to continue playing or quit.
8. View the final score and battle result.

The game supports up to **five rounds**, unless the player chooses to quit earlier.

▶️ How to Run the Project

Prerequisites

* Java Development Kit (JDK) installed.
* A terminal or command prompt.

Steps

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Navigate to the project folder**

```bash
cd YOUR_PROJECT_FOLDER
```

**3. Compile the Java program**

```bash
javac BattleLegends.java
```

**4. Run the game**

```bash
java BattleLegends
```

> **Note:** The source file containing the `public class BattleLegends` should be named `BattleLegends.java`. Replace the placeholder repository URL and folder name with your actual details.

📚 What I Learned

Through this project, I gained practical experience with:

* Implementing inheritance and abstraction in Java.
* Using method overriding to create character-specific behaviors.
* Understanding polymorphism through parent-class references.
* Handling user input and validating choices.
* Applying random number generation in a simple game.
* Organizing Java classes to build an interactive console application.

🚀 Future Enhancements

Possible improvements include:

* Adding character-specific power levels and health points.
* Introducing special attacks and defensive strategies.
* Developing a graphical user interface (GUI).
* Adding more mythological characters and battle arenas.
* Implementing more advanced battle mechanics.

👩‍💻 Project Information

* **Project Name:** Battle Legends
* **Category:** Java Mini-Project
* **Domain:** Java Programming and Object-Oriented Design
* **Developed During:** 3rd Semester


*Battle Legends combines Indian mythology with Java OOP concepts to create a simple, interactive gaming experience.*
