### Employee Salary Classifier
Training classification models estimating the likelihood that an individual will achieve an annual income of $80,000 or more, utilizing a sophisticated analysis of multiple determinants. This comprehensive assessment incorporates work experience , Industry , job title , state and many other features to deliver a nuanced prediction of financial success.

### Dataset
The dataset contains 17 columns and around 28000 rows. It contains different features like work experience , industry , job title , state, education degree etc..

### Data Preprocessing
1. Used Fuzzy Wuzzy to match different combinations of the name USA as data was manually entered by different users. <br>
2. Clubbed different education degrees into 4 most common degree categories. Similarly, done for Gender and Race. <br>
3. Took top 10 Industries and replaced other industries with "Other" for convenience. <br>
4. Took top 500 Job titles while replaced other job titles with "Other". <br>
5. Scaled down the Bonus column using RobustScalar. <br>
6. Used Frequency encoding for State, Industry, Job title, Race due to high cardinality. <rb>
7. Used Label encoding for target variable. <br>
8. Used Ordinal encoding for Education degree, Work experience, Age. <br>
9. Used One Hot encoding for Gender. <br>
10. Removed outliers from our data. <br>

### Model Training
With this dataset, Random Forest exhibited the highest model accuracy, reaching 81%, surpassing Naive Bayes,Logistic Regression,KNN which hovered around 76%, with Decision Tree slightly ahead at 78%.

<h3 align="center"><b>Developed with :heart: by <a href="https://github.com/DEV270201">Devansh Shah</a> & <a href="https://github.com/smit1999">Smit Vora</a></b></h3>



