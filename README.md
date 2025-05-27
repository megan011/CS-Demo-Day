# CS-Demo-Day

🛡️⚔ Battle Simulator ⚔🛡️

Concept: This is a battle game where different characters will fight against each other and gain their role of either a Knight, Soldier, or Archer based on a random dice roll. Players can either attack or use a special move each turn. Based on the role, the player will gain certain weapons that will affect their result in the battle. 

OOP (Classes): There will be a base class called Character that has different subclasses including a Knight, Soldier, and Archer based on a random dice roll. Weapons will also be represented by a Weapon class which contains weapon names with its subclasses being its damage power. 

Data Members:

name: character's name

health: numeric health value

role: "Knight", "Soldier", or "Archer"



Inheritance: All subclasses will use super() to have shared attributes from the Character class. 

Polymorphism: All fighters will be stored into a list 

Testing: A separate file that includes test functions using assert statements. This will check if the features in the battle are working correctly. 
