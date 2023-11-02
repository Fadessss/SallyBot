# SallyBot

**Introduction**

SallyBot is an innovative chat bot prototype developed for Te Whatu Ora Counties Manukau. This project is part of our R&D project with the primary goal of streamlining HR processes, as SallyBot will assist the HR department by answering common queries, thereby reducing the workload on HR professionals. However, SallyBot goes beyond HR and is designed to provide information and support on a variety of topics, including Health & Safety, Finding Locations, and Project X.
Features

    HR Support: SallyBot can answer HR-related questions, guide employees through the onboarding process, and provide information about company policies and procedures.

    Health & Safety: SallyBot is equipped to offer information on health and safety guidelines, reporting incidents, and providing first-aid instructions.

    Location Services: Users can inquire about clinics locations, hopistals for Counties Manukau.

    Project X Information: SallyBot provides updates and relevant information about Project X, ensuring employees are well-informed.

**Installation**
1. Open Bot Framework Composer
2. Click "Open" and navigate to ./SallyBot/Sally
3. Open the bot (it will have a robot icon).
4. Click Publish in the left sidebar
5. Create a publishing profile. IMPORTANT NOTE: If you create new resources, your app service plan will default to "Standard" which charges roughly $5.00 NZD per day. Please immediately change your App Service Plan in the Azure console to the free plan by clicking "scale-up (App service plan)" in the side menu, selecting free, and confirming that you wish to downgrade.
6. Select your Azure Bot resource, select channels from the side menu, and select Microsoft Teams from the list of available channels. You can now open the bot in teams to test. IMPORTANT NOTE: This bot cannot be tested easily via web app, it is designed to be functional within teams.
7. If you would like to deploy this as a teams app please refer to these resources:
   
https://microsoft.github.io/botframework-solutions/clients-and-channels/tutorials/enable-teams/4-create-app-manifest/ 

https://learn.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/teams-developer-portal?source=recommendations

https://learn.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/apps-upload 
    
**Usage**

SallyBot is designed to be user-friendly and intuitive. Users can interact with it by typing or speaking their queries. Below are some example interactions:

    "How do I apply for annual leave?."
    "What are the health and safety guidelines?"
    "Tell me about the latest updates on Project X."

SallyBot will interpret these queries and provide relevant responses or guide users through various processes.
