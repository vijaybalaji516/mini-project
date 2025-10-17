### 🧰 **1. Extract the ZIP File**

* Locate the file `Plant-Disease-Recognition-System-main.zip`.
* Right-click → **Extract All** (Windows) or use Archive Manager (Linux/macOS).
* This will create a folder named `Plant-Disease-Recognition-System-main`.

---

### 🐍 **2. Install Python**

* Make sure Python (version **3.7+**) is installed.
* Check with:

```bash
python --version
```

or

```bash
python3 --version
```

👉 If not installed, download from [https://www.python.org/downloads/](https://www.python.org/downloads/) and install it.
During installation, check ✅ **“Add Python to PATH.”**

---

### 📁 **3. Open the Project Folder**

* Open **Command Prompt** (Windows) or **Terminal** (Linux/macOS).
* Navigate into the extracted folder:

```bash
cd Plant-Disease-Recognition-System-main
```

---

### 🧪 **4. Create a Virtual Environment (Recommended)**

This keeps project dependencies isolated:

```bash
python -m venv venv
```

Activate it:

* **Windows:**

  ```bash
  venv\Scripts\activate
  ```
* **Linux/macOS:**

  ```bash
  source venv/bin/activate
  ```

---

### 📦 **5. Install Required Libraries**

The project usually contains a `requirements.txt` file. Install dependencies with:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, typical dependencies for plant disease detection include:

```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python flask
```

---

### 🧠 **6. (Optional) Check/Download the Dataset**

* Some projects include a `dataset` or `data` folder.
* If not, the README may have a link to download the dataset.
* Place the dataset inside the project directory if required.

---

### 🏃 **7. Run the Application**

Many such projects use Flask or Streamlit for the web interface.
Look for a file named something like:

* `app.py`
* `main.py`
* `run.py`

Then run:

```bash
python app.py
```

or

```bash
streamlit run app.py
```

---

### 🌐 **8. Open in Browser**

Once the server starts, it will show something like:

```
Running on http://127.0.0.1:5000/
```

or

```
Local URL: http://localhost:8501
```

👉 Open that URL in your browser to use the Plant Disease Recognition System.

---

### 🧼 **9. Deactivate Virtual Environment (When Done)**

```bash
deactivate
```

---

Would you like me to **open the ZIP and check the exact file to run** (like `app.py` or `main.py`) so I can give you the exact run command?
