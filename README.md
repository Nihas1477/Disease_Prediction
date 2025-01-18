<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Disease Prediction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            color: #333;
        }
        h1, h2, h3 {
            color: #0056b3;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow-x: auto;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <h1>Disease Prediction</h1>
    <p>A machine learning-based project to predict diseases based on input symptoms. This project leverages data-driven insights to assist in preliminary disease diagnosis, helping users understand potential health issues quickly.</p>

    <h2>Features</h2>
    <ul>
        <li>Input symptoms and receive predictions of possible diseases.</li>
        <li>Utilizes machine learning models for accurate predictions.</li>
        <li>Interactive user interface for ease of use.</li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>Pandas and NumPy for data manipulation</li>
        <li>Scikit-learn for building machine learning models</li>
        <li>Flask for the web framework</li>
        <li>HTML and CSS for front-end</li>
    </ul>

    <h2>How to Run the Project</h2>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/Nihas1477/Disease_Prediction.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd Disease_Prediction</code></pre>
        <li>Install the required dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Run the Flask application:</li>
        <pre><code>python app.py</code></pre>
        <li>Open your web browser and visit:</li>
        <pre><code>http://127.0.0.1:5000/</code></pre>
    </ol>

    <h2>Dataset</h2>
    <p>The dataset used for training the model contains various symptoms mapped to their respective diseases. This dataset is processed and used to train machine learning models for predictions.</p>

    <h2>Project Structure</h2>
    <ul>
        <li><code>app.py</code>: Main Flask application file.</li>
        <li><code>templates/</code>: Contains HTML templates for the user interface.</li>
        <li><code>static/</code>: Contains static files like CSS and JavaScript.</li>
        <li><code>model/</code>: Trained machine learning model files.</li>
        <li><code>data/</code>: Dataset used for training and testing.</li>
    </ul>

    <h2>Contributions</h2>
    <p>Contributions are welcome! Feel free to fork this repository and submit pull requests.</p>

    <h2>License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>. You can view the license <a href="https://github.com/Nihas1477/Disease_Prediction/blob/main/LICENSE">here</a>.</p>

    <h2>Contact</h2>
    <p>If you have any questions or feedback, feel free to reach out:</p>
    <ul>
        <li>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></li>
        <li>GitHub: <a href="https://github.com/Nihas1477">Nihas1477</a></li>
    </ul>
</body>
</html>
