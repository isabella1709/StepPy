# StepPy

StepPy is a simple web application built with Python that provides an interactive calculator interface through a clean and responsive web interface.

## 🚀 Features

- **Interactive Calculator**: Perform basic mathematical operations directly in your browser.
- **User-Friendly Interface**: Built using Flask and HTML templates.
- **Responsive Design**: Works well on desktop and mobile devices.

## 🛠️ Technologies Used

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Styling**: Pure CSS
- **WSGI Server**: Configured using `wsgi.py`

## 📁 Project Structure

```
StepPy/
├── calculator/
│   ├── __init__.py
│   └── ...
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
├── templates/
│   ├── base.html
│   └── index.html
├── app.py
├── requirements.txt
├── runtime.txt
├── wsgi.py
└── README.md
```

## ▶️ How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone https://github.com/isabella1709/StepPy.git
   cd StepPy
   ```

2. **Create a virtual environment** (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Start the application**:

   ```bash
   python app.py
   ```

5. **Access the app**:

   Open your browser and go to `http://localhost:5000`

## 📝 License

This project is licensed under the MIT License.

---

*This README was generated based on the current structure and purpose of the StepPy project. Make sure to update it as the project evolves.*
