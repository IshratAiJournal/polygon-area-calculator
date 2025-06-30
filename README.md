# Polygon Area Calculator 🔷📐

This is **Project 4** from FreeCodeCamp’s *Scientific Computing with Python* certification.

### 📖 What it does
This project creates two classes — `Rectangle` and `Square` — to calculate area, perimeter, diagonal, and fit calculations.  
It also prints an ASCII-art style picture of the shape.

### 🧰 Features

- 📏 Set and get width, height, side  
- ➗ Calculate area, perimeter, diagonal  
- 🖼️ Display shape using stars (`*`)  
- 🔁 Check how many times a shape can fit inside another

### 🧠 Skills practiced

- Python Classes and Inheritance  
- Method Overriding  
- ASCII formatting  
- Geometric calculations  
- OOP fundamentals

### 🔁 Example Usage

```python
rect = Rectangle(10, 5)
print(rect.get_area())
print(rect.get_picture())

sq = Square(3)
print(sq.get_diagonal())
print(rect.get_amount_inside(sq))
