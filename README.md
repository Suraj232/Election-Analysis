# Election-Analysis
## 1.	Overview of Election Audit
##### The main purpose of this audit is to gather the election data and calculate the findings by using python programing language. With the help of this programming language, the end result is easily calculated and the result is displayed.
## 2.	Election-Audit Results
### 
- 369,711 votes were cast in this congressional election.
- The breakdown of the total number of votes for each county is shown in the image below:

  <img width="168" alt="County_Votes" src="https://user-images.githubusercontent.com/110261837/190295793-5fa15ef8-3040-45b4-b7d4-b64784a3fc41.png">
- Denver County has the largest number of votes with 306,055
- The Breakdown for the votes received by the Candidates is shown in an image below:

  <img width="236" alt="Candidate_Votes" src="https://user-images.githubusercontent.com/110261837/190296341-d799390a-af34-4e14-b216-bb5061c8a1c7.png">
- Diana Degette won the election with 272,892 votes. Her votes accounts to 73.8% of total votes.
## 3.	Election-Audit Summary: 
This same piece of code can be reused by doing a bit of modification.
-First modification required will be to load a different csv file. 
For example

- First change can be made by using different csv file. 
- For example, At the very beginning of the code at line no. 9 file_to_load = os.path.join(“election_results.csv”)
  If another file with the same format data is uploaded, then the code will work fine and give the results accordingly.
- Second changes required will be inidentifying the correct header names from the csv file. If the csv data’s have different header, then the selection of columns for  rows[ ] function will be different. For example, if the county name is in column 3 and candidate is in column 2 then only changes required is to mention the correct column number in row[ ] function.
For example: Candidate_name = row[1]
