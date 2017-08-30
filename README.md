# 1OneOne
Globally Accessible Disaster Response Solution for citizens/NGOs/1st Responders/Governments

As an outside observer of many disaster situations, consuming specifics mostly from news media, one of the key observations I have made is that "WE HAVE NOT YET ENTERED THE DIGITAL AGE" as far as disaster response is
concerned!

Case-in-point, with Hurricane Harvey battering Texas, people who needed help, would dial 911 and if they were lucky enough to get through and reach a voice prompt, in many instances wait time was 45 minutes or more because their resources were stretched too thin! Some affected people/families relied on social media to send their pleas for help, and in many such cases social crowd had a very effective response to the situation. However, not everyone is twitter savvy or well connected on Facebook and know how to tag their posts so that it does not get drowned in a stream of millions of posts happening on these networks. 

Also in one of the radio interviews a Police Chief of Houston (?) was asked about all 911 being stretched too thin and not able to handle call volume. Interviewer also brought up that many people are sending their pleas for help on social media. **In response, police Chief's response was that they do not have capacity or staff trained to find needles in this haystack of social media chatter (words are my representation of the police chief response since I do not have exact quote.**

Now shifting focus away from Houston a little bit, around same time there is a major flooding situation happening in South Asia (Eastern India, Bangladesh ....) where **tens of millions of people are affected by floods and some 1000/1500 people have perished!** Talk about Tsunamis in Asia, earthquake in Haiti and many many more disasters where scale is so huge that no traditional 911 type of system can effectively respond to the situation. 

Hence, the though is born that we really need a new solution for the Digital Age - a solution that can save lives in immediate aftermath of the disaster, and provide a common platform for recovery efforts.

Why Open Source?
I know that there is plenty of money being spent on disaster response and recovery efforts everytime there is a disaster, and someone with effective solution and plenty of "reach" to get necessary contracts signed could make enormous amount of money by offering this type of solution "as a service" if they target western economies. However, disaster does not strike based on people's economic status or their geography - on the contrary, when distaster strikes, poorer people are harmed much more disproportionately. So one of the key goal here is that whatever solution we can build as "contributors" of this open source project, it should be available and accessible to everyone and everywhere without their financial status or their government's ability to pay for it. 

The Road-map:
This is just the beginning. Over last few days (end of August 2017), I have started putting together a wish list, and want to build one Deck (for those of us who don't like to read plain text READMEs) to attract potential contributors into this project and help build this solution.

---------------------------------------------
Initial thoughts:
---------------------------------------------
- Build a white-label-ready, cloud-ready disaster portal that can be readily available for deloyment annd use across various geographies
by local/state/federal governments (if they chose to), by NGOs, or by pretty much anybody else. This will allow local administrators to set geographic boundaries of the areas of interest or areas they serve.
- Build a core router at 1OneOne.com / 1OneOne.org to bind all these deplyments and keep track of geographic boundaries catered by each deployment.
- Build smartphone apps that users can download on their phones across supported platforms. 

-------------------------------------------------------------
PIE-IN-THE-SKY: Some of the core capabilities envisioned are:
-------------------------------------------------------------
Front-office / consumer facing capabilities where...
  - Part of reporting/requesting asstance: someone can report disaster situation, request assistance, share pictures/videos, status updates. Using AI, NLP and other modern approaches, the system will do the job of filtering this information to create views for "information of interest to officials and responders", to "families and friends", to "news media", and "social media"
  - Part of reuniting families goal, allow reporting of lost or missing family members, friends, and/or pets
  - A "Community Thread" view to allow folks to check on status of their loved ones in the affected areas
  - check official status updates and status 
  - request/accept donations
  
Back-office / Administration capabilities:
- TBD
- View all 1OneOne responding organizations active in geography of interst
- Activate disaster situation in a certain geographic area
- Send updates and alerts to registered devices in the affected area
- Route Assistance requests to field responder and/or other entities as necessary
- Respond to individual requests with status updates
- Process donations
- Manage monetary/non-monetary donation distributions
  
App Features - Requester-side:
- App will auto locate nearest disaster response team's deployment of 1OneOne (through 1OneOne.com acting as DNS of sorts). If disaster situation is activated by the 1OneOne server, the app will prompt user to register user being in the affected zone, and receive alerts/updates from the 1OneOne responders team. 

- Request assistance - with as much or as little information they are able to provide. Goal here is that a user in disaster situation should be able to request assistance simply by pressing one button if necessary - system could automatically catpure GPS coordinates, ambient noises, pictures of surroundings, using voice UI interact with user, and capture voice memo from the user to be passed onto responders. OR the app will allow user to provide specifics details while requesting help. If there are network bandwidth issues (often there are in disaster situations), the app could simply use SMS texting mechanism.


App Features - Responders-side:
- Find nearby requesters, understand their requests and situations
- Receive requests for assistance rounted by the back-office team and accept/reject a specific request (think Uber)
- Communicate with specific requester and obtain specific details if necessary
- Status update on assigned requests - voice, video, pictures, text












