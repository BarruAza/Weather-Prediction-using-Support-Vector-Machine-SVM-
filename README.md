<h1>🌦️ Weather Prediction using Support Vector Machine (SVM)</h1>

<h2>📌 Project Overview</h2>
<p>
  This project is a final assignment for the <strong>Intelligent Systems (Sistem Cerdas)</strong> course at 
  <strong>Universitas Brawijaya</strong>. It focuses on building a 
  <strong>weather classification system</strong> using the 
  <strong>Support Vector Machine (SVM)</strong> algorithm, based on historical daily weather data from Malang (2010–2024).
</p>
<p>
  The system can classify weather conditions into three categories:
</p>
<ul>
  <li>🌞 Clear (Tidak Hujan)</li>
  <li>🌧️ Drizzle (Gerimis)</li>
  <li>⛈️ Heavy Rain (Hujan Lebat)</li>
</ul>

<hr />

<h2>🎯 Objectives</h2>
<ul>
  <li>Classify daily weather conditions using <strong>SVM</strong>.</li>
  <li>Evaluate the accuracy of SVM in distinguishing between three weather classes.</li>
  <li>Identify the most influential weather features in classification.</li>
</ul>

<hr />

<h2>📊 Dataset</h2>
<ul>
  <li><strong>Source:</strong> Daily historical weather data from Malang (2010–2024)</li>
  <li><strong>Format:</strong> CSV</li>
  <li><strong>Features:</strong>
    <ul>
      <li><code>temperature_2m_min</code> (°C)</li>
      <li><code>temperature_2m_max</code> (°C)</li>
      <li><code>temperature_2m_mean</code> (°C)</li>
      <li><code>precipitation_sum</code> (mm)</li>
      <li><code>precipitation_hours</code> (hours)</li>
    </ul>
  </li>
  <li><strong>Target:</strong> Weather condition (<code>weather_code</code>) mapped into 3 classes</li>
</ul>

<hr />

<h2>🛠️ Tools & Libraries</h2>
<ul>
  <li><strong>Python</strong> (Google Colab)</li>
  <li>Libraries:
    <ul>
      <li><code>pandas</code>, <code>numpy</code></li>
      <li><code>matplotlib</code>, <code>seaborn</code></li>
      <li><code>scikit-learn</code> (SVM, preprocessing, evaluation)</li>
      <li><code>PCA</code> for dimensionality reduction</li>
    </ul>
  </li>
</ul>

<hr />

<h2>⚙️ Methodology</h2>
<ol>
  <li><strong>Data Preparation:</strong> Cleaning, normalization (MinMaxScaler), and feature selection.</li>
  <li><strong>Modeling:</strong> Training SVM with RBF kernel for non-linear classification.</li>
  <li><strong>Evaluation:</strong> Accuracy, Cross-validation, Confusion Matrix, Classification Report.</li>
</ol>

<hr />

<h2>📈 Results</h2>
<ul>
  <li>Training Accuracy: <strong>92.55%</strong></li>
  <li>Testing Accuracy: <strong>92.44%</strong></li>
  <li>Cross-validation Accuracy: <strong>92.02% ± 0.91%</strong></li>
  <li>Stable performance across subsets, with minor misclassifications between <em>Drizzle</em> and <em>Heavy Rain</em>.</li>
</ul>

<hr />

<h2>🚀 How to Run</h2>
<ol>
  <li>Clone this repository:</li>
</ol>
<pre><code>git clone https://github.com/yourusername/SISCER-Weather-Prediction.git
cd SISCER-Weather-Prediction
</code></pre>
<ol start="2">
  <li>Open the Jupyter Notebook / Google Colab file.</li>
  <li>Upload dataset (<code>daily_data_combined_2010_to_present_Malang.csv</code>).</li>
  <li>Run all cells to train and test the SVM model.</li>
</ol>

<hr />

<h2>👥 Team Members</h2>
<ul>
  <li>Barru Wira Yasa (235150301111021)</li>
  <li>Evan Rayhandra Gerard (235150307111034)</li>
  <li>Muhammad Radhi Rasyidi Rafli (235150307111041)</li>
  <li>Timothy Bertu Pasaribu (235150301111027)</li>
</ul>

<hr />

<h2>📚 References</h2>
<ul>
  <li>Pratama et al. (2022), JIPI</li>
  <li>Rifqi &amp; Aldisa (2023), JOSYC</li>
  <li>Oemarki et al. (2021), SENAMIKA</li>
  <li>Santi et al. (2023), UNJ Proceedings</li>
  <li><a href="https://www.kaggle.com" target="_blank" rel="noopener">Kaggle Weather Dataset</a></li>
</ul>

<hr />
