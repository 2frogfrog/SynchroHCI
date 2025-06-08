# Redesigning synchro - ACE
![](https://github.com/2frogfrog/SynchroHCI/blob/3517aa6a9f9eb57b5bb03aefc25e42dd9be02640/project_report/images/logo.png)

## **Problem and Design Overview**
For this project, we focused on streamlining task management and simplifying the map import process. Many users reported feeling overwhelmed by the volume of tasks displayed and noted redundancy across several of them. Additionally, importing maps was a tedious process. Users had to locate a map using a third-party service, such as Google Maps, take a screenshot, and manually upload it to Synchro Studios. They then had to draw lanes over the imported image to begin adjusting parameters. To address these challenges, we implemented a minimalistic design aimed at reducing cognitive load and enhancing the learning experience for our target audience.


## **Design Walkthrough**
For our design, we chose two main tasks to focus on and work to improve. We wanted to make the lane settings more user-friendly to new users and provide a better way to import a map. Through user research and many sketches, we felt these were the most important fixes to Synchro. 
#### Importing Maps
The goal was that a user should be able to import a map directly from 3rd party services like google or apple maps or upload an image. If the image isn't clear, the user should be able to be redirected to a help page and find a way to fix the issue.
#### Lane Settings
After they had imported the map, the lane settings were the next task we chose to work on. We wanted to simplify the settings and add a search bar to immediately find the parameters of a lane. Not only that but we wanted to clearly show which lane you have selected by highlighting it on the map as well as the header bar of the lane settings.



## Design Research 
#### Research Process
The goal of our user research was to focus on new users and the struggles they faced when learning the software, as well as a larger
scale perspective of all types of users both novice and experienced to see what common issues they all faced. With that in mind, we 
chose two methods of user research: participation observations and surveys. We observed new users in a Civil Engineering classroom 
where the class had never used the software before and then sent out a survey to not only those students but other instructors and 
people who possibly had experience.
#### Key Insights
- *New users struggle with importing a map*: While observing the engineering class we noticed multiple students struggling to work with importing a Google image and using it
  to create an intersection. We decided to then make this one of our main tasks since it seemed impractical for users to be tabbing 
  between Synchro and Google Maps constantly.
- *The lane Settings are overwhelming to new users*: From both the survey and observations we noticed that the lane settings in general were very hard to grasp. There was too much information displayed at once, and it was difficult to find individual parameters as needed.
- *Adding a new lane is not intuitive*: From the observation study, it appeared that many new users didn't find the way to add lanes easy or self-explanatory. Our goal was to make it clear when you add a lane and to make it visually obvious what lane you are currently using. 


## Iterative Design
#### Design Process
##### Paper Prototype to Usability Testing
In the early stages of our design process, we built a paper prototype of Synchro Studio that focused on two core tasks: importing maps and editing lane settings. We simulated key interactions using cutouts and dialog boxes, allowing users to walk through steps like selecting a map source, handling errors during import, and editing lane configurations. This helped us visualize the app's basic structure and interactions. Usability testing revealed that while the map import flow was fairly intuitive, especially when users were guided through error resolution, there was confusion around the dropdown menus for editing lanes. One participant misunderstood their purpose, suggesting that the interaction wasn't as clear as we thought. This process showed us that assumptions about what's obvious to users don't always hold true, especially when it comes to interface elements that aren't visually distinct or self-explanatory. Based on what we observed, we made changes to make the interface clearer and easier to use, helping us move on to a digital prototype.
##### Digital Prototype to Heuristic Evaluation
After developing a digital prototype of Synchro Studio, we tested it with users to evaluate how well the interface held up during real interaction. The prototype included an interactive map import process, error handling, lane selection, and parameter editing through a searchable interface. During the heuristic evaluation, we observed that the first task, importing a map, was generally clear, but the second task, editing lane parameters, caused confusion due to unclear instructions and interface feedback. This highlighted the need for better visual cues and more intuitive workflows. As a result, we made these improvements: we greyed out inactive functions at startup to guide the user through the correct sequence of actions, added a “Try Again” button to simplify re-importing maps, and introduced visual highlights to make active lanes more obvious. We also replaced numbered parameter lists with named ones and added an “X” to close the parameter panel, helping reduce clutter and making the interface easier to understand. Reflecting on this process, we realized how small interface changes, like button states, highlights, and naming conventions, can have a big impact on how confident and in control users feel. These insights pushed us to focus more on clarity, feedback, and reducing guesswork in the final design.
#### Key Insights
-How designers intend their software to be used can often differ significantly from how users actually interact with it. This became evident during our usability testing, where participants struggled with navigating and modifying lane settings. To address this, we adjusted the software to enforce a sequential workflow. This was accomplished by disabling certain buttons until prerequisite actions were completed and introducing pop-up dialogs that guided users step-by-step, similar to reading a book. These constraints helped reduce confusion by directing users through the intended process in the correct order.
-Initially, we focused heavily on core functionality and unintentionally overlooked smaller features that contribute to a smooth user experience. For instance, in our digital prototype, users who failed to import a map had to close the error message and restart the entire process. We improved this by adding a "Try Again" button, which brought users back to the initial import screen and adding a “X” button to close the lane settings panel.
-Visual design elements like color can significantly enhance the usability of software. During testing, users reported confusion when trying to determine which lane or setting they were modifying. In response, we implemented color highlights by marking the active lane and setting in yellow to draw attention. We also improved the readability of the parameters table by alternating row colors between light blue and gray, helping users visually distinguish between different parameters.
## Technical and Soft Skills Learned
#### Technical Skills
- Figma
- Conducting User Research
- Usability Testing
- Prototyping: sketches, storyboarding, paper, and digital
#### Soft Skills
- Adaptability
- Collaboration and teamwork



