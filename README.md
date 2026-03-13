# Nigeria House Price Prediction – My Second Project

**Goal**: Predict house prices in Nigeria and identify key factors (bedrooms, location, property type, etc.) driving real estate values, with a focus on major cities like Lagos and Abuja.

**Dataset**: Nigeria Houses and Prices (Kaggle) – real estate listings across states including bedrooms, bathrooms, title, town, state, and price.

**Tools Used**:
- Python, pandas (data handling)
- Matplotlib & Seaborn (visualization)
- Google Colab

**What I Did**:
1. Loaded and cleaned the data (handled missing values, types, outliers)
2. Explored patterns with 5 EDA plots (bedrooms, bathrooms, title, state, price distribution on log scale)
3. Provided business insights and recommendations under each plot

**Key Insights** (from EDA):
- Location (Lagos/Abuja) is the strongest price driver
- More bedrooms/bathrooms → higher prices
- Detached/duplex properties command premium
- Prices are right-skewed (mid-range dominates, luxury tail)

**Next Steps**:
- Build a regression model to predict price and quantify feature importance
- Deploy as interactive app (Streamlit)

View the full notebook: [Nigeria_House_Price_Prediction_My_Second_Project.ipynb](link-to-your-ipynb-file)

