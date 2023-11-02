# SallyBot

**Introduction**

SallyBot is an innovative chat bot prototype developed for Te Whatu Ora Counties Manukau. This project is part of our R&D project with the primary goal of streamlining HR processes, as SallyBot will assist the HR department by answering common queries, thereby reducing the workload on HR professionals. However, SallyBot goes beyond HR and is designed to provide information and support on a variety of topics, including Health & Safety, Finding Locations, and Project X.
Features

    HR Support: SallyBot can answer HR-related questions, guide employees through the onboarding process, and provide information about company policies and procedures.

    Health & Safety: SallyBot is equipped to offer information on health and safety guidelines, reporting incidents, and providing first-aid instructions.

    Location Services: Users can inquire about clinics locations, hopistals for Counties Manukau.

    Project X Information: SallyBot provides updates and relevant information about Project X, ensuring employees are well-informed.

**CONTENT**

There are two important directories in this project containing two different bot options:

    - Sally Language Studio

    - Sally Bot Framework Composer 

These are two different implementations of the same bot using Language Studio and Bot Framework Composer. 
We recommend using the Language studio bot as opposed to the Bot Framework Composer bot. Its advantages are listed in the included User Guide.

Detailed installation instructions can be found in the User Guide, but an abbreviated guide for each is also provided below.

**Installation for Sally Language Studio**
1. Open Language Studio and create a Custom Question Answering project.
2. Inside your project click "Add source". Select the .xls file inside the Sally Language Studio folder.
3. Click the publish button on the left sidebar and publish your knowledge base.
4. Create a bot using this knowledge base from the publish screen. You can get your Language Resource Key from the Azure console by going to {Your Language resource} -> {Keys and Endpoints} -> Copy "Key 1".
5. Go to the App Service resource, click "Configuration" and change the value of "EnablePreciseAnswer" to 'false'.
6. Select your Azure Bot resource, select channels from the left sidebar, and select Microsoft Teams from the list of available channels. You can now open the bot in teams to test it.

**Installation for Sally Bot Framework Composer**
1. Open Bot Framework Composer
2. Click "Open" and navigate to ./Sally Bot Framework Composer/Sally
3. Open the bot (it will have a robot icon).
4. Click Publish in the left sidebar
5. Create a publishing profile and publish your bot.
6. Select your Azure Bot resource, select channels from the left sidebar, and select Microsoft Teams from the list of available channels. You can now open the bot in teams to test it.

**IMPORTANT NOTE:** If you create new Azure resources for either of these bots, your app service plan will default to "Standard" which charges roughly $5.00 NZD per day. Please immediately change your App Service Plan in the Azure console to the free plan by clicking "scale-up (App service plan)" in the side menu, selecting free, and confirming that you wish to downgrade. Also make sure that the Azure Bot service is on the "F0" (free) service plan.
 
**IMPORTANT NOTE:** Sally Bot Framework Composer cannot be tested via web app, it can only be tested through teams. Sally Language Studio can be tested in both.

If you would like to deploy this as a teams app please refer to these resources:
   
https://microsoft.github.io/botframework-solutions/clients-and-channels/tutorials/enable-teams/4-create-app-manifest/ 

https://learn.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/teams-developer-portal?source=recommendations

https://learn.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/apps-upload 
    
**Usage**

SallyBot is designed to be user-friendly and intuitive. Users can interact with it by typing or speaking their queries. Below are some example interactions:

    "How do I apply for annual leave?."
    "What are the health and safety guidelines?"
    "Tell me about the latest updates on Project X."

SallyBot will interpret these queries and provide relevant responses or guide users through various processes.
