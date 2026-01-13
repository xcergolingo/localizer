# localizer instrunction to run

1. Install packages
Python 3.10+
pip install jupyter openai

2.  Open the notebook
From the repo root run jupyter notebook (or jupyter lab) and open check_data_no_api_key.ipynb

3. Set OpenAI key
Replace the placeholder api_key in the notebook (both places that set openai.api_key = "api_key" / api_key = "api_key") with the actual key

4. Point to the input files
Make sure the files referenced by the notebook (e.g. Localizable 7.xcstrings, Localizable 7 updated.json) are in the notebook working directory or update the file paths in the cells

5. Run cells top → bottom
Use “Run All” (or run cells in order)
