### **README File for VS Code Users**

Below is the formatted `README.md` file tailored for Python projects and VS Code users.

---

```markdown
# Python Starter Project

This is a Python starter project that includes VS Code configuration, virtual environment support, and essential package installation instructions.

---

## 📁 **Project Structure**

```
project/
├── .vscode/
│   ├── settings.json     # VS Code configuration
│   ├── launch.json       # Debugging settings
│   ├── tasks.json        # Tasks configuration
├── .venv/                # Virtual environment (to be created)
├── requirements.txt      # List of required packages
└── README.md             # Project documentation
```

---

## 🛠️ **Instructions**

### 1. Check Python Version
Ensure Python **3.12 or later** is installed by running:
```bash
python3 --version
```

### 2. Create a Virtual Environment
1. Create the virtual environment:
   ```bash
   python3 -m venv .venv
   ```
2. Activate the virtual environment:
   - **Linux/WSL:**
     ```bash
     source .venv/bin/activate
     ```
   - **Windows:**
     ```bash
     .venv\Scripts\activate
     ```

### 3. Install Required Packages
To install all required packages:
```bash
pip install -r requirements.txt
```

### 4. Use VS Code Configuration
This project includes pre-configured files in the `.vscode/` directory:
- **`settings.json`**: Linting, formatting, and Python interpreter settings.
- **`launch.json`**: Debugging configurations.
- **`tasks.json`**: For running `pytest`.

---

## 🖥️ **Recommended VS Code Extensions**
Open the **Extensions Panel** (`Ctrl + Shift + X`) and install the following extensions:

1. [Python (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-python.python)  
2. [Pylance (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)  
3. [Test Explorer UI](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer)  
4. [Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)  
5. [Flake8 Linter](https://marketplace.visualstudio.com/items?itemName=ms-python.flake8)  

---

## 🧪 **Running Tests**
To run tests, use:
```bash
pytest
```

Or use the **VS Code Test Explorer** panel. 

---

## ⚙️ **Debugging**
1. Open the file you want to debug.
2. Navigate to the **Run and Debug** panel (`Ctrl + Shift + D`).
3. Select `Python: Current File` or `Run Pytest`.
4. Click the **▶️ Start Debugging** button.

---

## 🌟 **Project Features**
- **Automatic Formatting**: `Black` is enabled on save (`Ctrl + S`).
- **Linting**: Supports `Flake8`, `Pylint`, and `MyPy`.
- **Testing**: Fully integrated with `pytest`.

---

## 📖 **Additional Information**
- To update Python packages:
  ```bash
  pip install --upgrade -r requirements.txt
  ```
- If you add additional packages, update `requirements.txt` with:
  ```bash
  pip freeze > requirements.txt
  ```

---

## ❓ **Questions or Issues**
If you encounter any questions or issues while using this project, feel free to contact the project administrator.
```

---

### **Summary**
This README file provides clear and detailed instructions for **setting up a Python project** and using **VS Code configurations**. It ensures developers can quickly start working on the project without unnecessary complexity.

If further modifications are needed, let me know! 😊


### **README ფაილი VS Code-ის მომხმარებლებისთვის**

ქვემოთ წარმოდგენილია ფორმატირებული `README.md` ფაილი Python პროექტის სრულყოფილი გამოყენებისთვის VS Code-ში.

---

