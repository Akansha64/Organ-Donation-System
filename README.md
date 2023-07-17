# Organ-Donation-System
ORGAN DONATION SYSTEM

1. Introduction:
● The organ donation system aims to manage organ donation records efficiently,
ensuring a seamless process of matching donors with recipients.
● The system will track and maintain information about donors, recipients,
admins(hospitals), and organ types to facilitate effective organ transplantation.

2. Database Design:
● At first, we started by designing the database schema for the organ donation
system.
● We then identified the main entities involved, such as donors, recipients,admins,
and organ types.
● We defined the attributes for each entity, such as donor ID, name, address, blood
group, and contact information as well as organ specific information.
● In this project, we have built a many to many relationship set “donor_receiver”
consisting of donor_basic and receiver_basic entity sets having attributes.
● This management system consists of 4 organs :- pancreas,cornea,liver,kidney
● There exists a “ISA” (specialization/generalization) relationship between
donor_basic and donor specific organs and similarly between receiver_basic and
receiver_specific organs entity set.

3. Database Creation:
● The project was developed using MySQL database requirements.
● The necessary SQL statements to create tables for each entity, define primary
and foreign keys, and establish relationships between tables were developed
● We ensured proper normalization to eliminate redundancy and maintain data
integrity.

4. Data Population:
● We populated the database with sample data to test the functionality of the
system.
● Added entries for donors, recipients, hospitals, and other relevant entities.
● Included various scenarios to cover different aspects of organ donation, such as
different organ types, matching criteria, and transplant history.
● This data will allow us to evaluate the system's performance and simulate
real-world scenarios.

5. Graphical User Interface:
● To develop a GUI for organ donation management system, Python programming
language along with StreamLit web based framework is used.
● The user interface provides functionality for tasks such as adding new
donors/recipients, updating their information, searching for potential matches,
and tracking transplant history.


6. Functionality Implementation:
● Using PL/SQL queries along with aggregate functions to interact with the
database, retrieve, manipulate data, and perform all the required operations of
this system efficiently.
● For example, writing queries to register a new donor, update donor information,
search for compatible recipients based on matching criteria (such as blood group
and organ type), and record transplant details.


7. Testing and Validation:
● Thoroughly tested the system to ensure its functionality and usability.
● Tested different scenarios and inputs to verify the system's accuracy and
performance.
● We validated the system against the requirements and made the necessary
changes.

8. Future scope
● Removing redundancy in the tables by allowing a user to receive and/or donate
multiple organs on a single user ID
● Designing the GUI in a way that allows user to shift frames
● Incorporating other organ’s donations as well
● Trying to design systems managing various aspects of medical healthcare
