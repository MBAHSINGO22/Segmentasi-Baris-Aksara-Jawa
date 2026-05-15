<h1 align="center">Text Line Segmentation using OpenCV</h1>

<p align="center">
  Project for text line segmentation using Python and OpenCV
</p>

<hr>

<h2>📌 Description</h2>

<p>
This project performs text line segmentation from an input image using image processing techniques with Python and OpenCV. 
The system detects text lines using horizontal projection analysis and separates each line into individual image segments.
</p>

<p>Suitable for:</p>

<ul>
  <li>Document image processing</li>
  <li>OCR preprocessing</li>
  <li>Handwritten text segmentation</li>
  <li>Computer vision learning projects</li>
</ul>

<hr>

<h2>🛠 Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>OpenCV</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Google Colab</li>
</ul>

<hr>

<h2>✨ Features</h2>

<ul>
  <li>Image upload using Google Colab</li>
  <li>Grayscale conversion</li>
  <li>Gaussian Blur preprocessing</li>
  <li>Binary thresholding using Otsu method</li>
  <li>Morphological image processing</li>
  <li>Horizontal projection analysis</li>
  <li>Peak detection for text lines</li>
  <li>Automatic text line segmentation</li>
  <li>Visualization of segmentation results</li>
</ul>

<hr>

<h2>⚙️ Project Workflow</h2>

<ol>
  <li>Import required libraries</li>
  <li>Upload image</li>
  <li>Preprocess image</li>
  <li>Apply thresholding</li>
  <li>Calculate horizontal projection</li>
  <li>Detect text line peaks</li>
  <li>Determine segmentation boundaries</li>
  <li>Crop and save segmented lines</li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
project-folder/
│
├── VIKASABARU_235314099.ipynb
├── hasil_baris/
│   ├── line_1.png
│   ├── line_2.png
│   └── ...
└── README.md
</pre>

<hr>

<h2>🚀 Installation</h2>

<p>Clone repository:</p>

<pre>
git clone https://github.com/your-username/your-repository-name.git
</pre>

<p>Install dependencies:</p>

<pre>
pip install opencv-python numpy matplotlib
</pre>

<hr>

<h2>▶️ Usage</h2>

<ol>
  <li>Open notebook in Google Colab or Jupyter Notebook</li>
  <li>Upload handwritten/document image</li>
  <li>Run all cells</li>
  <li>View segmentation results</li>
</ol>

<hr>

<h2>💻 Example Code</h2>

<pre>
projection = np.sum(clean == 255, axis=1)

kernel_avg = np.ones(k) / k
smooth = np.convolve(projection, kernel_avg, mode='same')
</pre>

<hr>

<h2>📈 Future Improvements</h2>

<ul>
  <li>Character segmentation</li>
  <li>Word segmentation</li>
  <li>OCR integration</li>
  <li>Deep learning text detection</li>
  <li>Multi-column document support</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
Eugenius Kriswinar Adi Cahya
</p>

<hr>

<h2>📄 License</h2>

<p>
This project is intended for educational and research purposes.
</p>
