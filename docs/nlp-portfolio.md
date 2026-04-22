Brenda Fuemmeler
P7: Portfolio Presentation
Module 6 Repo:
🔗 https://github.com/bfuemmeler/nlp-06-nlp-pipeline
________________________________________
1. NLP Techniques Implemented
This project applies a range of natural language processing (NLP) techniques to transform unstructured text into meaningful insights.
•	Tokenization:
Implemented both word-level and sentence-level tokenization to break raw text into analyzable units.
•	Text Cleaning and Normalization:
Removed punctuation, normalized whitespace, and converted text to lowercase to ensure consistency across analysis steps.
•	Frequency Analysis:
Generated unigram and n-gram frequency distributions to identify dominant terms and recurring phrases.
•	Web Scraping and Content Extraction:
Used HTML parsing to extract structured text and metadata from web pages.
•	API-Based Text Processing:
Processed JSON responses from APIs, demonstrating the ability to work with nested and semi-structured data formats.
•	Sentiment Analysis:
Applied sentiment scoring (e.g., using spaCy + TextBlob extensions) to quantify tone and subjectivity in text.
These techniques demonstrate how raw text can be systematically prepared and analyzed using repeatable methods.
________________________________________
2. Systems and Data Sources
This project integrates multiple data sources and formats:
•	Web Pages (HTML):
Extracted content using BeautifulSoup, handling inconsistent tag structures and embedded metadata.
•	APIs (JSON):
Parsed nested JSON objects and normalized them into tabular structures for analysis.
•	Text Data:
Worked with raw and semi-structured text requiring cleaning before analysis.
Handling Data Variability
Different formats required different strategies:
•	HTML required structural validation (checking for expected tags)
•	JSON required key validation and normalization
•	Text required cleaning and filtering
3. Pipeline Structure (EVTL)
The project follows a structured EVTL (Extract, Validate, Transform, Load) pipeline:
•	Extract:
Collected data from web sources and APIs, saving raw inputs for traceability.
•	Validate:
Verified structure and required fields to prevent errors throughout.
•	Transform:
Applied NLP techniques including tokenization, normalization, and feature extraction (frequency, sentiment).
•	Load:
Output results to structured formats such as CSV files and summary reports for further analysis or visualization.
4. Signals and Analysis Methods
The analysis focused on extracting meaningful signals from text:
•	Word Frequency:
Identified the most common terms to highlight dominant topics.
•	N-gram Analysis:
Captured multi-word patterns to provide context beyond single-word frequency.
•	Keyword Extraction:
Isolated high-value terms relevant to the subject matter.
•	Sentiment and Subjectivity:
Measured tone to distinguish between objective and opinion-based content.
•	Pattern Recognition:
Observed repeated structures and phrasing across documents to identify themes.
These methods move beyond simple counts to provide deeper insight into text meaning and structure.
________________________________________
5. Insights
The analysis revealed several key patterns:
•	Data cleaning significantly impacts results:
Small preprocessing changes (e.g., removing stop words or punctuation) meaningfully altered frequency distributions and improved signal clarity.
•	Context matters:
N-gram analysis provided more meaningful insights than single-word frequency alone by preserving phrase-level meaning.
•	Structure influences interpretation:
Differences between HTML and JSON sources affected how easily meaningful information could be extracted.
•	Sentiment added interpretive value:
Sentiment scoring helped distinguish between informational and opinion-driven content.
Overall, the results demonstrate how structured pipelines can turn raw, messy text into actionable insights.
________________________________________
6. Representative Work
NLP-01-GETTING-STARTED
https://github.com/bfuemmeler/nlp-01-getting-started

Example of work: Word Frequencies and created Word Cloud

<Figure size 1200x600 with 1 Axes>

NLP-02-TEXT-PREPROCESSING
https://github.com/bfuemmeler/nlp-02-text-preprocessing
Example of work: Analyze Bigrams

Top 10 Bigrams:
special effects: 1433
could been: 1383
would been: 1239
better than: 1103
there some: 1047
when they: 1038
each other: 936
know what: 913
waste time: 888
your time: 849

NLP-03-TEXT-EXPLORATION
https://github.com/bfuemmeler/nlp-03-text-exploration
Example of work: Corpus exploration

FUEMMELER GENERAL OBSERVATIONS:
- Tokens cluster by category (patient, doctor, hospital).
- Words that appear in similar contexts behave similarly.
- Co-occurrence reveals contextual relationships between words.
- Bigrams capture local structure beyond single tokens.
- Patterns emerge before any machine learning is applied.

FUEMMELER SPECIFIC OBSERVATIONS:
- commom stop words should be removed (the, after, new)
- could be used for analyzing around negative feedback words (delay, shortage, patient safety)

NLP-04-API-TEXT-DATA
https://github.com/bfuemmeler/nlp-04-api-text-data
Example of work: Used new API URL to extract, validate & transform data

NLP-05-WEB-DOCUMENTS
https://github.com/bfuemmeler/nlp-05-web-documents
Example of work: Changed target URL to extract, validate & transform data

NLP-06-NLP-PIPELINE
https://github.com/bfuemmeler/nlp-06-nlp-pipeline
Example of work: Add analyze to steps after validate, transform


1. Skills
This project demonstrates the following technical capabilities:
•	Python Data Processing:
Writing modular scripts to extract, clean, and analyze data using libraries like pandas and spaCy.
•	Text Data Handling:
Processing unstructured and semi-structured text from multiple sources.
•	Data Cleaning and Normalization:
Transforming messy inputs into consistent, analysis-ready formats.
•	Pipeline Design (EVTL):
Building repeatable, structured workflows for data processing.
•	Working with APIs and Web Data:
Parsing JSON and HTML using appropriate tools and validation techniques.
•	Analytical Thinking:
Interpreting patterns, trends, and signals from processed data.
•	Professional Communication:
Presenting findings clearly using Markdown, structured documentation, and visual outputs.
