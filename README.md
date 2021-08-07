# MSA-aiproject

## :rocket: Problem Specification

Globally, the pandemic has disrupted healthcare chains that try to provide health services and has highlighted the shortage of medical staff worldwide. And in mental healthcare, which has taken a severe hit during the pandemic, it’s underscored that there are [not enough mental health professionals to meet demand](https://www.who.int/news/item/05-10-2020-covid-19-disrupting-mental-health-services-in-most-countries-who-survey).

> “The sudden loss of employment and social interaction, and the added stressors of moving to remote work or schooling, and more recently, impacts of sudden, localised ‘lockdowns’ to prevent further outbreaks have **severely impacted** the mental health of many Australians.”

> “...while many people may not experience any long-term concerns, COVID-19 has the potential to contribute to or exacerbate long-term mental illness including anxiety, depression, PTSD, and substance misuse.”
      
-[Australian Institute of Health and Welfare](https://www.aihw.gov.au/reports/mental-health-services/mental-health-services-in-australia/report-contents/mental-health-impact-of-covid-19)

During the many lockdowns we faced in Australia, most of the mental health screening services had to be offered via telephone or video consultations. And with the number of affected people increasing, there was a clear lack of resources we could access. There is still heavy uncertainty as to when and how things would return to normal. Hence, there is **a need for a new generation of mental healthcare tools that are as dynamic as the people they serve** in the post-COVID world.

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

### Future Scope
This project has vast possibilities of scaling and expansion. The app can be linked with the dataset of all mental health service providers in the specified area and people can be linked to the one of their choice. More options can be added to do a proper screening (as prescribed by a professional) for users who wish to get a report and send it to their mental health professional. It can potentially fill the gaps along the entire mental healthcare journey, from symptom monitoring to episode management.
