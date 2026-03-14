# 🎨 Artistic Image Filters using Python

This project applies different **artistic image processing effects** to a normal image using Python.
The program converts an uploaded image into **pencil sketch and oil painting styles** using computer vision techniques.

---

# 📌 Features

The program generates the following artistic outputs:

✏️ **Pencil Sketch Effect**
Converts the original image into a black-and-white pencil sketch using grayscale conversion, inversion, Gaussian blur, and image division.

🎨 **Smooth Oil Pastel Effect**
Creates a soft and smooth painting effect by applying Gaussian and median filters on the brightness channel.

🖌 **Grainy Oil Paint Effect**
Produces a textured oil painting style with stronger filtering and reduced brightness levels.

🖼 **Edge Preserving Oil Paint Effect**
Maintains image edges and important details while creating an oil painting appearance.

---

# 🛠 Technologies Used

* **Python**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* **SciPy**
* **Pillow (PIL)**
* **Google Colab**

---

# 📦 Required Libraries

Install the required libraries using:

```bash
pip install numpy matplotlib scipy pillow opencv-python
```

---

# ⚙️ How the Program Works

1. Upload an image using Google Colab.
2. Read the image using PIL.
3. Convert the image into a NumPy array.
4. Normalize pixel values.
5. Apply **pencil sketch transformation**.
6. Convert the image from **RGB to HSV color space**.
7. Modify the **brightness channel** using Gaussian and Median filters.
8. Generate three oil painting styles.
9. Convert processed images back to RGB.
10. Display the results using Matplotlib.

---

# 🖼 Output

The program displays:

* Original Image
* Pencil Sketch
* Smooth Oil Pastel
* Grainy Oil Paint
* Edge Preserving Oil Paint

---

# ▶️ How to Run

1. Open the program in **Google Colab or Jupyter Notebook**.
2. Run the code.
3. Upload an image when prompted.
4. The program will automatically generate all artistic effects.

---

# 📚 Applications

* Image processing learning
* Computer vision experiments
* Artistic photo filters
* Digital art generation
* Photo editing tools



If you want, I can also give you a **much more professional GitHub README (with badges, demo images, and sections that impress recruiters)** which will make your **GitHub look like a strong developer profile.**