```markdown
# Python Starter Project

ეს არის Python-ის სტარტერი პროექტი, რომელიც შეიცავს VS Code-ის კონფიგურაციას, ვირტუალური გარემოს მხარდაჭერას და ძირითადი პაკეტების ინსტალაციის ინსტრუქციას.

---

## 📁 **პროექტის სტრუქტურა**

```
project/
├── .vscode/
│   ├── settings.json     # VS Code-ის კონფიგურაცია
│   ├── launch.json       # დებაგინგის პარამეტრები
│   ├── tasks.json        # ამოცანების (Tasks) პარამეტრები
├── .venv/                # ვირტუალური გარემო (ვირტუალური გარემოს შესაქმნელად)
├── requirements.txt      # საჭირო პაკეტების სია
└── README.md             # პროექტის ეს დოკუმენტაცია
```

---

## 🛠️ **ინსტრუქციები**

### 1. Python ვერსიის შემოწმება
გადადით ტერმინალში და შეამოწმეთ, რომ Python-ის ვერსია **3.12 ან უფრო ახალია**:
```bash
python3 --version
```

### 2. ვირტუალური გარემოს შექმნა
1. შექმენით ვირტუალური გარემო:
   ```bash
   python3 -m venv .venv
   ```
2. გააქტიურეთ ვირტუალური გარემო:
   - **Linux/WSL:**
     ```bash
     source .venv/bin/activate
     ```
   - **Windows:**
     ```bash
     .venv\Scripts\activate
     ```

### 3. საჭირო პაკეტების ინსტალაცია
ყველა საჭირო პაკეტის დასაყენებლად:
```bash
pip install -r requirements.txt
```

### 4. VS Code-ის კონფიგურაციის გამოყენება
პროექტი უკვე მოიცავს VS Code-ის კონფიგურაციის ფაილებს `.vscode/` დირექტორიაში:
- **`settings.json`**: ლინტინგი, ფორმატირება და Python ინტერპრეტატორის პარამეტრები.
- **`launch.json`**: დებაგინგის პარამეტრები.
- **`tasks.json`**: `pytest`-ის გაშვებისთვის.

---

## 🖥️ **VS Code-ის გაფართოებების ინსტალაცია**
გახსენით **Extensions Panel** (`Ctrl + Shift + X`) და დააყენეთ შემდეგი გაფართოებები:

1. [Python (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-python.python)  
2. [Pylance (Microsoft)](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)  
3. [Test Explorer UI](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer)  
4. [Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)  
5. [Flake8 Linter](https://marketplace.visualstudio.com/items?itemName=ms-python.flake8)  

---

## 🧪 **ტესტების გაშვება**
ტესტების ჩასატარებლად გამოიყენეთ:
```bash
pytest
```

ან **VS Code-ის Test Explorer**-დან. 

---

## ⚙️ **დებაგინგის გამოყენება**
1. გახსენით ფაილი, რომლის დებაგინგიც გსურთ.
2. გადადით **Run and Debug** პანელში (`Ctrl + Shift + D`).
3. აირჩიეთ `Python: Current File` ან `Run Pytest`.
4. დააჭირეთ **▶️ Start Debugging** ღილაკს.

---

## 🌟 **პროექტის ფუნქციები**
- **ავტომატური ფორმატირება**: `Black` ჩართულია შენახვისას (`Ctrl + S`).
- **ლინტინგი**: მხარდაჭერა `Flake8`, `Pylint` და `MyPy`.
- **ტესტირება**: `pytest` სრულად ინტეგრირებულია.

---

## 📖 **დამატებითი ინფორმაცია**
- Python პაკეტების განახლებისთვის:
  ```bash
  pip install --upgrade -r requirements.txt
  ```
- პროექტის გაფართოებისთვის დამატებითი პაკეტების ინსტალაციის შემდეგ, განაახლეთ `requirements.txt`:
  ```bash
  pip freeze > requirements.txt
  ```

---

## ❓ **კითხვები ან პრობლემები**
თუ პროექტის გამოყენებისას რაიმე კითხვა ან პრობლემა შეგექმნებათ, გთხოვთ, დაუკავშირდეთ პროექტის ადმინისტრატორს.
```

---

### **შეჯამება**
ეს README ფაილი შეიცავს დეტალურ ინსტრუქციებს **Python პროექტის დასაწყებად** და **VS Code-ის კონფიგურაციის გამოყენებისთვის**. ის შექმნილია, რათა მომხმარებლებს სწრაფად და მარტივად მიაწოდოს პროექტის ძირითადი ინფორმაცია. 

თუ რაიმე სხვა დამატება გჭირდებათ, მომწერეთ! 😊