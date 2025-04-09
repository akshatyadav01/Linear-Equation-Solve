<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  
</head>
<body>

  <h1>🧮 Linear Equation Calculator</h1>
  <p>
    A desktop application built using <strong>Python</strong>, <strong>Tkinter</strong>, and <strong>MySQL</strong>,
    designed to solve systems of linear equations using <strong>Gauss-Jacobi</strong>, <strong>Gauss-Seidel</strong>, and <strong>Residual</strong> methods.
    It features an intuitive graphical interface and detailed result tables for clear interpretation.
  </p>

  <h2>🚀 Features</h2>
  <ul>
    <li>Solves 3-variable linear equations of the form <code>Ax + By + Cz = D</code></li>
    <li>Supports Gauss-Jacobi, Gauss-Seidel, and Residual methods</li>
    <li>Tabulated display of each iteration</li>
    <li>Interactive GUI using <code>ttkbootstrap</code> and <code>Tkinter</code></li>
    <li>Partial pivoting for increased numerical stability</li>
    <li>Educational and user-friendly</li>
  </ul>

  <h2>🛠️ Tech Stack</h2>
  <table>
    <tr><th>Technology</th><th>Description</th></tr>
    <tr><td>Python</td><td>Core language</td></tr>
    <tr><td>Tkinter</td><td>GUI framework</td></tr>
    <tr><td>ttkbootstrap</td><td>Modern styled widgets</td></tr>
    <tr><td>MySQL</td><td>Optional - data logging (future)</td></tr>
    <tr><td>PyArduino</td><td>Optional - Arduino input (future)</td></tr>
    <tr><td>pywhatkit</td><td>Optional - Automation (future)</td></tr>
  </table>

  <h2>📷 Screenshots</h2>
  <p>Add UI and table screenshots here (e.g., <code>assets/screenshot1.png</code>).</p>

  <h2>🧪 Solving Methods</h2>

  <h3>1. Gauss-Jacobi Method</h3>
  <p>
    An iterative method using initial guesses. Each variable is updated independently using previous iteration values.
  </p>

  <h3>2. Gauss-Seidel Method</h3>
  <p>
    A faster-converging method using updated values immediately within the same iteration.
  </p>

  <h3>3. Residual Method</h3>
  <p>
    Computes residuals (difference between LHS and RHS) and updates the variable with the maximum residual.
  </p>

  <h2>📦 Setup Instructions</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/your-username/linear-equation-calculator.git
cd linear-equation-calculator</code></pre>
    </li>
    <li>Install dependencies:
      <pre><code>pip install ttkbootstrap</code></pre>
    </li>
    <li>Run the application:
      <pre><code>python linear_calculator.py</code></pre>
    </li>
  </ol>

  <h2>🎮 How to Use</h2>
  <ul>
    <li>Open the application</li>
    <li>Enter coefficients for 3 equations</li>
    <li>Select solving methods: Jacobi, Seidel, or Residual</li>
    <li>Click "Enter" to compute</li>
    <li>Review iteration tables and final results</li>
  </ul>

  <h2>📁 Folder Structure (Recommended)</h2>
  <pre><code>linear-equation-calculator/
├── linear_calculator.py   # Main script
├── README.html            # This file
└── assets/                # (Optional) Screenshots and other assets</code></pre>

  <h2>🙋‍♂️ Contributing</h2>
  <p>
    Contributions are welcome! Feel free to suggest improvements or open a pull request if you'd like to add MySQL integration, Arduino input, or enhance the GUI.
  </p>



  <h2>👨‍💻 Author</h2>
  <p>
    <strong>Akshat Yadav</strong><br/>
    <a href="https://github.com/your-username" target="_blank">GitHub</a> • 
    <a href="https://linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
  </p>

</body>
</html>
