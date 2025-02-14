# gibbs_minima
CHEME 545 midterm project

02/14 
Q1 - what all we're doing:
1. Exploring/Cleaning the data:
- Check data-types
- df.describe() - see distribution: data is skewed 
- Nan to 0 : fillna
- drop duplicates
2. Defining target and features
3. Pre-processing data for training:
  - dummy encoding of non-numerical features
  - robust scaling : because we didn't want to remove outliers 
  
