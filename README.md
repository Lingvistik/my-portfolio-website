Emil’s Music Workshop

This is an imaginary website which was designed to provide music production services (original compositions, music backgrounds, sound FX) for various types of client’s needs. 

UX

This website was designed around the real idea of music production provided by myself which was based on my existing work, some of what can be heard in the portfolio section of the website.
The idea was to keep it as simple as possible and intuitive enough, in terms of navigating through the website and learning about the features.
Targeted audience for the website would be both businesses and private individuals, meaning the final products would for be for commercial or non-commercial use.
The offer is consisted of producing music from scratch or collaborating on an existing project or ideas as the name of the site is immediately suggesting so that anyone who needs music for their projects would get an idea of what to expect just by browsing through the website.

•	As a private individual, I want an original love song dedicated to my future wife, so that I can perform it at our wedding. – user example 1

•	As a professional radio DJ, I’m always in a search for good quality jingle that would complement different sections of my show. – user example 2

•	Our advertising company needs fresh and clever little musical pieces that would fit our TV or Radio commercials. – user example 3

•	Young gaming production company seeks composers and producers for collaboration on the new projects. – user example 4

•	As a theatre director I’m looking for high quality sound effects which I will use for my next play. – user example 5

Features

Existing Features

•	Feature Home Page - allows website users and potential clients to quickly access the contact section, by clicking “Let’s Work Together!” button.
•	Feature Work – allows users to listen to the musical examples which would give users image of what they can expect, by clicking on the images which then opens the audio/video players.
•	Feature Testimonials carousel – shows users stories on an automated sequence and can be controlled by clicking on left/right arrow.
•	Feature Contact – allows user to get in touch with the author

There are several features that would be implemented over the period of time and as will project get bigger more of the features will be introduced subsequently. 

Features Left to Implement

•	An automated mastering tool that can be used unlimitedly allowing users to upload their existing audio files which would then be processed by built-in software after which would user download finished copies that fit the standards of the music industry
•	A forum page which would serve as user community place where users would share their experiences and stories, discussing the potential collaborations, etc.


Technologies Used

This website was built around the layout provided by the Bootstrap libraries which were used for the basic grid setup that served as a skeleton for the interface design.
Languages used for the website were HTML and CSS.
The Carousel plugin was taken from the Bootstrap library of components and modified to fit the desired effect. 

Libraries used for the project
•	Bootstrap
•	Font Awesome
•	Google Fonts

Testing

As the website was built with the mobile first approach in mind I would always view any new feature on the mobile device view first using the Chrome’s inspect utility. 
If appearance of any particular page on the site wasn’t optimized for the mobile devices browsing, I would use media queries outside of what was already built in the Bootstrap’s library.
For instance on mobile view I’ve hidden part of the text that appears when hovered or clicked on the Home page image. I have also changed how dropdown menu behaves on mobile view where it pushes the content of the page below the dropdown menu, while on the desktop view dropdown menu overlays the content.
Text carousel has also been adjusted for the mobile view via media query where the font size has been reduced to fit the smaller screen devices.

TESTING the Features

Navbar feature
    Desktop view
1.	Click on the Navbar button and verify that that dropdown menu appears overlaying the page content
2.	Hover on the dropdown items and verify that it changes background color
3.	Cick on the dropdown items and verify that it changes the font color
    Mobile view
1.	Click on the Navbar button and verify that that dropdown menu appears pushing the page content down
2.	Cick on the dropdown items and verify that it changes the background and font color

Home page main contact feature:
1.	Go to the “Home” page via navbar or clicking on the logo positioned left on the site
2.	Hover on the main image and verify that text appears 
3.	Hover on the “Let’s Work Together!” button and verify that it changes background and font color
4.	Click on “Let’s Work Together!” button and verify that it leads to the Contact page

Work section - portfolio:
1.	Go to the "Work" page via navbar
2.	Hover on the images and verify that text on the images changes font color
3.	Click on images and verify that they open appropriate player
4.	Click on play and verify that it reproduces audio/video files

Work section - testimonials:
1.	Go to the "Work" page via navbar
2.	Click on the left/right arrow and verify that different user experience are showed

Contact form:
1.	Go to the "Contact" page via navbar, footer icon or home page’s “Let’s Work Together!” button
2.	Try to submit the empty form and verify that an error message about the required fields appears
3.	Try to submit the empty list form and verify that an error message about the required list items appears
4.	Click on the list form and verify that it shows different list items
5.	Try to submit the form with an invalid email address and verify that a relevant error message appears


Deployment

All the code has been written on GitPod Workspace and was saved (committed) on my GitHub repository. 
As the website was building, different versions have been committed to the GitHub repository in order to prevent any potential work loss.


Credits

Content
•	For a simple mp3 player used in the Work section
https://www.youtube.com/watch?v=M2qehZrWVfc
•	Div positioning
https://www.freecodecamp.org/news/how-to-center-things-with-style-in-css-dc87b7542689/
•	Hover effect used on the Home page, adjustments to the code have been made in order to create desired effect.
https://miketricking.github.io/bootstrap-image-hover/
•	carousel text, adjustments to the code have been made, media query set for the mobile phone devices
https://codepen.io/Washable/pen/Oxqjbq?editors=1100
•	text over image, adjustments to the code have been made, used for the images on the Work section
https://www.w3schools.com/howto/howto_css_image_text.asp

Media
•	Cover image is an original art by my wife Ardena Vuckovic-Bacic
•	Electronic music img
https://www.piqsels.com/en/public-domain-photo-fvbek
•	Recording img
https://www.pxfuel.com/en/free-photo-oecaa
•	World music img
https://www.flickr.com/photos/87251943@N05/7991501908
•	video games music img
https://www.flickr.com/photos/shardsofblue/5609066215/sizes/m/
•	Home page img
https://www.piqsels.com/en/public-domain-photo-svaqy

Acknowledgements
•	I received inspiration for this project from the Course lessons provided by Code Institute
•	Additional inspiration I received in a form of feedback from my friends and family
