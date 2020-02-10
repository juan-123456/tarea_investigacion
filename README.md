# tarea_investigacion


+ Big Data: is the storage or data set whose volume, speed, processing are much larger than a database.
***

+ The importance of the data: Your data is important because if someone gets your data. You can impersonate your identity or even get your bank account and grab the money. Now that your data is already becoming digital, they have become much more important.
***

+ Difference between private and open data: Virtually open data is easily found while private data is not.
***

+ Difference between structured and unstructured data: Structured data is data that is easy to search while unstructured data is difficult to search as well as multimedia files.
***

+ Difference between stored and moving data: The stored data are structured and generate information and the moving data are the ones that are circulating in the network.
***

+ Data analysis: It is responsible for examining the data in order to draw a conclusion about the information.
***

+ Impact of data analytics: the impact it has is that companies can now earn income through data analysis
***

+ Different types of data analytics
-Descriptive: In a business it allows you to see the main metrics within the business. For example, gains and losses in the month, sales made, etc.
-Diagnostic: You must have the necessary tools so that the analyst can deepen the data and isolate the root cause of a problem.
-Predictive: Predictive analysis has to do with prediction. Either the probability of an event occurring in the future, the forecast of a quantifiable amount or the estimation of a point in time at which something could happen - all of them are done through predictive models.
-Prescriptive: The prescriptive model uses an understanding of what has happened, why it has happened and a variety of "what could happen" analysis to help the user determine the best course of action to take. The prescriptive analysis is usually not only with an individual action, but in fact it is a series of other actions.
***


+ Docker: The idea behind Docker is to create lightweight and portable containers for software applications that can be used on any machine with Docker installed, thus also facilitating the deployment or execution of the software.
***

+ MapReduce: it is a framework that provides a parallel and distributed data processing system and is aimed at solving problems with large data sets, so it uses the HDFS distributed file system.
***

+ Hoodoop: is a set of open source programs and procedures that anyone can use as the “backbone” of their Big Data operations.
***

+ Apache Spark: The idea is that we have n machines, for example ten machines, and each of those instances will have a version of Apache Spark installed. In this way, when we have to process a large amount of data, for example a very large file, we can divide it into ten parts, and each machine will handle a tenth of the file, and in the end we will join it.
***

+ Lamba and Kappa: Its objective was to have a robust fault-tolerant system, both human and hardware, that was linearly scalable and that allowed writing and reading with low latency, while kappa points to "weak" Lambda Architecture and how to solve them through an evolution Your proposal is to eliminate the batch layer leaving only the streaming layer.
***

> Commands

+ Git init: Create a new repertoire
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git init
Reinitialized existing Git repository in C:/Users/Usuario/Desktop/Prueba/.git/
}
```
***
+ Git status: Shows the list of the files, along with the files that are about to be added
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ nano bigdata.txt

Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bigdata.txt

nothing added to commit but untracked files present (use "git add" to track)
}
```
***

+ Git add: This command can be used to add files
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git add bigdata.txt
warning: LF will be replaced by CRLF in bigdata.txt.
The file will have its original line endings in your working directory
}

```
***

+ Git commit: Used to change the header
```javascript
Usuario@AERO MINGW64 ~/Desktop (master)
$ git commit --amend
[master 2bbd870] Prueba123
 Date: Fri Jan 31 13:03:20 2020 -0600
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
}
```
***
+ Git reset: Remove commits.
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git reset index.html
Unstaged changes after reset:
M       index.html

Usuario@AERO MINGW64 ~/Desktop/Hola (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

}
```
***

+ Git log: Shows a list of commits in a branch along with all the details
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git log
commit b77348c433f7a5fae9e5cdd591e22870544f4549 (HEAD -> master)
Author: Andres Ramirez <aero.1715@hotmail.com>
Date:   Fri Jan 30 21:39:05 2020 -0600

    First project

}
```
***
+ Git rm: It is used to remove files from the index and the directory you are working on
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git rm bigdata.txt
rm 'bigdata.txt'
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    bigdata.txt

}
```
***
+ Git mv: Used to move a file
```javascript
Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git mv Pagina1.html index.html

Usuario@AERO MINGW64 ~/Desktop/Prueba (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    bigdata.txt
        renamed:    Pagina1.html -> index.html
}
```
***
+ Git commit --amend: We can modify the most recent confirmation and even combine changes.
```javascript
Usuario@AERO MINGW64 ~/Desktop (master)
$ git commit --amend
[master 2bbd870] Prueba123
 Date: Fri Jan 31 13:03:20 2020 -0600
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
}
```
***
# Second partial :books:

+ Data life cycle in BIG DATA: Given the characteristics of Big Data: volume, speed and variety; They require a different type of collection and analysis than any other type of data.
The Big Data analysis presents a great challenge, not only for the management of a large amount of data but also for the need to know the life cycle of the data and establish a base based on the nature of the Big Data.
  
  - The phases of the data life cycle in Big Data are as follows:
    
    - Análisis interno
    - Recogida y filtrado de datos
    - Extracción de datos
    - Validación y limpieza de los datos
    - Análisis de los datos
    - Visualización de los datos
    

