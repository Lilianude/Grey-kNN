Grey k Nearest Neighbor (GkNN) Imputation Technique.
    
	The codes were written using the grey k nearest neighbour algorithm for iterative missing value imputation.


   Description
	
	The imputation algorithm is based on an article that describes the imputation of missing data using the grey k Nearest Neighbours algorithm, which is based on the Grey relational analysis theory. The Grey k nearest neighbour approach replaces the traditional kNN imputation technique, which cannot handle the heterogeneity of datasets. GRA measures the absolute distance between reference and comparative projects using the grey relational coefficient (GRC) and grey relational grade (GRG). Grey relational analysis is a method for determining the grey relational degree and assessing the contribution measure of the system's underlying behaviour or the degree of influence between system elements. Shichao Zhang wrote the article on which this algorithm is based, Nearest neighbour selection for iteratively KNN imputation.


   Getting Started
   Dependencies

The following packages were used in the Jupyter notebook.
•Pandas
•Numpy
•Sklearn
•OS
•Seaborn


   Installing the package

•The codes for the project are attached in the folder
•Anaconda package should be downloaded if not on your system and installed, then the Jupyter notebook can be launched.


   Executing the code

•The iPython Notebooks consist of the practical execution of the Gray kNN imputation using python      3.8, numerical, categorical and heterogenous codes were written to take care of data of this nature. In places with path files do the following:     
•‘pathIncomplete’: Set the path file to your incomplete dataset folder
•‘complete_df’: Set the path file to the complete dataset excel file for the current name of the dataset being dealt with.
•‘imputed_df’: Set to a path file folder where you want the imputed files to be kept
•NRMS.csv: set to a folder where you want the NRMS file stored
•AE.csv: set to a folder where you want the AE file stored.


   Acknowledgements
   Inspiration, advice and code snippets:

•Stack overflow
•Towards Data Science
•Kushal Chotaliya
•Medium
•Leetcode