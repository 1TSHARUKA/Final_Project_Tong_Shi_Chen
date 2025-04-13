This repository contains the information of final project for Data Science I: Foundations.

<h1 align="center"> Exploring Pollution Levels and Media Trends Between States: </h1>
<h3 align="center"> A Study of New York Times News Reports </h3>  

## Abstract:

The role of news media in shaping public opinion has been a well-discussed topic by scholars. With the New York Times API and US news ranking on pollution, our research found no significant relationship between higher pollutant levels and higher media coverage in terms of the absolute number of news reports they receive and the mean sentiment level of each article. This means states with higher pollutants deserve more media attention in raising awareness of the potential health risks. 

Our findings indicate that there is no clear correlation between pollution severity and the volume of media attention. In fact, states with better environmental performance—such as Vermont or Oregon—sometimes receive disproportionately harsher media tone. Additionally, topic similarity analysis across states revealed the prominence of recurring national themes, such as “climate change” and “carbon dioxide,” suggesting that coverage often reflects broader political and ideological framing rather than local environmental conditions.

These results raise critical questions about the representativeness of media narratives in public discourse and highlight opportunities for more targeted environmental communication strategies.

<!-- PREREQUISITES -->
<h2 id="prerequisites">Prerequisites</h2>

This project is written in the Python programming language and requires the following packages:<br>
<code>pandas</code>, <code>numpy</code>, <code>requests</code>, <code>dotenv</code>, <code>os</code>, <code>time</code>, <code>nltk</code>, <code>sklearn</code>, <code>matplotlib</code>, <code>transformers</code>

These can be installed using <code>pip install</code> or loaded via your preferred Python environment manager (e.g., conda, poetry). Additional dependencies such as downloading NLTK resources may be required for text preprocessing and model use.

Before running the scripts, ensure that necessary NLTK resources are downloaded using:

<pre><code>import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
</code></pre>


<!-- Repository Structure -->
<h2 id="project-files">Repository Structure</h2>

<p>
This repository contains datasets, scripts, and output files for our final project. 
Our analysis includes custom scraping, sentiment analysis, textual similarity testing, and visualization.
</p>

---

<h3>Python Code</h3>

<ul>
  <li><code>Python_web_scrapping_sentiment.ipynb</code> – Scrapes New York Times articles and computes the mean sentiment score for each state</li>
  <li><code>Python_geo_plot1.ipynb</code> – Creates a geo plot for US News pollution rankings</li>
  <li><code>Python_geo_plot2_3.ipynb</code> – Generates geo plots for the number of articles and average sentiment by state</li>
  <li><code>Python_bi_gram_5states.ipynb</code> – Extracts and visualizes bigrams from the five states with the most media coverage</li>
  <li><code>Python_bigram_similarity.ipynb</code> – Performs cosine similarity tests based on bigrams between selected states</li>
  <li><code>Python_simi_2.ipynb</code> – Further explores bigram similarity among grouped states</li>
</ul>

---

<h3>Scripts / Visual Outputs</h3>

<ul>
  <li><code>rank_cut.JPG</code> – Geo plot for US News pollution ranking by state</li>
  <li><code>number_cut.JPG</code> – Geo plot showing total number of articles collected by state</li>
  <li><code>senti_cut.JPG</code> – Geo plot for average sentiment score by state</li>
  <li><code>Sample_states_combined_barplot.PNG</code> – Combined top bigrams for selected states showing national trends</li>
  <li><code>10states.PNG</code> – Cosine similarity visualization across selected states (Figure 4)</li>
  <li><code>all_simi_filter.JPG</code> – Cosine similarity matrix for all 31 states (filtered by &gt;0.4)</li>
  <li><code>inlfation_plot.PNG</code> – Sentiment “inflation” index comparing NYT sentiment to US News pollution ranking</li>
  <li><code>lowest3_barplot.PNG</code> – Top bigrams for states with the lowest NYT sentiment inflation</li>
  <li><code>high3_barplot.PNG</code> – Top bigrams for states with the highest NYT sentiment inflation</li>
  <li><code>lowest6.JPG</code> – Cosine similarity matrix for six states with lowest sentiment inflation (filtered by &gt;0.35)</li>
  <li><code>top_bigrams_Alaska.PNG</code> – Top 20 bigrams extracted from Alaska articles</li>
  <li><code>combined_bigrams.PNG</code> – Combined bigram plot for New Jersey and Connecticut</li>
</ul>

---

<h3>Data</h3>

<ul>
  <li><code>full_data_updated.csv</code> – Complete dataset of all articles with available metadata for 31 states</li>
  <li><code>senti_clean.csv</code> – Processed file including mean sentiment scores and article counts by state</li>
  <li><code>Usnews_ranking.csv</code> – State-level US News pollution rankings used as a benchmark</li>
  <li><code>CT_data.csv</code> – Raw dataset of all articles pulled for Connecticut</li>
  <li><code>NJ_data.csv</code> – Raw dataset of all articles pulled for New Jersey</li>
</ul>



<!-- CONTRIBUTORS -->
<h2 id="contributors">Contributors</h2>

<p>
This project was completed as part of the final project for 
the course <strong>PPOL 5203 — Data Science I: Foundations</strong> (Fall 2023) at 
<a href="https://mccourt.georgetown.edu/">Georgetown University, McCourt School of Public Policy</a>.
</p>

We gratefully acknowledge the guidance and support of Professor <strong>Tiago Ventura</strong> throughout the project.

<ul>
  <li><strong>Wendy Shi</strong> - <a href="mailto:ys1012@georgetown.edu">ys1012@georgetown.edu</a></li>
  <li><strong>Irene Chen</strong> - <a href="mailto:yc1171@georgetown.edu">yc1171@georgetown.edu</a></li>
  <li><strong>Tian Tong</strong> - <a href="mailto:yt583@georgetown.edu">yt583@georgetown.edu</a></li>
</ul>

<h2 id="license">License</h2>

<p>
This project is shared for academic purposes. Please cite appropriately if using or extending the work. Data sources belong to the respective owners (e.g., New York Times, US News).
</p>


