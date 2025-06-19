# Day 9 – Feature Engineering

## ✅ What I Practiced:
- Extracted titles (Mr, Mrs, Miss) from passenger names using regex
- Created new categorical columns: `AgeGroup` and `FareBand`
- Used `.apply()` to run a custom function on the Age column
- Binned continuous Fare values using `pd.qcut()` for analysis

## 💡 What I Learned:
- `.str.extract()` with regex can pull clean info from messy text like names
- `.apply()` lets me process every value in a column with custom logic
- `qcut()` is powerful for slicing numeric data into equal-sized groups
- Features like `Title` and `FareBand` make patterns more obvious (e.g., higher fare = higher survival)

## 🤔 Struggles:
- Regex for title extraction was tricky to read at first
- Understanding how `qcut()` chooses the bin edges took a bit of thinking
- Had to carefully debug column creation to avoid overwriting anything

## 🔥 Final Thought:
I’m seeing how feature engineering gives raw data more meaning.  
Each new column feels like turning on a light in a dark room — more of the picture becomes clear.
