# 🎓 Python OOP Assignments

Welcome to **Python OOP Assignments** — a curated set of 21 practical exercises that take you from beginner to confident object-oriented Pythonista! 🐍🚀

---

## 🌟 What You'll Learn

✔️ Classes and Objects  
✔️ self vs cls  
✔️ Public / Private / Protected  
✔️ Inheritance & super()  
✔️ Static, Class, and Instance Methods  
✔️ Decorators (@property, @staticmethod, etc.)  
✔️ Custom Exceptions  
✔️ Iterable Classes  
✔️ Composition & Aggregation  
✔️ And much more!

---

## 📂 Assignment List

| No. | Topic                            | File                   |
|-----|----------------------------------|------------------------|
| 01  | Using `self`                     | `01_student_self.py`   |
| 02  | Using `cls`                      | `02_counter_cls.py`    |
| 03  | Public Variables & Methods       | `03_car_public.py`     |
| 04  | Class Variables & Methods        | `04_bank_class.py`     |
| 05  | Static Methods                   | `05_mathutils_static.py` |
| 06  | Constructors & Destructors       | `06_logger_lifecycle.py` |
| 07  | Access Modifiers                 | `07_employee_access.py` |
| 08  | super() Function                 | `08_teacher_super.py`  |
| 09  | Abstract Classes                 | `09_shape_abstract.py` |
| 10  | Instance Methods                 | `10_dog_instance.py`   |
| 11  | Class Methods                    | `11_book_classmethod.py` |
| 12  | Static Methods Again             | `12_temp_converter.py` |
| 13  | Composition                      | `13_car_engine.py`     |
| 14  | Aggregation                      | `14_department_emp.py` |
| 15  | MRO & Diamond Inheritance        | `15_mro_diamond.py`    |
| 16  | Function Decorators              | `16_log_decorator.py`  |
| 17  | Class Decorators                 | `17_greeting_decorator.py` |
| 18  | Property Decorators              | `18_product_property.py` |
| 19  | `__call__()` & callable()        | `19_multiplier_callable.py` |
| 20  | Custom Exceptions                | `20_invalid_age.py`    |
| 21  | Custom Iterable Class            | `21_countdown_iterable.py` |

---

## 📸 Preview

```python
# Example from Assignment 20

class InvalidAgeError(Exception):
    pass

def check_age(age):
    if age < 18:
        raise InvalidAgeError("Age must be 18 or above")

try:
    check_age(15)
except InvalidAgeError as e:
    print("Caught an exception:", e)

🧠 Bonus
Want quizzes, notes, or MCQs based on these topics? Ask away and let’s turn this repo into a learning powerhouse! 💪

💡 Tip
Clone → Practice → Push → Share Your Journey 💻🔥

🛠️ Tools Used
Python 3.10+

VSCode / Jupyter Notebook

Git & GitHub

🙌 Contribute
Found a typo or want to add your solutions? Pull requests are welcome!

🧑‍💻 Author
Made with 💖 bynWarisha Akram
