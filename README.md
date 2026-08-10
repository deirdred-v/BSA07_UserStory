# User Stories

Summary:
Studing User Stories (US), understanding their benefits, learning how to create them and their associated acceptance criteria and test scenarios. And also discussing user stories with others involved in the development process.

## Contents

1. [Chapter I](#chapter-i) \
   1.1. [Task 1. Haircut Appointment](#41) \
   1.2. [Task 2. Delivery of Orders)](#42)
2. [Chapter II](#chapter-i) \
   2.1. [Exercise 00 — Description of User Stories](#51) \
   2.2. [Exercise 01 — Description of User Stories](#52) \
   2.3. [Exercise 02 — User Stories Coordination](#53)

## Chapter I <div id="chapter-i"></div>

### Description of tasks

### Task 1. Haircut Appointment <div id="41"></div>

The management of a chain of barbershops decided to implement an online booking system. The main objective is to develop the business by expanding the customer base through the possibility of online registration, as well as to reduce employee labour costs and manual labour by automatically informing customers through communication channels. 

Both registered and unregistered visitors can book an appointment on the website. When making an appointment, they can select the type of service: hairdressing or cosmetology, as well as the service itself, the master and the time from the available intervals. The system should provide automatic sending of reminders to clients through the communication channel chosen by the client (Telegram, WhatsApp, VK, SMS) according to the schedule set by the manager. After receiving a service, the system offers the client to evaluate the service and write suggestions on how to improve the work.

The schedule of masters and the services provided by each master should be entered by the manager, who may be more than one person. This person is also responsible for keeping the schedule up to date and adjusting it if necessary, communicating with customers manually, marking the service, charging and accepting payment, sending the payment data to the accounting department. The manager can also receive reports on completed services and view customer feedback.

Each master has the ability to view the schedule and appointments for their services, as well as customer reviews.

### Task 2. Delivery of Orders <div id="42"></div>

During the lockdown, many grocery stores and food companies dramatically increased their online sales and the need for quick delivery of small quantities to individual customers increased. 

A group of students got together and decided to create a delivery service startup. The idea is to quickly receive information about orders, pickup location and time, delivery location, desired delivery dates, and distribute this information to couriers who will pick up the order at the pickup location and deliver it to the delivery location. They decided to develop an online system where orders could be collected and quickly sorted for delivery by couriers.

The first step was to collect orders from stores and caterers in any way possible and have the operator enter them into the system in a consistent format, as well as developing a mobile application for the courier. The courier should be able to view order information, select an order from those available, book it, pick it up at the collection point and deliver it to the customer. The result of the courier's actions should be immediately reflected in the system via a mobile application. The system should also include a dispatcher who controls the couriers and reassigns orders if necessary. Information on received orders should be sent to the accounting department (to another IT system) to calculate delivery charges with order suppliers. Order delivery information should also be sent to the accounting department to calculate payment to couriers. Accrued payment should be transferred to the system and displayed in the courier's personal account. And there should also be an administrator's workstation, where couriers are registered and access rights are assigned to all of them.

## Chapter II <div id="chapter-ii"></div>

### Exercise 00 — Description of User Stories <div id="51"></div>

Create at least 2 US for a manager for task 1:

1. Define at least two of the manager's needs in our system.
2. Write a US for each need:
   1. specify the US identifier;
   2. specify the US header — an active verb expression of the user's goal;
   3. describe US:
      1. specify the user role, 
      2. specify the benefit (value) to the role,
      3. specify the required action(s).
3. Develop acceptance criteria for one of the US, describe:
   1. precondition — the circumstances, the role of the user;
   2. actions performed by the user in the system;
   3. result — value to the user.
4. Develop a test scenario for the second US, describe:
   1. preconditions: on what data to check, what settings, what actions should precede;
   2. actions: what should be done by the user and the system;
   3. expected result: what will confirm the correctness of the execution.
5. Indicate your answers in the file ex00\_<product prefix>\_us\_<role>.docx.

### Exercise 01 — User Stories Coordination <div id="52"></div>

Create at least 4 more US's for task 1.

1. Select two roles other than manager in task 1.
2. Identify at least two needs for each role in our system.
3. Describe the US for each need by applying the requirements of paragraph 2 ex.00.
4. Describe the acceptance criteria for each selected role, one US at a time, applying the requirements of paragraph 3 ex.00.
5. Describe a test scenario for each selected role applying the requirements of paragraph 4 ex.00.
6. Indicate your answers in the file ex01\_<product prefix>\_us\_<role>.docx.

### Exercise 02 — User Stories Coordination <div id="53"></div>

Discuss and agree on the US developed.

1. Find one or more people among your fellow students or friends with whom you can discuss US by playing the roles of "user", "customer", "developer" one by one or together. 
2. During the discussion, make sure that the conditions of 3 Cs are met:
   1. Card: if the US doesn't fit enough, then split it into two or more or rework the US differently;
   2. Conversation: Discuss each of the US with each role. Refine the US if necessary;
   3. Confirmation: as a result of discussion and refinement, harmonize US with each role;
   4. Write a minutes of the discussion, specify:
      1. Who participated in the discussion;
      2. What role they played;
      3. What changes have been made to the US;
      4. Reasons for the changes.
3. When discussing check the three characteristics of INVEST:
   1. independence of each US; if there is a dependency — make them independent. If not — specify the dependency: which US depends on which (this will be needed for prioritization — in what order to implement US, in what order to check);
   2. negotiability of each US: whether it was discussed with "user", "customer", "developer" — indicate what conclusions were reached;
   3. value — confirm that the business value of each US is understood; if the business value is not understood, it is a reason to enlarge the US or rework it.
4. Identify each change, explain the reason for the change, record it.
5. Indicate your answers in the file ex02\_<product prefix>\_us.docx.
