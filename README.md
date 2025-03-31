# 🎨 Image Color Palette Generator

This is a simple web application built with **Flask** that allows users to upload an image and generates a 10-color palette based on dominant colors using **KMeans Clustering**. Users can click on any color box to copy its HEX code.

## ✨ Example

1. Upload an image.
2. The app shows the image and 10 color boxes below it.
3. Click on any color to copy its HEX code!
![image](https://github.com/user-attachments/assets/07956e42-5af8-48ef-ad2e-a55994386696)

---

## 📸 Features

- Upload images (`.png`, `.jpg`, `.jpeg`, `.gif`)
- Extract dominant colors using KMeans
- Display colors as clickable boxes
- Click-to-copy HEX codes
- Responsive and clean UI (Bootstrap 5 + custom CSS)

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/color-palette-generator.git
   cd color-palette-generator
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```bash
   python main.py
   ```

5. Visit [http://localhost:5001](http://localhost:5001) in your browser.

---

## 📂 Project Structure

```
├── main.py               # Flask backend logic
├── templates/
│   └── index.html        # Frontend template
├── static/
│   ├── uploads/          # Uploaded images
│   └── css/
│       └── styles.css    # Custom styles
├── requirements.txt      # Python dependencies
└── README.md             # This file
```

---

## 🧪 Dependencies

- Flask
- Flask-Bootstrap
- Flask-CKEditor
- matplotlib
- scikit-learn
- numpy
- Pillow

> 📌 You can generate a `requirements.txt` with:
```bash
pip freeze > requirements.txt
```

---



## 📜 License

MIT License © 2025

```

Let me know if you want this exported as a file, or if you'd like me to auto-generate the `requirements.txt` for you too!

