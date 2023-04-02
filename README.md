# FactFindr

## Inspiration
In this era of technology, the intake of information through digital media has grown exponentially and it has provided people with personal motives to spread falsified information among the masses to create biased opinions and a sense of unrest. The falsified information is provided to the people especially during elections to create political unrest among the masses or simply to spread a rumour. Since most of the information consumed by people is in the form of text, through newsletters, it has become a great target spot for people with malicious intent. 

FactFindr focuses on detecting falsehoods and provides analytic insights based on the organization, country, events or person in a visually compelling manner.

## What it does and How we build it
FactFindr includes:
1. Data Preprocessing - Assigns the label to true and fake news. Cleaning, and formatting the data. Concatenating both datasets together. 
2. NLP - To extract relevant information, this uses the techniques like stopwords, tokenization, converting to lowercase, and stemming. 
3. Extracting Information - For better understanding with respect to organization, person, and country that appears more frequently in the news. 
4. Visualization - To visualise the relationships among news with sentiments and analytic insights based on the organization, country, events or person.
5. Modelling - To identify the long-term dependency, the dataset is trained on LSTM (long short-term memory networks).

## Outcomes
1. From extracting the information we could able to see the correlation between the label, organization and Person. For example:
After calculating the correlation between different features in the dataset, it appears that the combination with the highest count is (0, "Clinton", "FBI"). This suggests that news articles related to Clinton and the FBI may be more likely to be fake news. ![Correlation2](https://user-images.githubusercontent.com/56245613/229376479-f0b2702a-f75e-4f1b-afe8-6e83980f0bf8.png)



2. From extracting the information we could able to see the correlation between the organization, country and Person. For example:
("russia", "nato") are showing one of the top 15 correlations, similarly ("nvestig","fbi","hillari clinton")	 as per the dataset.
![Correlation](https://user-images.githubusercontent.com/56245613/229376472-1f5ff5ab-0663-479f-8570-e76bf9753541.png)

