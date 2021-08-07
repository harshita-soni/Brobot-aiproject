# MSA-aiproject

## :rocket: Problem Specification

Globally, the pandemic has disrupted healthcare chains that provide health services and has highlighted the shortage of medical staff worldwide. And in mental healthcare, which has taken a severe hit during the pandemic, it has emphasized that there are [not enough mental health professionals to meet demand](https://www.who.int/news/item/05-10-2020-covid-19-disrupting-mental-health-services-in-most-countries-who-survey).

> “The sudden loss of employment and social interaction, and the added stressors of moving to remote work or schooling, and more recently, impacts of sudden, localised ‘lockdowns’ to prevent further outbreaks have **severely impacted** the mental health of many Australians.”

> “...while many people may not experience any long-term concerns, COVID-19 has the potential to contribute to or exacerbate long-term mental illness including anxiety, depression, PTSD, and substance misuse.”
      
-[Australian Institute of Health and Welfare](https://www.aihw.gov.au/reports/mental-health-services/mental-health-services-in-australia/report-contents/mental-health-impact-of-covid-19)

During the many lockdowns we faced and continue to face in Australia, most of the mental health screening services had to be offered via telephone or video consultations. And with the number of affected people increasing, there has been a clear lack of resources available. There is still heavy uncertainty as to when and how things would return to normal. Hence, there is **a need for a new generation of mental healthcare tools that are as dynamic as the people they serve** in the post-COVID world.

## :rocket: Idea

The idea behind this project is **to develop technology capable of building trusted relationships and conversations** with people. This can be achieved by deploying a bot service that can help ease the initial screening process for people who are seeking mental health related aid. 

Sometimes all we need is to talk to someone or have someone listen to us. Some of our most vulnerable moments happen at 2 am, when there’s no one around. BroBot is designed to be there for you, to have a tiny conversation, to vent out your feelings and to direct you to the right professionals if required.

## :rocket: Approach

### Why AI?
[Recent research articles](https://pursuit.unimelb.edu.au/articles/hey-siri-how-s-my-mental-health) have concluded that conversational systems have the potential to play a key role in future mental healthcare and also to help cut down global e-waste. Azure Bot Service incorporates artificial intelligence, natural language processing and a natural conversation experience seamlessly and is hence ideal for this project.

### Data Phase
To create a knowledge base for the bot, data was collected from FAQ pages of various organisations that provide mental health services. Upon creation of the knowledge phase, these Q&A were edited and additional phrases were added to each question to ensure maximum efficiency.

### Model Phase
Once the initial knowledge base was ready, a few trial runs were done. Next, it was linked to a chat bot using the Azure Bot Service, and the chit-chat personality was set to be caring & empathetic. The bot has been deployed to be accessed through web, but can further be expanded to other channels such as Microsoft Teams.

### Production Phase
I sent the link to the chatbot to a few friends to seek feedback. This brought up several errors and bugs where the bot was giving answers that may be conceived as inappropriate. More questions, answers and alternative phrasing were then added to the knowledge base to incorporate whatever issues were brought to light.


## :rocket: Implementation 
The dataset was scraped from FAQ pages of numerous organisations, such as:
-	https://www.wellnessinmind.org/frequently-asked-questions/
-	https://www.heretohelp.bc.ca/questions-and-answers
-	https://mhaustralia.org/resources/frequently-asked-questions
-	https://magazine.vitality.co.uk/10-biggest-mental-health-questions/
-	https://www.webmd.com/mental-health/qa/default.htm
-	http://www.mhbsf.org/faq/

Care was taken to ensure the data only comes from sources that are certified or have been working in the field for a long time. This generated a knowledge base with about 120 different questions. Few of the questions specific to the organisation itself were removed during the pre-processing phase. This was followed by adding alternative phrasing for each question.

Upon receiving feedback from people who tried striking conversation with the initial version of the bot, the questions were further fine-tuned. More questions were added on topics relating to suicide prevention, bereavement, grief management and LGBTQ+ representation, bringing it to a total of 133 q&a pairs.

A few of the bugs reported are as follows:

<img src="https://github.com/harshita-soni/MSA-aiproject/blob/main/images/My%20Post-2.png" alt="Screenshots" width="500" height="500">

## :rocket: How to run the code
The repository contains one HTML file [bot.html](https://github.com/harshita-soni/MSA-aiproject/blob/main/bot.html) and one Jupyter Notebook [bot.ipynb](https://github.com/harshita-soni/MSA-aiproject/blob/main/bot.ipynb) which can be downloaded and run to produce the web app for Brobot. The HTML file is the easier of the two options as it can be run without any specific software requirements.
