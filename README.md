# Web Scraping for Events in Raleigh

## Project Description

This project was completed as a final project for DSC 405 at North Carolina State University. It was developed collaboratively with two other group members to demonstrate proficiency in web scraping techniques and the application of Python libraries to solve real-world problems.

#### **Background**
Raleigh, NC has seen a significant increase in events, festivals, and community gatherings, contributing to its vibrant cultural and social scene. However, discovering these events can be a challenge due to fragmented information spread across multiple websites.

#### **Problem Statement**
Finding local events in Raleigh is inefficient and time-consuming due to the scattered nature of event information across various platforms.

#### **Proposed Solution**
This project provides a data-science-driven solution to simplify event discovery. By scraping local event websites and consolidating the results into a single, user-friendly dataset, users can easily find and explore events in one centralized location.

#### **Ethical Considerations**
- **Attribution**: All scraped data will include proper credit to the original sources.
- **Responsible Scraping**: We employ techniques to minimize disruption to the functionality and performance of the websites we scrape.

---

### Scraped Data Sources
We collected event data (title, date, time, and ticket link) from the following websites:
1. [Goodnights Comedy Club](https://www.goodnightscomedy.com/)
2. [Lenovo Center](https://www.lenovocenter.com/events)
3. [Coastal Credit Union Music Park](https://www.coastalcreditunionmusicpark.com/shows)

---

### Python Libraries Used
The following Python packages were utilized:
- **`requests`**: For fetching the HTML content of web pages.
- **`BeautifulSoup4`**: For parsing and extracting data from HTML.
- **`pandas`**: For structuring and manipulating the data.
- **`time`**: For adding delays between scraping requests to prevent server overload.

---

### Final Dataset Metadata
- **Output File**: `data/sample_output.csv`
- **Columns**:
  - `Title`: Event name.
  - `Date`: Date of the event.
  - `Time`: Time of the event.
  - `Ticket Link`: URL for purchasing ticket(s).

**Process**: Data from the three sources were scraped, cleaned, and concatenated into a single DataFrame before being saved as a CSV file.

---

### Possible Applications
1. **Tourism Platforms**: Integrate into a platform for locals and tourists to explore Raleigh’s events.
2. **Community Promotion**: Share the data with local tourism boards or community organizations to enhance event visibility.
3. **Research**: Use the dataset for academic or professional studies on cultural trends and community engagement in Raleigh.

---

### How to Run This Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/webscraping-events-raleigh.git
2.	**Install Dependencies**:
Ensure you have Python installed, then run:
    ```bash
    pip install -r requirements.txt
3.	Run the Notebook:
Open scraping_demo.ipynb in Jupyter Notebook or your preferred environment and run the cells.

5.	Output:
The sample_output.csv file will be generated under the `data/` directory.

---
## Acknowledgments

This project acknowledges and credits the websites from which data was collected:
- Goodnights Comedy Club
- Lenovo Center
- Coastal Credit Union Music Park
