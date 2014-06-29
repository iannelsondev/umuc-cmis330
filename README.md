umuc-cmis330
============

Course work for UMUC CMIS330 - Software Engineering
# DO NOT STEAL MY CODE! DO YOUR OWN WORK!

SRS
Instructions     
Scenario

You have been asked to lead a software development team to build a system fulfilling the Statement of Need below. Your team is employed by a small company. The customer wants a project that balances reasonable development cost, timely delivery, software quality, and functionality.

 

 In this project, you will perform preliminary system engineering and create an analysis model for this system. (See Module 3, Figure 3.1 of the course module commentaries for an overview of the elements of an analysis model). Completing this project will require that you do the following:

 Develop initial notes of the structure/functionality of the system.
 Produce an initial system specification document for the system.
 Develop a detailed scenario based model by writing use cases and develop an activity diagram.
 Create a behavioral model that identifies events with a use case
  

  Completing this project will require that you produce a software requirements specification (SRS) document for the system The SRS that you create will be a combination of the System Specification (SS) and the SRS; your SRS must include the essential components of the SS in the SRS.

   

   Your SRS will provide the foundation for Projects 2 through 4, so it must:

   Describe the customer requirements
   Establish the basis for software design
   Be testable, flexible, and traceable.
    

     Statement of Need

     John and Jane are starting a bed-and-breakfast (B&B) in a small New England town. They will have three bedrooms for guests. They want a system to manage the reservations and to monitor expenses and profits. When a potential customer calls for a reservation, they will check the calendar, and if there is a vacancy, they will enter the customer name, address, and phone number, dates, agreed upon price, credit card number, and room numbers. Reservations must be guaranteed by 1 day’s payment. Reservations will be held without guarantee for an agreed upon time. If not guaranteed by that date, the reservation will be dropped.

      

       SRS Template

       Please use the IEEE template to develop your SRS. The IEEE Std 830-1998: IEEE recommended practice for software requirements specifications is posted in the Reserved Readings section on the Class Menu. The entire outline for the SRS is provided in section 5, Figure 1.  Familiarize yourself with the type of information and diagrams to be provided in a SRS.

       You may follow either of two paths; Structured Analysis/Design (SSA/D) methodology (i.e. organize your requirements by functional hierarchy) or Object-Oriented Analysis/Design (OOA/D) methodology (i.e. organize your requirements by objects). The contents of your SRS will be somewhat dependent upon this choice.
       Look at the IEEE Standard 830 - 1998 Annex A. Annex A has suggested formats for your SRS. If you are following the SSA/D methodology, use template A.7. For OOA/D, use A.4.
       Template A.4 allows you to organize your requirements by objects. For example, objects in a patient monitoring system include patients, sensors, nurses, physicians, medicines, etc. Each object has a set of attributes and each object performs a set of functions, services, methods, or processes. Note that objects may share attributes and services that can be grouped together as classes.
       Template A.7 allows to organize your requirements into a hierarchy of functions organized by either common inputs, common outputs, or common internal data access. You will then use Data Flow Diagrams (DFDs) and data dictionaries to show the relationships between and among the functions and data.
        

        Note: Whatever your choice, you must address and write section 3 of the template (figure 1) to successfully address the requirements for project 1. For additional context please see the SyRS Outline and the Outline Explanation depicted in Annex A of the IEEE Std 1233-1998: IEEE Guide for Developing System Requirements Specification. You can use this to further inform and flesh out the development of your A.4 or A.7 template as appropriate.

         

         Make any reasonable assumptions based on your understanding of the problem that allow you to address as many sections of your chosen SRS template as possible. I do not expect, or require, that you completely address all sections of the template. However, your SRS must address, and be built around, the required deliverables specified below. (You must incorporate the below requirements into the appropriate sections of your SRS).

          

           The assignment

           (4 points) Demonstrate your understanding of the customer’s statement of need by producing a preliminary documentation of the structure/functionality of John and Jane’s B&B. (This is how you shall include the essential components of an SS into your SRS). The basic objective here is to address the question “What is this system supposed to do”?
           Identify, describe, and arrange in a structured manner, the features the system must have and the functions it must perform to satisfy John and Jane’s expressed need. Identify the expected performance and any anticipated constraints of the system. Much of this information should fit into the introductory and system functionality/description sections of the SRS. (See sections 5.1.1 (Purpose) and 5.1.2 (Scope) of the IEEE standard 830-1998). Note that sections 5.1.1 and 5.1.2 provide guidance on how to complete sections 1.1 and 1.2 of the SRS outline shown in figure 1.
            

            (16 points) Pay special attention to the following required deliverables on which the bulk of your grade will be decided. (Please read the “project descriptions” in the project description section of the syllabus for additional context and information on course projects).
            Produce an architectural context diagram (ACD) for the B&B. An ACD models how the system interacts with external entities (See the ACD template posted in the Projects conference; also see Module 1, Figure 1.5 of the course module commentary).
            Produce a context-level (Level 0) Data Flow Diagram (DFD) for the B&B. The context level 0 DFD focuses on the flow of data through a system. (See Module 2, Figure 2.7 of the course module commentaries for an example of a context diagram).
            Refine your DFD to level 1. (See Module 3, Figure 3.4 of the course module commentaries for an example of Level 1 and Level 2 DFDs). It may also be necessary to include process specifications to ensure that your DFD is defined to the lowest possible specification for design. If you prefer an object-oriented approach, you may supplement your use cases by using an activity diagramto depict the flow of interaction within a specific scenario.
            The level 0 and Level 1 DFDs depict the basic components of the IT system you will develop and its internal and external interfaces.
            Produce a class diagram, or an Entity Relationship Diagram (ERD) of the B&B to describe your system’s data and its interrelationships. (See Module 2, Figure 2.8 of the course module commentaries for an example of a class diagram).
            A class diagram models the objects that the system will manipulate and the operations that that will be applied to the data objects. You want to ensure that it properly supports your use cases and DFDs by capturing the attributes and behaviors of the objects that the system users (actors) must manipulate as they interact with the system and/or perform the operations implied by the functions/processes in your DFDs.
            Identify the customers, users, and other stakeholders of the B&B system. (See Module 2, Figure 2.1 of the course module 2 commentaries for how defining the users help in eliciting requirements for a system). Produce a use case diagram for B&B (See Module 2, Figure 2.6 and Table 2.2 of the course module commentaries for examples of use cases and use case diagrams). Use the module 2, Table 2.3 of the course module commentaries to develop (at least two) scenarios for the system.
            Produce a state diagram for the B&B. (See Module 3, Figure 3.5 of the course module commentaries for an example state transition diagram).
             

             See Module 1, Table 1.1 of course module commentaries for some guidance on how to incorporate the above diagrams into your SRS.
