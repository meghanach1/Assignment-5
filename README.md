# Assignment-5

MACHINE LEARNING ASSIGNMENT 5

Name: Meghana Chodagiri

Student ID: 700749050


GitHub link: https://github.com/meghanach1/Assignment-5

Video link: https://drive.google.com/file/d/1QO_OnPQzl0nF2ag-ltMcR-EhNgn89uoE/view?usp=share_link


Programming elements: 

    Clustering & Dimensionality reduction

1.	Principal Component Analysis:

        In the below code, the libraries were imported, and data is loaded from the given csv.
        After loading the csv data, pd_read file is used to read the .csv file and get the data as an output, .isnull() .any() function is used to get the       type of function, head() function is used to get the detailed table of the data.


    
a.	Apply PCA on CC dataset.

        In the below code, I used transform (), Data frame functions to get the principal components in a tabular column and the final Df to get the output. I have taken k as 3 and done fitting. After applying k means algorithm, the silhouette score has been improved.
 
b.	 Apply k-means algorithm on the PCA result and report your observation if the silhouette score has improved or not?

    In the below code I used Kmeans function to get the clusters and fix () to fix the data, iloc() function to get the location , predict() to predict the cluster for each data point and print the predictions made by the classifier. Silhouette to calculate the silhouette score. I have used accuracy_score to get the accuracy.
   
c.	 Perform Scaling+PCA+K-Means and report performance.

    In the below code I have used StandardScaler() function for scaling and iloc() function to get the location and after scaling, I have fit_transform the pca and created a new data frame for the scaled array .

   
2.	Use pd_speech_features.csv

    In the below code, the have loaded the data using pd_read_csv and read data using head() function.
  
a.	Perform Scaling and
b.	 Apply PCA (k=3)

      For performing scaling, I have used StandardScaler and then fit_transform the dataset.
 
c.	Use SVM to report performance.
  
    In the below code, I have imported SVC and get the svc classifier and fit the data into columns. Then I used prediction, accuracy score and calculate the silhouette score.
  
3.	Apply Linear Discriminant Analysis (LDA) on Iris.csv dataset to reduce dimensionality of data tok=2.

  
         In the below code, I have imported the lineardiscriminantanalysis and read function to read the given data. iloc () function is used to get the location. Standard scalar and label encoder to get the transformed data and print function to print the output.


4. Briefly identify the difference between PCA and LDA

        Both LDA and PCA rely on linear transformations and aim to maximize the variance in a lower dimension. PCA is an unsupervised learning algorithm while LDA is a supervised learning algorithm. This means that PCA finds directions of maximum variance regardless of class labels while LDA finds directions of maximum class separability.
        It reduces the features into a smaller subset of orthogonal variables, called principal components – linear combinations of the original variables. The first component captures the largest variability of the data, while the second captures the second largest, and so on.
        LDA finds the linear discriminants in order to maximize the variance between the different categories while minimizing the variance within the class.



