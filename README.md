#Bootstrap Knowledge Check Assignment

Overview:
The assignment was completed following the guidelines provided. The objective was to build a responsive webpage utilizing Bootstrap while demonstrating proficiency in fundamental web development concepts. I started by adding a Bootstrap CDN, a registration form, a responsive table, images, and a navigation bar. All while familiarizing myself with Git and GitHub to track changes, add repositories, and maintain commit logs to track my progress throughout the assignment.
Throughout the process, I encountered a few challenges and limitations, which will be discussed later in this document.

Part 0:
I started the assignment with a basic boilerplate and added a Bootstrap CSS framework using a CDN to the head element. I also pulled up previous exercises for reference, used appropriate areas as starter codes, and adjusted as necessary for the assignment.

Part 1: Form Creation and Layout:
-Responsive Registration Form
1.	First, I added a Container class within a div element and nested all other elements associated with the form. This centers all content within the associated Div.
1.	I added a field for First name, Last name, Email, and Password.
2.	I applied a Bootstrap grid layout using the div class="row” and nested 2 additional div elements with class=col-md-6 creating 2 equal columns that aligned both the first and last names next to each other on medium screens or larger.
3.	I added validation classes for email and password using the appropriate type.
4.	A button element was added and styled with Bootstraps="btn-success" to make the button green.
5.	All fields on the form are required.
6.	I applied spacing utilities i.e.: mb-2, pt-2 to add spacing between elements.

Part 2: Table for Displaying Data
-Responsive Table
1.	Below the form I added a table component and made it responsive to screen size by adding it to a div with class=” table-responsive”
2.	Added both striped (alternating colors) and hoverable (highlighted when hovered over) rows to the table.
3.	Added column titles using <th> elements nested within a <tr> element.
4.	Added hard coded user data within <td> elements nested within a <tr> element. This was applied to two rows.

Part 3: Image and Button Utilities
-responsive images with button utilities
1. Added a div with a container class of container-fluid to ensure images stretched the full width of the screen, but I did add padding to add some white space to the sides.
2. the first image was added with an img-fluid utility class to scale appropriately within the parent div element. The image also stretches across the parent container.
3. the second image was added with the utility class of rounded-circle to style in the shape of a circle. The image was centered using “text-center” within the parent div element.
4. 2 buttons were created with accompanying text. All content was centered on the page with <div class=” text-center” with the buttons nested inside.
5. One button is visible on all screens and the other becomes invisible on small screens using the utility classes of d-none and d-md-block. Buttons were styled with two different pre-defined Bootstrap colors.

Part 4: Navigation Bar:
-Responsive Navbar
1. A navbar was created using the nav element with navbar navbar-expand-md was added to show the full menu on medium-sized screens or larger while a hamburger menu appears on smaller screens. A fixed-top utility class was added to keep the navbar fixed to the top of the screen no matter how far you scroll down.
2. Home, About, and Contact sections were added using list items nested in a ul. No active links were added to the menu options indicated by the # sign.
4. A navbar button was added to enable the hamburger menu but is currently not functional. I looked online and found the button would be functional with JS, so that portion was omitted.
5. Created a div to make navbar items collapse on smaller screens using collapse navbar-collapse.
6. The navbar was styled using utility classes.

Opportunities and limitations:
1.	Initially I struggled to navigate the command line while using GIT and GitHub, particularly in understanding how to properly track changes.
2.	To remedy some mistakes, I looked up some commands online. However, I was left hopeless when I applied the git reset # --hard command causing me to lose my progress and erase my work before my eyes.
3.	I am interested in learning how to amend past commits without affecting more recent ones. My current workaround involves copying my existing code into a separate work pad to retain it in case I make a mistake again. Then I would rest my working directory to a previous commit, making necessary corrections, and then add the retained code on the notepad before committing again.

