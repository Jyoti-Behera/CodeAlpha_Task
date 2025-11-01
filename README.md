
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Iris Classification — Project Info</title>
  <style>
    :root{--bg:#f7fafc;--card:#ffffff;--accent:#2563eb;--muted:#6b7280}
    body{font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial;line-height:1.6;background:var(--bg);color:#111;padding:24px}
    .container{max-width:900px;margin:0 auto}
    .card{background:var(--card);border-radius:12px;padding:20px;margin-bottom:18px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    h1{font-size:1.6rem;margin:0 0 8px}
    h2{font-size:1.05rem;margin:0 0 12px;color:var(--accent)}
    p.lead{margin:0 0 14px;color:var(--muted)}
    ul{margin:8px 0 12px 18px}
    code{background:#f3f4f6;padding:2px 6px;border-radius:6px;font-family:monospace}
    .meta{display:flex;gap:12px;flex-wrap:wrap;margin-top:8px}
    .badge{background:#eef2ff;color:var(--accent);padding:6px 10px;border-radius:999px;font-weight:600}
    .section-title{display:flex;align-items:center;gap:10px}
    .small{font-size:0.9rem;color:var(--muted)}
    pre{background:#0f172a;color:#e6eef8;padding:12px;border-radius:8px;overflow:auto}
    .row{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    @media (max-width:700px){.row{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="section-title">
        <h1>Iris Classification — Project Summary</h1>
        <span class="badge">Machine Learning</span>
      </div>
      <p class="lead">Simple and clean HTML snippet containing Objective, Technologies Used, Steps Involved and Results. Drop this inside your project site or GitHub Pages.</p>
    </div>

    <!-- Objective -->
    <section class="card" id="objective">
      <h2>Objective</h2>
      <p class="small">A short statement describing the goal of the project.</p>
      <p>Build and evaluate a supervised machine learning model to classify iris flowers into three species (<em>Setosa</em>, <em>Versicolor</em>, <em>Virginica</em>) using the classic Iris dataset. The model should be able to predict species given four numeric features: sepal length, sepal width, petal length and petal width.</p>
    </section>

    <!-- Technologies -->
    <section class="card" id="technologies">
      <h2>Technologies Used</h2>
      <p class="small">List of libraries, tools and environment used for development.</p>
      <ul>
        <li><strong>Language:</strong> Python 3.x</li>
        <li><strong>Libraries:</strong> NumPy, Pandas, Matplotlib, Seaborn, scikit-learn</li>
        <li><strong>Notebook:</strong> Jupyter Notebook (.ipynb)</li>
        <li><strong>Version control:</strong> Git &amp; GitHub</li>
      </ul>
    </section>

    <!-- Steps Involved -->
    <section class="card" id="steps">
      <h2>Steps Involved</h2>
      <p class="small">High-level workflow used in the notebook.</p>
      <div class="row">
        <div>
          <h3 style="margin:0 0 8px;font-size:0.98rem">Data &amp; Exploration</h3>
          <ul>
            <li>Load the Iris dataset from CSV or sklearn.datasets</li>
            <li>Inspect data: head(), describe(), isnull checks</li>
            <li>Visualize distributions and pairplots</li>
          </ul>
        </div>
        <div>
          <h3 style="margin:0 0 8px;font-size:0.98rem">Modeling &amp; Evaluation</h3>
          <ul>
            <li>Split dataset into train and test sets (e.g., 80/20)</li>
            <li>Train models: Logistic Regression, KNN, Decision Tree, Random Forest</li>
            <li>Evaluate using accuracy, precision, recall, and confusion matrix</li>
            <li>Tune hyperparameters (GridSearchCV) and pick best model</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Results -->
    <section class="card" id="results">
      <h2>Results</h2>
      <p class="small">Summarize model performance and include snippets (replace with your actual results).</p>
      <ul>
        <li><strong>Best model:</strong> Random Forest Classifier</li>
        <li><strong>Accuracy (test):</strong> <code>0.96</code> <!-- replace with your value --></li>
        <li><strong>Confusion Matrix:</strong> Achieved high precision and recall for Setosa; minor confusion between Versicolor and Virginica.</li>
      </ul>

      <h3 style="margin-top:12px">Example Prediction</h3>
      <pre><code>Input:  [5.1, 3.5, 1.4, 0.2]
Prediction: Iris-setosa</code></pre>

      <p class="small">Tip: Replace the placeholder values above with actual numbers from your notebook.</p>
    </section>

    <div style="text-align:center;margin-top:18px;color:var(--muted);font-size:0.95rem">Made with ❤️ by Jyoti Behera — update names &amp; metrics before publishing.</div>
  </div>
</body>
</html>
