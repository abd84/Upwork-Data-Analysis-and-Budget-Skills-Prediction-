<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
  <h1>Upwork Project Data Analysis and Prediction Models</h1>

  <h2>Overview</h2>
  <p>This project involves a comprehensive analysis of Upwork project data using <strong>Power BI</strong> to uncover actionable trends and insights, with a focus on predicting key project attributes such as <strong>budget</strong>, <strong>required skills</strong>, and <strong>completion timelines</strong> based on historical data.</p>

  <h2>Objectives</h2>
  <ul>
    <li><strong>Data Analysis</strong>: Analyzed Upwork project data using Power BI to identify trends and generate actionable insights.</li>
    <li><strong>Prediction Models</strong>: Developed and compared four different machine learning models to predict project budgets, required skills, and completion timelines:
      <ul>
        <li>Recurrent Neural Networks (RNN)</li>
        <li>Artificial Neural Networks (ANN)</li>
        <li>Random Forest</li>
        <li>Decision Tree</li>
      </ul>
    </li>
    <li><strong>Optimization</strong>: Improved model accuracy through advanced optimization techniques, particularly focusing on the <strong>RNN</strong> model.</li>
  </ul>

  <h2>Key Results</h2>
  <ul>
    <li><strong>Best Performing Model</strong>: <strong>RNN</strong> was identified as the top-performing model with an initial accuracy of <strong>76%</strong>, which was optimized to <strong>87%</strong> through advanced optimization techniques.</li>
    <li><strong>Neural Networks</strong>: Utilized neural networks to model complex relationships in the project data, significantly outperforming traditional machine learning models like Decision Tree and Random Forest.</li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>Power BI</strong> for data visualization and analysis</li>
    <li><strong>Python</strong> for model development and optimization</li>
    <li><strong>Libraries</strong>: TensorFlow, Keras, scikit-learn, pandas</li>
  </ul>

  <h2>Model Evaluation</h2>
  <ul>
    <li><strong>RNN</strong>: Best suited for sequential data, capturing the dependencies and trends in project data.</li>
    <li><strong>ANN</strong>: Performed well for general-purpose prediction tasks.</li>
    <li><strong>Random Forest</strong>: Useful for interpreting feature importance but less effective for time-based predictions.</li>
    <li><strong>Decision Tree</strong>: Good for simple problems but lacked precision in this case.</li>
  </ul>

  <h2>Conclusion</h2>
  <p>Leveraging neural networks for complex forecasting tasks like project budgeting and timeline predictions has proven effective, providing improved accuracy compared to traditional machine learning methods.</p>

  <h2>Installation</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/yourusername/upwork-project-analysis.git</code></pre>
    </li>
    <li>Install necessary Python dependencies:
      <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Open the <strong>Power BI</strong> dashboard for interactive data analysis.</li>
    <li>Run the Python scripts to train the models and optimize their performance.</li>
  </ol>

  <h2>Future Improvements</h2>
  <ul>
    <li>Incorporate additional project features (e.g., client ratings, freelancer expertise) to further improve model accuracy.</li>
    <li>Experiment with more advanced deep learning architectures like <strong>LSTMs</strong> or <strong>Transformer models</strong> for better time-series prediction.</li>
  </ul>

</body>
</html>
