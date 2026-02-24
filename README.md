Job Application Tracker

This is my Assignment 4 project. I built a simple website where we can track job applications. We can mark jobs as Interviewed or Rejected and see the total count on the dashboard. 

Live Link
(Add your live site link here)

GitHub Link
(Add your GitHub repository link here)

Technologies I Used
•	HTML
•	Tailwind CSS & DaisyUI
•	JavaScript (Vanilla)

What This Project Does
•	Shows total jobs, interviewed jobs, and rejected jobs.
•	Has three buttons: All, Interviewed, Rejected.
•	Shows minimum 8 job cards.

•	Each card shows:
  o	Company name
  o	Position
  o	Location
  o	Job type
  o	Salary
  o	Description

Each card has:
  o	Interviewed button
  o	Rejected button
  o	Delete button

When I click:
Interviewed → The job moves to Interview tab and count increases.
Rejected → The job moves to Rejected tab and count increases.
Delete → The job is removed and the count decreases.
If no jobs are available in a tab, it shows a message.

Frequently Asked Questions (FAQs)
1.	Difference between getElementById, getElementsByClassName, querySelector, querySelectorAll
    •	getElementById() selects one element using id.
    •	getElementsByClassName() selects many elements using class.
    •	querySelector() selects the first matching element.
    •	querySelectorAll() selects all matching elements.

2.	How to create and insert an element?
    •	First create: const div = document.createElement("div");
    •	Add text: div.innerText = "Hello";
    •	Insert it:document.body.appendChild(div);

3.	What is Event Bubbling?
    When we click on a child element, the event also goes to the parent element.
    This is called event bubbling.

4.	What is Event Delegation?
    Instead of adding event to many elements, we add one event to the parent element.
    It makes the code simple and cleaner.

5.	Difference between preventDefault() and stopPropagation()
    •	preventDefault() stops default browser behavior.
    •	stopPropagation() stops the event from going to parent.

What I Learned
  •	How to work with DOM
  •	How to change data using JavaScript
•	How to update UI dynamically
•	How to use Tailwind and DaisyUI
