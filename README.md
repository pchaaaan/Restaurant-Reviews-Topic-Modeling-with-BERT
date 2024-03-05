<h1>Topic Modeling on Arizona Restaurant Reviews with BERTopic</h1>

<p>This is an advanced NLP project where BERTopic, a state-of-the-art topic modeling technique, is utilized to analyze and extract meaningful topics from a dataset of Arizona restaurant reviews. The project aims to uncover the underlying themes within the reviews, providing insights into customer sentiments and preferences.</p>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Python</li>
  <li>pandas</li>
  <li>matplotlib</li>
  <li>seaborn</li>
  <li>BERTopic</li>
  <li>transformers</li>
</ul>

<h3>Dataset</h3>
<p>The dataset comprises restaurant reviews, each with a 'text' column for the review content. The analysis focuses on extracting topics that represent recurring themes across these reviews.</p>

<h2>Implementation Details</h2>

<h3>Data Visualization</h3>
<ul>
  <li>Distribution of review lengths is visualized to understand the dataset's nature.</li>
  <li>Temporal changes in topic frequencies and their distribution across different star ratings are analyzed.</li>
</ul>

<h3>Topic Modeling with BERTopic</h3>
<ul>
  <li>A BERTopic model is created, leveraging UMAP for dimensionality reduction and extracting diverse topics from the review texts.</li>
  <li>The model is further refined using zero-shot topic modeling to classify reviews into predefined categories like "Ambiance" and "Price."</li>
</ul>

<h3>Analysis and Visualization</h3>
<ul>
  <li>The most relevant words for each topic are visualized, and the hierarchical structure of topics is explored to understand their relationships.</li>
  <li>Topic frequencies over time and across different star ratings are plotted to reveal trends and patterns.</li>
</ul>

<h3>Insights</h3>
<p>The analysis provides a nuanced understanding of customer feedback, highlighting areas of excellence and concern within the restaurant industry in Arizona. Zero-shot topic modeling offers a focused lens on specific aspects of dining experiences, allowing for targeted analysis and interpretation.</p>

<h2>Results</h2>
<p>The project uncovers diverse topics, ranging from food quality and service experiences to ambiance and pricing, reflecting the multifaceted nature of restaurant reviews. Visualizations offer a compelling narrative of how these topics evolve over time and vary with customer satisfaction levels.</p>

<hr>
