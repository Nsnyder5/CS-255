# CS-255
Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

DriverPass essentially provides a better way for student drivers to study for their theoretical driving exams, and schedule appointments to practice their practical driving tests. DriverPass wanted to create a website that allows customers to create an account, purchase a study package, study and take exams online, and schedule appointments with drivers to practice. Employees of DriverPass also need the ability to purchase packages for customers and schedule their appointments. Below is the Gnatt Chart I created: 
<img width="2042" height="1196" alt="image" src="https://github.com/user-attachments/assets/a4f94600-54ac-47db-91fd-58e3c8a77a9e" />


What did you do particularly well?

I felt that my diagrams and descriptions in project 2 were easy to understand and provided context and crucial information for key concepts of the application.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I think I could've added even more detail to my descriptions in project 1. Other than that, I am pretty proud of my work.

How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

I felt that I was able to understand the user's needs via the technical requirements and interview. I created use cases and diagrams to fit these use cases, which allowed me to visualize the user's needs. I then adapted the needs into what would be possible for a website. The users are the ones that use the site the most, so their needs must be at the forefront. In addition, making sure the site is easy to use and comprehend is also important. Attached are all the Use Case Diagrams I created. 

UML Case Diagram: 
<img width="1324" height="1188" alt="image" src="https://github.com/user-attachments/assets/72a60370-9756-4567-8cfd-80022cfcf9a6" />

UML Activity Diagrams 
<img width="996" height="1382" alt="image" src="https://github.com/user-attachments/assets/9afa798b-05cd-4c5e-b427-6a9a60f92462" /> <img width="1200" height="1314" alt="image" src="https://github.com/user-attachments/assets/1008ed9d-b88c-4247-818e-6f152098c413" />


UML Sequence Diagram
<img width="1436" height="640" alt="image" src="https://github.com/user-attachments/assets/567526b1-89b2-4a42-9488-06ef57624b80" />


UML Class Diagram
<img width="1378" height="768" alt="image" src="https://github.com/user-attachments/assets/dd66644f-6484-4e6e-8c22-b1c74ef00a0a" />



How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

Thinking in terms of functional and non-functional requirements was very helpful for the software design. I also felt that creating use case, UML, and Gantt diagrams was very helpful for visualization and giving others a better understanding of what the application should do. I've also done well with depicting things visually in order to get my point accross. 

My Speaker Notes for the Presentation: 
Slide 2: "First, let's look at what the system will actually do for you. Based on our interviews, we identified two main 'Functional Requirements'; these are the core jobs the software performs. First, it allows you to schedule a full session in one go. Second, and most importantly, it acts as a gatekeeper: the system automatically checks if a car or instructor is free before it lets you book. This eliminates human error. We also have 'Non-functional Requirements,' which are about performance. We made sure the system works in your web browser so you don't need to buy special computers, and we set a speed target so your staff isn't waiting around for pages to load." 

 

Slide 3: "This is what we call a Use Case Diagram. It's a high-level map of who interacts with your system and what they can do. On the left, you see the 'Administrator'—that's you or your receptionist. You can see lines connecting the Admin to tasks like 'Schedule Driving Session' and 'Manage Student Profiles.' This diagram confirms that the system covers all the daily responsibilities we discussed, ensuring that no part of your workflow is left out of the digital transition." 

 

Slide 4: "This Activity Diagram gets into the details of a specific task: Scheduling a Session. Think of this as a flowchart for the software's brain. It starts when you enter the student and time. The diamond shape represents a decision point where the system asks, 'Is this instructor free?' If the answer is 'No,' it stops you and shows an error. If 'Yes,' it saves the appointment. This logic is built directly into the code to prevent the double-booking conflicts that were happening with the paper logs." 

 

Slide 5: "We know that you handle sensitive student information, so security was a top priority in this design. First, every staff member will have their own secure login. We also use SSL encryption, the same technology banks use, to ensure that when you send data from your computer to the server, it can't be read by anyone else. We also added a safety lock; if someone tries to guess a password and fails three times, the account locks up to stop hackers." 

 

Slide 6: "Finally, in the spirit of transparency, I want to outline the current limitations. First, while we track appointments, we aren't processing credit cards inside the app yet, but you'll still use your current payment terminal for that. Second, this is a staff-facing tool, so there isn't a mobile app for students to download just yet. And lastly, because it is cloud-based, you will need an active internet connection to access the schedule. These are things we can look at upgrading in Phase 2, but for now, we focused on your core scheduling needs." 
