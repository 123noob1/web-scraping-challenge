# web-scraping-challenge
For this challenge, use <code>Beautiful Soup</code> and <code>Jupyter Notebook</code> to scrape and analyze information from <a href="https://static.bc-edx.com/data/web/mars_news/index.html">Mars news site</a> and <a href="https://static.bc-edx.com/data/web/mars_facts/temperature.html">Mars Temperature Data Site</a>. The objectives/deliverables for this challenge are:
1) Scrape titles and preview text from Mars news articles.
   - Use Beautiful Soup object to extract text elements from the website
   - Extract the titles and preview text as a <code>dictionary</code> then into a <code>list</code>
   - (Optional) Store the list as a <code>JSON</code> file
2) Scrape and analyze Mars weather data, which exists in a table.
   - Use Beautiful Soup object to extract the table elements from the Mars Temperature Data Site
   - Assign the scraped data into a <code>DataFrame</code>
   - Examine the data types and adjust accordingly (ie: date >>> <code>datetime</code>, numbers >>> <code>int</code> or <code>float</code>)
   - Perform analysis of the dataset and create charts
   - Export the DF into a <code>CSV</code> file
## Folder Structure
- <code>codebase</code> stores the working Jupyter Notebook files for each deliverable
- <code>outputs</code> stores the output results (charts and dataset files)