+ Internal analysis: The Big Dara life cycle must begin with the understanding of the business and a justification of the need to carry out an analysis of this type, as well as the establishment of the objectives to be achieved. This stage of analysis allows us to understand the current situation of the company and what resources will be required throughout the analysis.
Likewise, those KPIs necessary to understand the results of the analysis and their ability to meet the established goals and objectives must be established.

+ Data collection and filtering: This part of the Big Data Life Cycle is dedicated to identifying those data relevant to the analysis, identifying the sources to find patterns and correlations.
The selection of data depends on the nature of the problem and the objectives established in the first part of the cycle. The data is collected and subjected to a filtering of corrupt data or data that does not respond to the established objectives.

+ Information extraction: The main objective of the data is to transform these into information. At this stage the data extraction and its transformation into an understandable format are carried out in order to perform a data analysis.

+ Validation and cleaning of data: Incorrect or invalid data can lead to false results that harm the analysis. The unstructured nature of Big Data makes their validation difficult. Therefore, this stage of the Big Data Life Cycle is essential, since it allows to reach the most relevant data for the objectives set.
In addition, this analysis not only allows the discarding of invalid data, but the analysis and observation of said data allow establishing patterns and trends that contribute to improving the understanding of the data to be analyzed

+ Data analysis: At this stage the integration of data sets is developed in order to give a unified view of the information. Throughout this stage of the cycle several problems of data structure and labels can occur.

+ Data visualization: Once the data is organized, it is necessary to transform it into information that provides value. All the useful information extracted must be “translated” in the form of reports that allow the correct interpretation of these.

  Reference: <https://piperlab.es/2019/05/14/el-ciclo-de-vida-de-los-datos-las-5-fases-para-llevar-a-exito-un-proyecto-de-big-data/>
***

 
+ Exploratory Data Analysis (A.E.D.): Is a set of statistical techniques whose purpose is to achieve a basic understanding of the       data and the relationships between the analyzed variables. To achieve this goal the A.E.D. provides simple systematic methods for       organizing and preparing data, detecting failures in the design and collection of data, treatment and evaluation of missing data,       identification of atypical cases (outliers) and verification of the underlying assumptions in most of multivariate techniques           (normality, linearity, homocedasticity). The prior examination of the data is a necessary step, which takes time, and is usually         neglected by data analysts. The tasks implicit in such an examination may seem insignificant and without consequences at first sight,   but they are an essential part of any statistical analysis.

  - STAGES OF THE AED To perform an AED:
   
    - Prepare the data to make them accessible to any statistical technique.
    - Perform a graphic examination of the nature of the individual variables to be analyzed and a numerical descriptive analysis that         allows quantifying some graphic aspects of the data.
    - Perform a graphic examination of the relationships between the analyzed variables and a numerical descriptive analysis that             quantifies the degree of interrelation between them.
    - Evaluate, if necessary, some basic assumptions underlying many statistical techniques, such as normality, linearity and                 homoscedasticity.
    - Identify possible atypical cases (outliers) and evaluate the potential impact they may have in subsequent statistical analyzes.
    - Evaluate, if necessary, the potential impact that missing data may have on the representativeness of the analyzed data.

***

+ Extraction, transformation and loading process(ETL): It is a data pipeline that is used to collect data from various sources, transform the data according to business rules and load it into a destination data store. Transformation work in ETL takes place in a specialized engine and often involves the use of temporary storage tables to temporarily retain data as they are transformed and eventually loaded into their destination.The data transformation that takes place often involves several operations such as filtering, sorting, aggregation, data merging, data cleaning, duplication and data validation.


   ![alt text](https://docs.microsoft.com/es-es/azure/architecture/data-guide/images/etl.png)
Frequently, the three phases of the ETL process run in parallel to save time. For example, while data is being extracted, a transformation process on the data already received and preparation for loading may be working, and a load process may begin to work on the prepared data, instead of having to wait for That ends the entire extraction process.

***

+ Statistical data analysis: They are basically of 2 types, continuous data and discrete data. The continuous information is the one that cannot be told. For example, the intensity of a light can be measured but cannot be counted. Discreet information is what can be told. For example, you can count the number of bulbs.
Continuous data in the analysis of statistical data is distributed under the function of continuous distribution, which can also be called the probability density function or fdp
The discrete data in the statistical data analysis is distributed under the discrete distribution function, which can also be called the probabilized mass function fmp.

***

+ Data flow diagram: Trace the flow of information for any process or system. It uses defined symbols, such as rectangles, circles and arrows, in addition to short text labels, to display data inputs and outputs, storage points and routes between each destination. The data flow diagrams can vary from simple process scenarios even hand-drawn, to very detailed DFD and with multiple levels that progressively deepen how the data is handled.
  
  - Example:

     ![alt text](https://image.slidesharecdn.com/dfdprofyedra-160313133606/95/diagrama-de-flujo-de-datos-dfd-16-638.jpg?cb=1457877018)
 
 
