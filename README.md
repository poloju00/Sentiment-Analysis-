# 1. Create README.md with basic content
echo "# Sentiment Analysis Project

This repository contains the code and data for a sentiment analysis project using BERT.

## Files

- sentiment_analysis_.py - Python script for training and evaluating the model
- test.csv - Dataset used for training and testing

## How to Run

1. Install requirements:
   pip install -r requirements.txt
2. Run the script:
   python sentiment_analysis_.py

## License

Add your license info here.
" > README.md

# 2. Add files to git
git add README.md sentiment_analysis_.py test.csv

# 3. Commit changes
git commit -m "Add README, Python script, and dataset"

# 4. Push to GitHub
git push origin main
