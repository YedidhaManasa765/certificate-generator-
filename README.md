<h1 align="center">🎓 Certificate Generator</h1>

<p align="center">
A Python Flask application that generates personalized certificates from an Excel list and a certificate template image. All generated certificates are bundled into a ZIP file for easy download.
</p>

<hr>

<h2>📌 Features</h2>

<ul>
  <li>Upload an Excel file (<code>.xlsx</code>) containing participant names</li>
  <li>Upload a certificate template image (PNG/JPEG)</li>
  <li>Automatically generate personalized certificates</li>
  <li>Download all certificates together as a ZIP file</li>
  <li>Simple and user-friendly web interface</li>
</ul>

<h2>🚀 Project Overview</h2>

<p>
This project demonstrates:
</p>

<ul>
  <li>Building a web application using Flask</li>
  <li>Handling file uploads and downloads</li>
  <li>Generating images dynamically using Python</li>
  <li>Automating certificate creation for workshops, courses, and events</li>
  <li>Packaging generated files into a ZIP archive</li>
</ul>

<h2>🛠️ Skills Demonstrated</h2>

<ul>
  <li><strong>Flask</strong> – Backend web application development</li>
  <li><strong>Pandas</strong> – Reading and processing Excel files</li>
  <li><strong>Pillow (PIL)</strong> – Image manipulation and text rendering</li>
  <li><strong>HTML & Bootstrap</strong> – Frontend user interface</li>
  <li><strong>Python Automation</strong> – Batch certificate generation</li>
</ul>

<h2>📂 Project Structure</h2>

<pre>
certificate-generator/
│── app.py                     # Flask backend
│── requirements.txt           # Project dependencies
│── README.md                  # Project documentation
│── LICENSE                    # License information
│── .gitignore                 # Ignored files configuration
│
├── templates/
│   └── index.html             # Frontend interface
│
├── static/
│   └── background.jpeg        # Background image for webpage
│
├── samples/
│   ├── names.xlsx             # Sample participant list
│   ├── template1.png          # Sample certificate template
│   ├── NOTES.md               # Input/Output explanation
│   └── sample_certificates/   # Example generated certificates
</pre>

<h2>📸 Example Workflow</h2>

<h3>Input</h3>
<ul>
  <li>Excel file containing participant names</li>
  <li>Certificate template image</li>
</ul>

<h3>Output</h3>
<ul>
  <li>Personalized certificates in PNG format</li>
  <li>ZIP file containing all generated certificates</li>
</ul>

<h2>▶️ How to Run</h2>

<h3>1. Clone the Repository</h3>

<pre>
git clone https://github.com/your-username/certificate-generator.git
cd certificate-generator
</pre>

<h3>2. Install Dependencies</h3>

<pre>
pip install -r requirements.txt
</pre>

<h3>3. Run the Application</h3>

<pre>
python app.py
</pre>

<h3>4. Open in Browser</h3>

<pre>
http://127.0.0.1:5000
</pre>

<h2>🎯 Use Cases</h2>

<ul>
  <li>Workshops and Training Programs</li>
  <li>Online Courses</li>
  <li>Hackathons and Competitions</li>
  <li>College Events</li>
  <li>Webinars and Seminars</li>
</ul>

<h2>📜 License</h2>

<p>
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.
</p>

<h2>⭐ Support</h2>

<p>
If you find this project useful, consider giving it a star on GitHub!
</p>
