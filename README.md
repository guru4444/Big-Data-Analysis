Background: Power of big cloud computing services provided by IaaS companies like microsoft and google have opened doors to a lot of possibilities. Big data analysis has now become more efficient and affordable. Multiple claims were made by the documentary "Ross Kemp and the armed police", the major reason for this project to happen is to prove or disprove the mentioned claim. The given crime data consists of millions of rows of data, according to Tsai et al., best way to analyse big data is to analyse the data using innovative methods [1]. Also, as seen in [2] Apache spark comes with great deal of features that are best suited to analyse big magnitude of data efficiently.

Objective / Aim: There are 3 major claims made by the documentary "Ross Kemp and the armed police" with respect to violent crime in UK.

Violent Crime is increasing.
There are more firearms incidents per head in Liverpool than anywhere else in the UK.
Crimes involving firearms are closely associated with drugs offences
The aim of this project is to analyze the data available and to find out whether the claims given above are true or not. For efficient analysis Apache Spark and IaaS (Infrastructure as a service) are preferred.

Technical Approach:

The general approach followed to analyse the data is as follows:

Schema optimization

Filtering required data

Data Preprocessing

Visual Representation

Getting Insights

The approach starts with optimizing the schema of the loaded data, next according to the claim the required data is filtered. After which data preprocessing steps have been undertaken like removing duplicate rows, filling missing values etc. Then comes the visual representation here according to the claim the data is visually analyzed with the help of a graph. Finally insights are obtained based on the analysis.

Additionally, for claim 1 (violent crime is increasing), ARIMA model is used to find the right solution. Stationary test is also used before getting into the model.
