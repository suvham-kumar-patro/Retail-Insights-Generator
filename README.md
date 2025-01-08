# Retail-Insights-Generator


## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/suvham-kumar-patro/Retail-Insights-Generator.git
```

2.Navigate to the project directory:

```bash
  cd retail-insights-generator
```

3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```

4.Acquire an api key through makersuite.google.com and put it in .env file

```bash
  GOOGLE_API_KEY="your_api_key_here"
```

5. For database setup, run database/db_creation_global_tshirts_db.sqlg in your MySQL workbench

## Usage

1. Run the Streamlit app by executing:

```bash
streamlit run main.py
```

2.The web app will open in your browser where you can ask questions

## Sample Questions

- How many total t shirts are left in total in stock?
- How many t-shirts do we have left for Nike in XS size and white color?
- How much is the total price of the inventory for all S-size t-shirts?
- How much sales amount will be generated if we sell all small size adidas shirts today after discounts?

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- few_shots.py: Contains few shot prompts
- .env: Configuration file for storing your Google API key.
