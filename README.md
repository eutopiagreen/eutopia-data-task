# eutopia-data-task

This is a standard programming task that we ask candidates interviewing to join our team to fulfill to test their
preparation level.

## INSTRUCTIONS

The file dataset.pickle is a list of companies (and the relevant web content on their websites) organized by web pages.
50% of the companies use AI (column AI = 1), the other 50% does not (column AI = 0).
Below the content in each column:

• crunchbase_ID: the company unique identifier;
• home_text, aboutus_text, overview_text, whatwedo_text, company_text, whoweare_text: the web text scraped from each company’s website page (home_text shows the landing page text, aboutus_text shows the text retrieved from the about us page and so on..);
• AI: represents if a company is using AI technologies in its activities, if yes then 1, else 0

The task consists of writing an algorithm that is able to detect if a company is employing AI in its activities using as input
the text found on its website (columns: home_text, aboutus_text, overview_text, whatwedo_text, company_text,
whoweare_text).
IMPORTANT: The model must score above 85% on the test sample. We strongly advice the candidate to avoid simple
approaches such us TF-IDF test vectorization and the simple models (e.g. Logistic regression) to predict. We are looking
for a candidate who think out of the box, we like organ solution not textbook ones.
Notes:

1. NLP and ML techniques are compulsory; the candidate can choose to employ any techniques within these domains, but she/he should be able to justify the choice.
2. The candidate must save every variable that takes more than 5 minutes to run (e.g.: datacleaning: if this procedure takes more than 5 minutes, the candidate must save the
cleansed database);
3. The code should be tidy and easy to read; please, insert detailed comments to explain what the code is doing;
4. The deadline is in one week from the moment the candidate acknowledged to have eceived the instruction and other relevant files.
5. The candidate should deliver a code written in Python (3.7 strongly suggested) along ith all the stored variable as explained in point 2. and a short document where
explaining the candidate’s choices (see point 1.) and how she/he approached the task.

Please, upload all the relevant documents to this public GitHub repo.
