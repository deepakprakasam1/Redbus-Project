**Redbus Data Scraping and Filtering with Streamlit Application:**

This project involves extracting, transforming, and loading bus details from the Redbus website, followed by creating a user interface for data visualization. Below are the process details.

**Data Extraction or Data Collection - Web Scraping using Selenium:**
  1. Scraped data from the Redbus website.
  
  2. Sourced 10 State Transport bus route information which includes public & private buses.
  
  3. Sourced information for all available pages and routes.
  
  4. Collected Bus route Name, Bus name, Bus Type(Sleeper/Seater),  Departing Time, Duration, Reaching Time, Star-rating, Price, Seat availability.

**Transformation - Data Cleaning with Pandas:**

  1. Using pandas all data has been cleaned and loaded in a DataFrame.
    
  2. Merged all state transport DataFrames into a single DataFrame.
    
  3. Updated dtypes for the respective columns.

**Loading - Database Management with Postgres:**

  1. Created a Postgres database using Python.
  
  2. Created a table and pushed the DataFrame into Postgres database.

**Interactive Application – Using Streamlit:**

  1. Developed an interactive Stream lit application to view the collected data.
  
  2. Connect to Postgres database and pull data.
  
  3. Filters are used to allow users to select buses based on their criteria (eg: rating, seat availability & price)
