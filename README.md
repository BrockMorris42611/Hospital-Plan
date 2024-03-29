Brock Morris
Professor Aldwairi
Software Design
9/14/21

# Hospital Patient Organizational Tool with Unique Access for Nurses, Doctors, and Patients

<p>&nbsp;</p>

**Project Abstract**

![alt text](USERCASE%20DIAGRAM.PNG)

This project will be to build an organization system for hospitals. It functions on setting priorities for patients by looking at part of the hospital they are in whether it be the ICU, ER, or just a routine checkup. Profiles will exist for each patient and will contain various personal information. When a new patient is admitted, they will be placed in either of the previous mentioned categories, and then an urgency number (1 being the most urgent, and 5 being the least) based on their injury or lack of injury. There will also include a portal of some type with the option to sign in as a doctor, a nurse, or a patient with each having different privileges. A doctor can see every patient and which nurse is taking care of them as well as up coming procedure to be done by other doctors and nurses. A nurse can see what patients are next to be treated and the room number they are in. A patient can see the bills they have accrued, which doctor is treating them, what room they are in, and whether or not they have been cleared to go. Patients may also alter their personal information and insurance while nurses and doctors alter specification for treatment and priority levels. Patients also have access to a map of the hospital and cafeteria menu. They can also choose different payment plans for paying off their bills based on their credit score and health insurance rating. Doctors can also see the trend of patients and diseases via graphs with check marks indicating filters. I would also kind of like to have minimal queries and calls to the database so maybe a sort of cache map could be created to sort of hold the newest entered patients and then clear it upon log out.
<p>&nbsp;</p>

**Project Relevance**

This will be an object-oriented project with varying levels of control starting with doctors and going down to the patient level. There will also be object-oriented billing plans for the customers and then even one for the patient admittance type. Test driven development will be used to check every step of the way making sure that SQL queries go as smoothly as intended and are correct, among other things. A graphical interface will be put in place and will vary from each login type (i.e., a doctor will see different options than a nurse and patient, vice versa). There will be plenty of debugging in terms of making sure the different components interact well. This is also good way to become familiar with UML
<p>&nbsp;</p>

**Conceptual Design**

My contributions would include setting up a GUI and making sure all the mutations of it match the specific class of the “person” who is logging in be it a doctor, nurse, etc. I also would be able to work on the graphs and data for the doctor’s end of the platform so that data is represented in a way that is useful and maybe based off real-life examples. I can make sure these things are done right through TDD and checking expected outcomes depending on the situation or functionality being worked on. When it comes to the GUI, I need to do research on ones that are either built into java or a nicer looking integrated one that is found online. I also wouldn’t mind checking for optimization in implementation or just better data structures to use if needed. I also wouldn’t mind if someone wanted to turn this into a web-app or a mobile app.
<p>&nbsp;</p>

**Required Resources**

I would just need someone who knows how to do web application stuff, since I know nothing about it, and maybe someone to help me with phone application implementation. Help from someone who is decent with SQL or some other database query language that anyone knows. This is also preferably done in java to help with SQL integration, but I’m open to other solutions based on any other features that I or others want to add.
