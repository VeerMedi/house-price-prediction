
# House Price Prediction — University Project

This folder contains a single, self-contained Jupyter notebook that explores housing data and builds simple models to estimate house prices. It was created as a university project and is written so readers can follow the steps and learn how data and models come together.

**What the notebook does**
- **Overview:** Loads a dataset of home sales and walks through a clear, visual exploration of the data.
- **Explore:** Uses charts and plots to show how price relates to features like living area, basement size, number of bedrooms, floors, waterfront presence, and the location (latitude/longitude and zipcode).
- **Prepare:** Picks the columns to use for modeling and separates the house prices (the values we want to predict) from the rest of the data.
- **Model:** Tries a straightforward linear regression and a more advanced gradient boosting model to predict house prices, then compares how they perform.
- **Inspect:** Shows how model performance changes as the boosting model is trained and gives a short example of dimensionality reduction (PCA) to illustrate another way to look at the data.

**How it works (simple explanation)**
- The notebook first loads the data file `kc_house_data.csv` and shows a few examples and summary statistics so we understand what the dataset looks like.
- It then creates a set of visual plots to reveal patterns (for example, whether larger homes tend to cost more, or if homes by the waterfront are priced differently).
- After that, the notebook prepares the data for learning: it removes columns that just identify rows, and separates the price column so the models know what to predict.
- Two types of models are trained: a linear model (easy to understand) and a gradient-boosting model (a more powerful learner). Their predictions are compared to see which one estimates price better.

**Open and run (easy steps)**
- **Open the notebook:** Open `housesales.ipynb` with Jupyter or directly in VS Code (use the built-in notebook view).
- **Run the cells:** Use “Run All” to execute the notebook from top to bottom and watch each plot and result appear. No advanced setup is required beyond installing the listed packages.

**Files in this folder**
- `housesales.ipynb` — the project notebook you can open and run.
- `kc_house_data.csv` — the dataset used by the notebook.
- `requirements.txt` — list of Python packages used (install these to run the notebook).

**If you want to try it locally**
- Create and activate a Python virtual environment, then install dependencies with:

```
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Open `housesales.ipynb` and run the notebook. If you’d like, I can help make the notebook even more polished for submission (for example, adding short explanations next to each plot or packaging results into a printable report).

