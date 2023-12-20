# PP1

Photography website for code institute pp1

12/12/2023
Deciding to make a photography Website with a Gallery, About and a contact section I will be using HTML CSS and Balsamiq for the wireframe, I have constructed a basic wireframe using balsamiq to get the basic format in I have included these in the "read-me-docs"

included CDN for font awesome, added placeholder for logo. Trying to insert background image i think I have the right CSS but it's not showing not sure if its to do with file size and loading times. going to look into this more.

added footer links for social media.

13/12/2023

started to work on the styling fixed the broken links, had the text not in the <a> tags also fixed styling for css. noticed i hadn't put the direct file path in.
added border radius to nav links to make it look more appealing still figuring out how to make the nav bar not take the full top header, tried positioning etc. still figuring out.

managed to get the nav bar looking somewhat relative to my wireframe still currently working on the styling going to be adding in the footer soon, feeling overwhelmed with the nav bar.

worked on hero-text and positioned it into the middle of the page.

working on styling footer to have text items go from left to right instead of a list

managed to add my background image to the webpage I was using the wrong file path should have been ../ and not url() positioning is still a bit off so going to work on that

managed to make background color a bit darker using code from chat gpt code ( body::before {
content: "";
position: absolute;
top: 0;
right: 0;
bottom: 0;
left: 0;
background: rgba(0, 0, 0, 0.5);
z-index: -1;
})

14/12/2023

Had to move back to code anywhere because of gitpod.io limit

imported google fonts link and removed background color from nav bar and added a border.

managed to hide the scroll bar with the overflow:hidden on my background image
removed the text decoration from gallery text and added about page, going to change the design for about and add a packages section and about me section about photographer.

added a contact form still need to style.
also added more pages and set the action of the form to "mail to" still having trouble with codeanywhere being slow.

Still working on basic structure getting everything positioned and then will begin styling.

The objective of the webpage is to get more bookings and advertise the photographers work.

To do this im creating a website including a gallery and a contact form also an about section to get to know the photographer.

the functional specs and content required will be a contact form requiring name and email and a short message.

Im also considering adding different package options to the form which will be seperated into Headshots, landscape and weddings, I will include a radio form in my contact form to achieve this

15/12/2023

moving onto styling the form want to acheieve a vertical form its proving troublesome at the moment looking for different options on the css

borrowed some code from chat.gpt for the form here is the original code ive modified it to fit my webpage but was a good base to use

.form label {
display: block;
margin-bottom: 8px;
}

    .form input,
    .form textarea {
        width: 100%;
        padding: 8px;
        box-sizing: border-box;
        margin-bottom: 16px;
    }

    .form button {
        padding: 10px;
    }

removed " .form input,
.form textarea {
width: 100%;
padding: 8px;
box-sizing: border-box;
margin-bottom: 16px;
}

    .form button {
        padding: 10px;
    }

didnt like the styling of the default form.

added padding to the contact form and position to make it look more visually appealing with a border radius of 5% to make the corners more rounded and fit the aestethic of the webpage

changed the background color of the footer to match the visual of the website and changed the padding value so its not suffocating the page
added a message on the side of the contact form, also changed the padding and sizing for the message text
fixed background image changing on different page using "background attachment fixed" found this line of code on
https://www.w3schools.com/cssref/pr_background-position.php

changed the fontsize added padding and changed the colour of the text for the form
changed the padding of the nav bar to 1px also made the width 90%

removed the margin from the nav and flex end changed width to 50%
changed position of nav bar to be in the center may add margin back
added overflow hidden so the hover peusdo class doesnt overlap the bar

changed footer paddding to 1px

going to work on the gallery next and add a scrolling gallery maybe with an option to see the bigger photo with the target \_blank attribute maybe

17/12/2023

opened website on new device so need to sort out the resizing styling in css will achieve this with @media queries if this method doesnt work i will use bootstrap columns maybe but im sure that will involve in changing all columns in the workspace.

18/12/2023
added viewport height and width onto body elements its worked somewhat but there are still errors so need to work on resolving these

19/12/2023
still having problems with the footer, tried absolute, static and relative positioning to no avail, think it might be something to do with the div placement or lack of.
Hoping all these reps are going to git hub recently transferred onto vscode and noticing some little bits missing.

fixed the footer on the index.html page decided to add a div outside the footer then gave it a class name of .footer-container and changed the styling on the css to make it positioned at the bottom and stretched out with inline block.
