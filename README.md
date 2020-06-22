# Wrangle-and-Analyze-Data
Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations

**UDACITY** | Data Analyst Nanodegree Program

---

### OVERVIEW

Goal of this project is to gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. The dataset that will be wrangled (and analyzed and visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

### DEPENDENCIES

The following libraries are required to run this project:

- Python
- NumPy
- pandas
- Matplotlib
- Seaborn

### PROJECT FILES

<ul>
  <li>wrangle_act.ipynb: code for gathering, assessing, cleaning, analyzing, and visualizing data</li>
  <li>wrangle_report.pdf or wrangle_report.html: documentation for data wrangling steps: gather, assess, and clean</li>
  <li>act_report.pdf or act_report.html: documentation of analysis and insights into final data</li>
  <li>twitter_archive_enhanced.csv: file as given</li>
  <li>image_predictions.tsv: file downloaded programmatically</li>
  <li>tweet-json.txt: file constructed via API</li>
  <li>twitter_archive_master.csv: combined and cleaned data</li>
</ul>

### DATASET

Data was gathered from multiple sources:

<ul>
  <li> The WeRateDogs Twitter archive: twitter_archive_enhanced.csv provided for this project</li>
  <li> The tweet image predictions: what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and will be downloaded programmatically.</li>
  <li> Each tweet's entire set of JSON data in a file called tweet_json.txt aquired using tweet IDs in the WeRateDogs Twitter archive</li>
</ul>


