# Drug Discovery using Machine Learning and Data Analysis
## Part 1: Data Collection
1. Target protein search
2. chembl_webresource_client (Python library)
3. chEMBL Database
4. Bioactiviy data
5. Data pre-processing
    - Drop missing data
    - Drop duplicates
    - Label compounds according to bioactivity threshold
6. Curated Bioactivity data

## Part 2: Exploratory data analysis
1. Clean SMILES notation: output--> csv file
    - Remove small organic compounds
    - Remove salt
2. Calculate Lipinski's descriptors
3. Perform EDA
    - Box plot
    - Scatter plot
    - Statistical analysis

## Part 3: Descriptor calculation
1. Read in CSV file as a dataframe
2. Prepare input file to PADEL Descriptor
3. Calculate fingerprints using PADEL Descriptor

## Part 4: Model building
1. Read in CSV file as a Dataframe
2. Remove low variance features
3. Data splitting
4. Build a Regression Model
5. Make a scatter plot

## Part 5: Model comparison
1. Read in CSV file as a Dataframe
2. Remove low variance features
3. Build several Regression Models
4. Make a performance comparison plot

## Part 6: Deploy model
1. Input molecule
2. Code the web app
3. Save Model to file
4. Prediction
