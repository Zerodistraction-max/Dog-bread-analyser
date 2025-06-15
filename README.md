# 🐶 Dog Breed Analyzer

Welcome to the **Dog Breed Analyzer** – your intelligent companion for identifying dog breeds from images! Whether you're a pet owner, dog lover, or just curious, this tool helps you recognize breeds with just one click.

---

## 🚀 Features

- 📸 **Image Upload**  
  Upload any dog image using a simple and intuitive interface.

- 🧠 **Breed Prediction**  
  Harnesses the power of machine learning to predict the most likely breed from the image.

- 💻 **User-Friendly Interface**  
  Clean and interactive design built for ease of use.

---

## 🛠️ How It Works

The Dog Breed Analyzer is powered by a **transfer learning model** trained on a vast dataset of dog images. When you upload an image:
1. The model processes the image.
2. Extracts features using a CNN backbone.
3. Returns the most probable dog breed.

Explore the model and training steps in the [`dog-vision.ipynb`](dog-vision.ipynb) notebook.

---

## ⚙️ Installation & Setup

Get the project running locally with these steps:

### 1️⃣ Clone the repository

```bash

git clone https://github.com/Zerodistraction-max/Dog-bread-analyser.git
cd Dog-bread-analyser

```

Install dependencies:
(Please replace [dependency-manager] with pip, conda, or similar, and list specific requirements if known, e.g., pip install tensorflow scikit-learn)


# Example:
# pip install -r requirements.txt

If there isn't a requirements.txt file, you might need to install common libraries for deep learning, such as:

tensorflow or pytorch

scikit-learn

Pillow (for image processing)

flask or django (if it's a web application)

---

## ▶️ Usage
Once you have set up the project locally:

Run the application:
(Specify the command to start the application, e.g., for a Python web app:)

# Example:
# python app.py

Open in your browser:
Access the application through your web browser, typically at http://localhost:5000 (or another port if specified).

Upload an image:
Use the provided interface to upload an image of a dog.

View results:
The application will display the predicted dog breed.



> 📝 **Note:** You can see all the steps in the [`dog-vision.ipynb`](dog-vision.ipynb) notebook.



# Contributors
This project was developed by:

Suryansh Sapehia (23BAI11228)

Karan Singh Negi (23BAI11904)

Pragati Singh (23BAI11161)



## Tools:

| Library        | Installation Command                   |
| -------------- | -------------------------------------- |
| Pandas         | `conda install pandas`                 |
| Matplotlib     | `conda install matplotlib`             |
| NumPy          | `conda install numpy`                  |
| Scikit-Learn   | `conda install scikit-learn`           |
| TensorFlow     | `pip install tensorflow`               |
| TensorFlow Hub | `pip install --upgrade tensorflow-hub` |
| Flask          | `pip install flask`                    |

