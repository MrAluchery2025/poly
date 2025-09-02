# poly
📌 Polymorphism Challenge 🎭

This project demonstrates the concept of polymorphism in Python using object-oriented programming (OOP).

🔹 What is Polymorphism?

Polymorphism allows objects of different classes to share the same method name but behave differently depending on the object calling the method.

In this example, different vehicles implement the same method move(), but each defines its own unique behavior:

🚗 Car → "Driving on the road"

✈️ Plane → "Flying in the sky"

🚤 Boat → "Sailing on the water"

🚴 Bicycle → "Pedaling on the street"

🛠️ How it Works

A base class Vehicle is defined with a move() method placeholder.

Each subclass (Car, Plane, Boat, Bicycle) overrides the move() method with its own action.

A list of vehicles is created, and each object calls its move() method.

Polymorphism ensures that the correct version of move() is executed for each object.

▶️ Running the Program
python polymorphism_challenge.py

✅ Expected Output
🚗 Driving on the road...
✈️ Flying in the sky...
🚤 Sailing on the water...
🚴 Pedaling on the street...
