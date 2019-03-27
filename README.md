#  monkees-project
A fully responsive, mobile-friendly static website.


## UX

The website built for the fans of The Monkees band. Fans can view their photos videos and listen to their music. They also can sign up to their newsletter, and there is a form to contact the band. They can follow the social media links to view the band's Facebook, Twitter and Instagram posts.

The website is really straightforward, the user can find everything in one click.

## User stories:

## User A wants to view the band's videos. 
 - Landing on the home page, A will see the gallery button, and on the gallery page will find the videos.

## User B wants to see the latest posts on Twitter.
Every pages footer contains the social media links with their logo, so B needs to click on the Twitter link and it will navigate to the band's Twitter page.

## User C wants to sign up to the band's newsletter.
 - Every page contains the link at the footer of the page, so C needs to click on the link and it will open a modal where C needs to type in his/her name and email address to sign up, when it is done, C needs to click on the sign up button and then will gets a message to confirm the sign up was successful.

## User D wants to hire the band.
 - Every page contains two links to the hire us form page. One located on the footer next to the sign up link, the other is on the navbar hire us button.
 - D needs to click on the hire us link and then fill in the form. 
 - After click on the send button if all field filled, get a message sent message. If there is an empty field the user gets a warning that every field required.

 ## User E wants to go back to the home page.
 - User needs to click on the home button or the picture of the band.

## The strategy, scope, skeleton planes are located in assets/user-design-experience folder.

# Features

## Header:
- Picture of the band works as a link to the Home page The 'The Monkees' logo comes up only on tablets or desktops (above 767px width). Navbar with hover on effects and navigation buttons with different colour and icons.
   
## Main content:

 - Same background colour as the navigation button.
 -     Home:
        Give a description of the website and where the particular content can be found.
  -    News:
        The latest news about the band events
     - Gallery:
        Contains videos, pictures and audio files.
        The video and audio files can be played on the website.
     - Hire Us:
        Contains a form to contact the band.
       - -  After submitting the form: There is a basic validation to check if there is any empty field and check if the email address contains @ symbol.
       - -  If there is no empty field, 'message sent' message let the user know that the message sent.
 - The message is not sent to anyone and the message is not saved.

## Footer:
  -   The footer contains 5 links:
        Three navigate from the page to the social media pages, currently no link set on them.
        One brings the user to the hire us page.
        One opens up a modal to subscribe with a name and email address to a newsletter. When the user clicks on the sign up button the modal closes and another modal opens up to let the user know signed up successfully.
 - There is no action that happens after.
       
## Features left to implement

 - There is no back-end procedure after the user submit a form.
 - Maybe an online shop page in the future would be good.
   
## Technologies used
- HTML5 
- CSS3
- [Google fonts](https://fonts.google.com/)
    To load the fonts used on the website.
- [Font Awsome](https://fontawesome.com/)
    To load icons used on navbar and footer.
- [Bootstrap](https://getbootstrap.com/)
    Component library, e.g. grid system.
- [Jquery](https://jquery.com/)
- [Javascript](https://www.javascript.com/)
    Used some code for the validation method at the form.
- [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools/)
    For testing, to fix bugs.
- [Mozilla Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools)
    For testing, to fix bugs.
- [VS Code](https://code.visualstudio.com/)
- Bash
- [GitHub](https://github.com/)

## Deployment

Website was coded in VSCode IDE, with a local folder. On Github I created a new repository called monkees-project. 
to deploy the files to the repository i used the following bash commands:
 - echo "# monkees-project" >> README.md
 - git init
 - git add README.md
 - git commit -m "first commit"
 - git remote add origin https://github.com/varroz56/monkees-project.io
 - git push -u origin master

After uploading the files to GITHUB repositories I choosed a master branch to be online from GITHUB Pages.
 The website can be found at: https://varroz56.github.io/monkees-project/


## Testing

Each page was tested locally and on GITHUB pages using Chrome and Mozilla developer tools, testing its functionality as well as look and feel (in landscape and portrait mode) on Nexus 5S, Nexus 6P, iPhone 7, iPhone 7 Plus, iPhone 8, iPhone 8 Plus, iPhone X, iPad, iPad Pro, Galaxy Note 8, Mi Mix 2 and responsive desktop, also on Ms Edge, Firefox, Opera, and Chrome platforms. All links were tested along with music tracks audio controls and video player. 
The modal join fan club form and the hire us form was tested locally and remotely.

Got positive feedback from friends and other students on slack.

## Credits
Work based on other code

I chose to build the offered Monkees project, had inspiration from the Resume project for the layout.

For the form validation I used a [javascript code](https://github.com/twbs/bootstrap/issues/26271) shared on github and stackoveflow.

For the modal I used the bootstrap modal edited version.

## What changed after user design experience (UDX) phase
I have changed the initial font-family to an easy-to-read Roboto and Ubuntu

 	
	
	
