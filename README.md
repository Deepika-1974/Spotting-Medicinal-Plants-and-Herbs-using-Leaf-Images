
# Spotting Medicinal Plants and Herbs using Leaf Images🧠📸

A web-based **image classification application** built using **Flask** and a trained **Convolutional Neural Network (CNN)** model.  
This project allows users to upload an image and get predictions on the object or category recognized by the trained model.

---

## 🚀 Features

- 🖼️ Upload images through a clean web interface  
- 🤖 Predict image class using a trained CNN (`CNN.h5`)  
- 🔒 User authentication (Signup & Login)  
- 📊 Interactive dashboard for viewing results  
- 🧩 Modular Flask structure with templates and static assets  

---

## 🗂️ Project Structure

```

flask_app/
├── app.py                # Main Flask application
├── static/
│   ├── CNN.h5            # Trained CNN model
│   └── uploads/          # Uploaded images
├── templates/
│   ├── about.html
│   ├── dashboard.html
│   ├── home.html
│   ├── login.html
│   ├── result.html
│   └── signup.html

---

## 🧰 Installation and Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/flask-app.git
cd flask-app
````

### 2️⃣ Create a Virtual Environment

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows


### 3️⃣ Install Dependencies

pip install -r requirements.txt

If `requirements.txt` is missing, you can create one with:

pip freeze > requirements.txt

### 4️⃣ Run the Application

python app.py

Then open your browser and go to:
http://127.0.0.1:5000

## 🧠 Model Information

The application uses a pre-trained **CNN model (`CNN.h5`)** located in the `static/` folder.
It is trained on the **CIFAR-10** dataset for multi-class image classification.

## 🖥️ Templates Overview

| Template         | Description                             |
| ---------------- | --------------------------------------- |
| `home.html`      | Landing page for the app                |
| `signup.html`    | User registration form                  |
| `login.html`     | User login page                         |
| `dashboard.html` | Displays user activity or image results |
| `result.html`    | Shows classification results            |
| `about.html`     | About the project and team              |

---

## 📦 Dependencies

* Flask
* TensorFlow / Keras
* NumPy
* Pillow

## 🌐 Deployment

You can deploy this app easily on platforms like:

* [Render](https://render.com/)
* [Railway](https://railway.app/)
* [Heroku](https://www.heroku.com/)
* [PythonAnywhere](https://www.pythonanywhere.com/)

---

## 👩‍💻 Author

**Deepika T**
📧 [[T.Deepika1974@gmail.com](mailto:T.Deepika1974@gmail.com)]
🔗 [GitHub Profile](https://github.com/Deepika-1974)


## 💡 Acknowledgements

* [Flask Documentation](https://flask.palletsprojects.com/)
* [TensorFlow/Keras](https://www.tensorflow.org/)
* [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
