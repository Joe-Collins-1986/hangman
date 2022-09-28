To Do:
1. add subheadings to TOC
2. proof readme doc
3. spacing between sections

5. 
6. check an ansered errros with mentor including "Error with Permissions-Policy header: Origin trial controlled feature not enabled: 'interest-cohort'."
7. 
8. 
9. remove console log
10. tidy js

# Table Of Contents
- [Hangman Website Overview](#hangman-website-overview)
- [Responsive Review](#responsive-review)
- [User Experience (UX)](#user-experience-ux)
- [Further Development](#further-development)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Depolyment](#deployment)
- [Credits](#credits)

<br>


# Hangman Website Overview
   ## Live project [*(link to live project)*](https://joe-collins-1986.github.io/Hangman/)

   (**Note:** this is a fictitious client generated for the purpose of developing this project to test my HTML, CSS and javascript essentials.)

   This website has been designed to provide users with simple yet fun Hangman game to play when bored. It hs been created with a number of different topics whch can be accessed via the the settings section of the website.

   The client requesting this webite is using this as the first step in creating a site that will house a number of games and puzzles which he will later look to monitize through the use of advertisements.

   <br>


# Responsive Review

   ## Am I Responsive? [*(link to repsonsive review website)*](https://ui.dev/amiresponsive?url=https://joe-collins-1986.github.io/Hangman/)
   ![Responsive Review](assets/readme-assets/responsive-review/hangmanResponsiveReview.png)
   
   <br>

# User Experience (UX)

   ## Website Objectives

   <details>
      <summary style="font-weight:bold">Client Goals</summary>

   The client wants a simple and engaging game that is easy to use and will result in users returning to the site. 
   * Sleek yet simple UX design.
   * Easy to use functionality.
   * Responsive for any device size to encourage mobile use as well as desktop use.
   * Links to the client's social network accounts to enhance their online presence.
   * Addictive gameplay to encourage return clients and drive positive word of mouth to encourage new users.
   
   ---
   </details>

   <details>
      <summary style="font-weight:bold">Client Future Goals</summary>
   
   Points to consider for future development:
   * Additional words and topics to be added to the hangman game.
   * Allow for scores to be recorded and stored into a leader board.
   * Additional games and puzzles added to the site.
   * Generate advertisement revenue through the site.

   ---
   </details>

   <details>
      <summary style="font-weight:bold">First-Time Visitor Goals</summary>

   * Immediately engaged by the UX design.
   * Understand the purpose of the site.
   * Simple intuitive menu navigation.
   * Intuitive content and links to social media.
   * Readable and aesthetically pleasing on all devices.

   ---
   </details>

   <details>
      <summary style="font-weight:bold">Returning Visitor Goals</summary>
   
   * Revisit to replay game to try different topics.
   * Revisit to replay game to beat previous score.
   * Revisit to locate social media links to client.

   ---
   </details>

   <br>

   ## Website Design

  <details>
      <summary style="font-weight:bold">Colour Scheme</summary>

   Client wished the game to feel as though it was written on a piece of paper. Therefore main colours where kept simple with black and white.
   - Main colours: 
      - #000000 (Black)
      - #FFFFFF (White)

   To add a bit of simple colour to the main page margin lines gernerated through repeating linear gradients used some lighter colours found of papper note pads.
   - Margin lines on page:
      - #ffc0cb (Pink) (This colour will also to be used in for the required button hover animation to keep deisgn consitancy) 
      - #9198E5 (Maximum Blue Purple)

   To make sure the menu content stands out this will be set in a new colour. This will be set it a light yellow to mirror a post-it note
   - Menu colour:
      - #E7E773 (Straw) (This colour will be tweaked slightly using linear gradients to give a more real, 3d faded effect.) 


   ![Colour Palette](assets/readme-assets/design/hangman-colours.png)

   ---
   </details>

   <details>
      <summary style="font-weight:bold">Typography</summary>

   For the typography the client wanted an easy to read text which looked handwritten. The ballance was to locate a font that gave this impression whilst still being clearly legible even on a small screen.
   - Font applied with backup options: 'Handlee', cursive, sans-serif

   ---
   </details>

   <details>
      <summary style="font-weight:bold">Imagery</summary>

   The images used for development of this website were taken from Unsplash and Font Awesome. These were selected to be minimalist and not detract from the main content wich was styled through CSS to meet the clients specifications.
   - Image for the backgound wood effect (jon-moore-5fIoyoKlz7A-unsplash.jpg).
   - Image of the mountain doodle which shows on large screen viewings (nicolas-pinilla-GcDr6ZIzbIw-unsplash.jpg).
   - Pins and paperclips where edited in photoshop from unsplash images.
   - the flavicon icon presented on the web tab was taken from Font Awesome (f43c).

   ---
   </details>

   <details>
      <summary style="font-weight:bold">Audio</summary>

   Audio was selected on this project to enhance the user experience but as per best practice guidelines was defaulted to mute> This can be toggled on via the settings menu. <br>
   The audio was selected from youtube clips which provided provided agreement for free usage. In several instances the audio clips where modified using Audacity to shorten them or remove background noise.
   - Backgound music (opted not to apply this as it was likely to become menotonous and there would have been licencing issues to obtaining engaging music tracks).
   - Sound on correct answer (https://www.youtube.com/watch?v=403gX7TnhTQ)
   - Sound on incorrect answer (https://www.youtube.com/watch?v=RZEsfS1rGyY) - modified using Audacity
   - Sound on getting word correct (https://www.youtube.com/watch?v=ytjxf9YNJ-0) - modified using Audacity
   - Sound on getting word correct (https://www.youtube.com/watch?v=na-a3lLB13Q&t=16s) - modified using Audacity

   ---
   </details>

   <br>

   ## Structure Non-Linear Plane
   The entire website will be housed on a single index page. The menu navigation, change of topics and win/lose outcomes will be facilitated through the use of javascript animating relevent sections.

   <br>

   ## Wireframes

   - [Skeleton Plane](https://www.figma.com/file/a9GzO1BVIhSaGTQPYAINzx/hangman-wireframe-(Skeleton)?node-id=0%3A1)

   - [Surface Plane](https://www.figma.com/file/9w1TswEvWfI4N8Fek3Gocf/hangman-wireframe?node-id=0%3A1)

   **Note:** The structure and wireframes are only to act as a concept and are subject to change as the website development evolves in collaboration with the client.

   <br>

   ## Features


   ![Feature Mind Map](assets/readme-assets/features/mindmap%20-%20hangman.png)
   The above provides an inital mind map into what features might be appropriate for the website given the clients specifications.

   ### **Features Breakdown**

   Each section below will detail their specific function.
   

   <details>
      <summary style="font-weight:bold">Random Word</summary>
   <br>

   #### Random word selected form list
   There will be 3 lists in this game:

   1. animals
   2. cars
   3. countries
   
   Dependant on the topic selected the reandom word will be taken form the appropriate list. 
   
   If the user selects play again the word will be removed from the list so that it can not be duplicated.
   <br>

   ---

   </details>

   <details>
         <summary style="font-weight:bold">Present Word</summary>
   <br>
   
   #### Empty Word
   At the commencement of the game there is a function to locate a random word from a list (dependent on topic selected) and present as underscores.

   ![Start of game](assets/readme-assets/features/present-word/blank-word.png)
   <br>

   ---

   #### Guessed Letter
   If the user's guess is in the randomly selected word the letter will appear as well as encouraging words on the screen.

   ![Start of game](assets/readme-assets/features/present-word/correct%20guess.png)
   <br>
   
   ---

   #### Guessed Incorrect Letter
   If the user's guess is not in the randomly selected word the underscore will remain as well words informing the user the answer is incorrect.
   
   It will also result in a hangman element being drawn and the potential winning score being reduced (this ill be explained in moore detail in the hangman and score functions section):

   ![Start of game](assets/readme-assets/features/present-word/incorrect%20guess.png)
   <br>
   
   ---
   </details>

   <details>
      <summary style="font-weight:bold">Select Letters</summary>
   <br>

   #### Letters selected are checked against word
   The letter selected will be checked agaist the randomised word to see if it appears. If it does it will run success outcomes if it does not it will run fail outcomes. It will also update the presented word on the screen to incorporate correctly guessed letters.
   <br>

   ---

   #### Letters fade after use
   After a letter is selected it will fade and be deaactivated.

   ![Start of game](assets/readme-assets/features/select-letters/faded-letters.png)
   <br>

   ---

   #### On game completion deactivate all letters
   After the game is won or lost no letter buttons will be active. This is to stop any further amendments tot he score. <br>
   The letters will not fade, they will just be deactivated.
   <br>

   ---

   </details>
 
   <details>
      <summary style="font-weight:bold">Hangman Drawing</summary>
   <br>

   #### Incorrect answers draw hangman element
   On incorrect guess a hangman element will be drawn. This is done using canvas in js.

   ![Start of game](assets/readme-assets/features/hangman-drawing/hangman-elements.png)
   <br>

   ---

   #### On game completion hangman section will be replaced with outcome
   The div holding the hangman image will also be used to detail if the user has won or lost on game completion.

   ![Start of game](assets/readme-assets/features/hangman-drawing/win.png)
   <br>

   ---
   ![Start of game](assets/readme-assets/features/hangman-drawing/lose.png)
   <br>

   If reset is selected the webpage will refresh which will reset all variable and the game will start again at a score of 0.

   If play again is selected the required variable will be resent in js leaving the score to accumulate.
   <br>

   ---

   </details>

   <details>
      <summary style="font-weight:bold">Rules</summary>
   <br>

   #### Rules held on index page
   The rules content will be kept on the same page at the rest of the web content. This is to ensure the score is retained as backend data storage is not in use for this project.

   A scroll feature was added to the rules to post-it to keep the sizing consistant.

   ![Start of game](assets/readme-assets/features/rules/rules-top.png)
   <br>

   ![Start of game](assets/readme-assets/features/rules/rules-bottom.png)
   <br>

   ---

   </details>

   <details>
      <summary style="font-weight:bold">Settings</summary>
   <br>

   #### Settings held on index page
   The settings content will be kept on the same page at the rest of the web content. This is to ensure the score is retained as backend data storage is not in use for this project.

   A scroll feature was added to the settings to post-it to keep the sizing consistant. This will only appear if required on small screens.

   ![Start of game](assets/readme-assets/features/settings/settings.png)
   <br>

   ---

   #### Allow change in topic
   Within settings it will be possible to change the topic. This will change the list the randomised word is selected from and will also present the currents topic onto the html page.

   (See screenshot above)
   <br>

   ---

   #### Allow change in topic
   Within settings it will be possible to toggle the audio on and off. As per best practice this will be set to mute as default.

   (See screenshot above)
   <br>

   ---

   </details>

   <details>
      <summary style="font-weight:bold">Score</summary>
   <br>

   #### Score increase
   Set to increase the score dependant on how many incorrect answers the user makes.

   Potential score starts at 10 each game and reduces by 1 for each incorrect letter guessed.

   ![Start of game](assets/readme-assets/features/score/increase%20score.png)
   <br>

   ---

   #### Score decrease
   If the user does not guess the word in 10 attempts then their score will reduce by 5 points. This has the potential to take the users overall score into a negative figure.

   ![Start of game](assets/readme-assets/features/score/lose-5-points.png)
   <br>

   ---

   #### Score accumulation
   If the user opts to play again their score will be retained from the previous games witht he new score being added.

   ![Start of game](assets/readme-assets/features/score/accumulate%20score.png)
   <br>

   ---

   </details>

   <details>
      <summary style="font-weight:bold">Social Media Links</summary>
   <br>

   #### Present links to social media platforms
   The links provided will take the user to the social media platforms but not to active accounts. This is because the client is fictional and does not have real accounts.

   ![Start of game](assets/readme-assets/features/social-media/social-media.png)

   </details>

   </details>
   <br>

# Further Development
   * Add additonal catagories to the hangman game.
   * Use web-scrapping to generate full word lists for future catagories.
   * Add optional timer to game.
   * Provide language options to game.
   * Retain scores using back-end development to provide a scoreboard for users.
   * Add additional games.
   * Add advertisements to site to generate revenue.
   
   <br>

# Technologies Used

   ## Languages Used

   - HTML
   - CSS
   - JavaScript

   ## Frameworks, Libraries & Programs Used

   1. Google Fonts:
      - Used to obtain appropriate fonts to use in website not held as standard.
   2. Font Awesome:
      - Used to obtain several icons used to improve the visuals of the website.
   3. Git:
      - Used for version control and to Push to GitHub.
   4. GitHub:
      - Used to store and share the code as well as publish to live website.
   6. Figma:
      - Used to plan out website format.
   7. Web Developer:
      - Used to analyse HTML, CSS and JavaScript output and correct where required.
   8. Canvas:
      - Used to draw the hangman on js.

   <br>

# Testing
   ## HTML Validator Results: 
   - [HTML index page](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fjoe-collins-1986.github.io%2FHangman%2F)

   <details>
      <summary style="font-weight:bold">HTML Issue Resolution</summary>

   ### Warnings
   Following the HTML validation the following warnings were identified and addressed.

   ![HTML Warnings](assets/readme-assets/Bugs/html/html-warinings.png)

   ---

   #### **Resolutions**
   **Points 1 - 2:**
   These were initially implemented as li items acting a menu option directing to additional content. However, removed aria-label following best practice due to no href.

   ---

   **Points 3 - 7:**
   All ID first occurrences were addressed by changing duplicate IDs to classes.

   ---

   **Points 8:**
   Placed empty quotes into h2 space to remove error. This header is produced by js.

   ---

   ### Errors
   Following the HTML validation the following errors were identified and addressed.

   ![HTML Warnings](assets/readme-assets/Bugs/html/html-errors.png)

   ---

   #### **Resolutions**
   **Point 1:**
   Delete stray div tag.

   ---

   **Points 2 - 6:**
   - Replace IDs with Classes and update CSS to .element as opposed to #element.
   - Checked ID was not used in js.
   - Removed duplicate class syntax e.g .class="settings-pin" class="pin-right". This was changed to class=”settings-pin pin-right”.

   ---

   **Points 7 - 10:**
   Mute is defaulted as true so no need to specify. Therefore reomoved = “true”.

   </details>
   
   ___

   <br>


   ## CSS Validator Results
   - [CSS validator results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjoe-collins-1986.github.io%2FHangman%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

   <details>
      <summary style="font-weight:bold">CSS Issue Resolution</summary>

   ### Warnings & Errors
   Following the CSS validation the following warnings and erros were identified and addressed.

   ![HTML Warnings](assets/readme-assets/Bugs/css/css-errors.png)

   ---

   **Points 1 - 2:**
   Removed unnessesary semi-colon.

   ---

   **Warining Provided:** 'Imported style sheets are not checked in direct input and file upload modes'.

   **Stack Overflow Response to Warning:** You're just trying to validate your CSS file using the W3C validator, and it's letting you know that it's not going to validate the imported style sheet (Google's). It's not an error, just some information for you.

   </details>

   ___

   <br>

   ## JS Validator Results
   ![JS validator results using https://beautifytools.com/javascript-validator.php](assets/readme-assets/validation/js-validation.png)

   <details>
      <summary style="font-weight:bold">JS Issue Resolution</summary>

   ### Errors
   Following the JS validation the following errors were identified and addressed.

   **Points - define variables:** <br>
   ![HTML Warnings](assets/readme-assets/Bugs/js/define%20variable.png)

   Errors resolved by declaring i in the relevent for loops.

   ---

   **Points - template literal syntax:** <br>
   ![HTML Warnings](assets/readme-assets/Bugs/js/esversion.png)

   Cause by use of Font Awsome. no detriment to usage. Site functioning as expected, left unresolved.

   ---

   **Points - functions declared within loops referencing an outer scoped variable:** <br>
   ![HTML Warnings](assets/readme-assets/Bugs/js/functions%20declared%20within%20loops.png)

   Utilising outer scoped variables. No issues caused by this and maintainance is acceptable so left unresolved.

   ---

   **Points - expected a conditional expression and instead saw an assignment.:** <br>
   ![HTML Warnings](assets/readme-assets/Bugs/js/conditional%20not%20assignment.png)

   Functions built with if statements, with no else option. No errors occuring as a result therefore left as is.

   ---

   **Points - level not defined.:** <br>
   ![HTML Warnings](assets/readme-assets/Bugs/js/level%20not%20defined.png)

   HTML ID not defined as a variable. Created a variable for this and stored as level.

   ---

   **Points - 	'i' is not defined.:** <br>
   ![HTML Warnings](assets/readme-assets/Bugs/js/i%20not%20defined.png)

   Declare i as a variable.

   </details>
   
   ___

   <br>

   ## Lighthouse Accessibility Results:
   ![Accessibility Review](assets/readme-assets/validation/Accessibility.png)

   <br>

   ## Testing User Stories from User Experience (UX) Section

   <details>
      <summary style="font-weight:bold">Client Goals</summary>

   The client wants a simple and engaging game that is easy to use and will result in users returning to the site. 
   * Sleek yet simple UX design.
      - **REVIEW - UX design kept minimalist. Simple, clear colour scheme with engaging visuals to make the page look like it is being completed on a notepad as one might historically play hangman.**
   * Easy to use functionality.
      - **REVIEW - Simple intuitive buttons/functions. Built without overcomplicating and game requirements. All built on one page for simplicity.**
   * Responsive for any device size to encourage mobile use as well as desktop use.
      - **REVIEW - Built with responsive design for all devices. Structure of page amended to best suit the appropriate device size.**
   * Links to the client's social network accounts to enhance their online presence.
      - **REVIEW - Social network links located in footer with clear recognisable images.**
   * Addictive gameplay to encourage return clients and drive positive word of mouth to encourage new users.
      - **REVIEW - Used feedback from testers to build a game which has been well recieved with testers re-using for their own enjoyment.**
   
   ---
   </details>

   <details>
      <summary style="font-weight:bold">Client Future Goals</summary>
   
   Points to consider for future development:
   * Additional words and topics to be added to the hangman game.
      - **REVIEW - Option to add additional lists to the game and increase the existing lists. Code written to make this addition easy to implement.**
   * Allow for scores to be recorded and stored into a leader board.
      - **REVIEW - For future enhancements utilising back-end development, it would be good to store user data and scores to generate a leader board encouraging re-use and competition between users.**
   * Additional games and puzzles added to the site.
      - **REVIEW - Use the site to develop a range of similar games with a consistent aesthetic appeal.**
   * Generate advertisement revenue through the site.
      - **REVIEW - Once web traffic is sufficient use the site to advertise products and services. This must be done in a way to minimise the negative impact on user experience.**

   ---
   </details>

   <details>
      <summary style="font-weight:bold">First-Time Visitor Goals</summary>

   * Immediately engaged by the UX design.
      - **REVIEW - Engaging gameplay and visuals developed based on user feedback to ensure an immediate and continued interest in the game.**
   * Understand the purpose of the site.
      - **REVIEW - Very clear game purpose and easy to locate and read rules where required.**
   * Simple intuitive menu navigation.
      - **REVIEW - Menus built to stand out using colour differentiation. Always easily identified on the screen.**
   * Intuitive content and links to social media.
      - **REVIEW - Social Media links easily identifiable and located on the screen.**
   * Readable and aesthetically pleasing on all devices.
      - **REVIEW - Game structure amended to best present on each device size. Smooth responsive alterations on reducing screen size.**

   ---
   </details>

   <details>
      <summary style="font-weight:bold">Returning Visitor Goals</summary>
   
   * Revisit to replay game to try different topics.
      - **REVIEW - Multiple topics generated to keep people of different interests engaged. On completion of a topic, it will be unusable (until game reset) giving the user a feeling of accomplishment.**
   * Revisit to replay game to beat previous score.
      - **REVIEW - Accumulating score gives a challenge to users to see how high a score they can generate and try to beat this on re-visits.**
   * Revisit to locate social media links to client.
      - **REVIEW - Social Media links available for anyone trying to link in with the client (These are not set to real accounts for this project due to a fictional client).**

   ---
   </details>

   <br>

   ## Further Testing
   * Tested across Google Chrome, Safari, Microsoft Edge, Fire Fox browsers on both Mac and Windows.
   * Viewed on a variety of devices using Web Developer Tools as well as several live desktop, iPad and mobile devices. 
   * Each page tested by developer and friends to ensure functionality worked as expected.
   * Issued to Slack community to review and feedback on.

   <br>

   ## Development Bugs

   <details>
      <summary style="font-weight:bold">Menu toggle not presenting as indented</summary>
   
   On closing settings or rules using the close button on a small screen the menu remains open. I want this to close to improve aesthetics and reduce required button clicks when returning to game.

   ![Leave Settings Img](assets/readme-assets/Bugs/develoment/leave-settings.png)

   ![Leave Settings Img](assets/readme-assets/Bugs/develoment/small-menu.png)

   Image shows that after ‘Leave Settings’ is selected the menu remains on screen until the ? icon is selected again.

   Another issue this caused was that if the rules or settings content were opened on a small screen and the ? icon was clicked it would toggle the menu off and need to be clicked again to open the menu options.

   The final issue with the toggle option on the ? icon was that when it was set to on and the screen size was changed to large, when rules or settings were opened and the screen was returned to small the menu overlapped the rules or settings content.

   ![Leave Settings Img](assets/readme-assets/Bugs/develoment/overlap-menu.png)

   Image shows the menu overlapping rules and settings content.

   By adding the matchMedia code and moving the rules and settings in front of the small screen menu with a CSS z-index of 2 the functionality works as intended.
   
   <br>

   **Code block to resolve:**

      if (matchMedia("(min-width: 821px)").matches) {
            postIt.className = "post-it-contents";
      }
      else {
            postIt.classList.toggle("select");
      }

   ___

   </details>

   <details>
      <summary style="font-weight:bold">Canvas resize required</summary>
   
   When I initially drew the hangman on the canvas, I had an issue if the screen was re-sized. The image would not re-size along with it.

   By implementing a event listener for window re-size and calculating the canvas images based on a percentage of the canvas height and width I was able to resolve this issue.

   ![Leave Settings Img](assets/readme-assets/Bugs/develoment/hangman-resize.png)

   Image shows canvas not re-sizing to match screen change.
  
   <br>

   **Code block to resolve:**

      window.addEventListener("resize", function() {
        canvas.width = canvasSize.clientWidth;
        canvas.height = canvasSize.clientHeight;
        hangmanDraw();
      });

   The above image shows how when the screen size is changed the canvas re-sizes and redraws the required elements.

      function drawBase() {
        ctx.fillRect(canvas.width * 0.2, canvas.height * 0.9, canvas.width * 0.6, 5);
      }
   
   The above code block shows a canvas element calculated based on canvas dimensions.

   ___

   </details>
   
   <br>

   ## Key Learn
   The main key learn I took from this project was to build the readme file in conjunction with the website development.

   I was not sure if the design and functionality were feasible for the development of this project given my limited experience in CSS and JS. Therefore, I spent a lot of time building it in a test environment before deciding I could accomplish the desired result.

   By the time I had realised it was feasible I had completed a lot of the work. As a result of this I had to retrospectively complete sections of the readme file which would have been better suited to completing at the scoping, researching and initial build stages.

   Despite this I feel that I did a good job recording my progress through easy-to-understand concise commits which made it easier to revisit certain elements of the project where necessary.


   <br>

# Deployment
   ## Set up Local GitHub Repository
   1. Go to https://github.com/Code-Institute-Org/gitpod-full-template.
   2. Select use this template.
   3. Add repository name within my GitHub. (This will generate a repository in my Git Hub with the appropriate files.)

   ## Repository Framework
   1. Select the repository on GitHub and open with Gitpod (green button).
   2. Create required html page.
   3. Create assets folder.
   4. Within assets folder create css folder, images folder, js folder & readme-assets folder.
   5. Add required files to folders including style.css, images, script.js, etc.

   ## Update Repository
   1. When adding a new feature create a separate branch to work in safely typing into the terminal "git branch 'name of required feature/update'".
   2. Checkout the branch with "git checkout 'name of required feature/update'".
   3. Make updates and test using "python -m http.server".
   4. Once testing is complete add to Git staging area using "git add ."
   5. Commit the changes and add a useful explanation of what action was done to track the history in GitHub using "git commit -m 'explanation of update'".
   6. Once the feature is complete, fully tested, and ready to be added to the main branch first go to the main branch using "git checkout main".
   7. Merge the feature branch into the main using "git merge 'name of required feature/update'".
   8. Confirm merge was successful and then if it is not going to be re-used delete the feature branch using "git branch -d 'name of required feature/update'". (if deleting a branch with commits not merged to main delete with -D instead of -d)
   9. Use "git push" to push the commits to GitHub. These will then appear in the live website if it has been set up in GitHub Pages.

   ## GitHub Pages
   Deploy in GitHub Pages:
   1. Log in to my GitHub and go to my appropriate repository.
   2. Access settings.
   3. Under 'Code and Automation' go to pages.
   4. Leave the source as Deploy from Branch.
   5. Set Branch to Main.
   6. Save.
   7. Give GitHub a few minutes and the live URL is provided at the top of the GutHub Pages section of settings.
   8. Any Git Pushes from the terminal whilst working on the repository using Gitpod will now update in this live site.

   <br>

# Credits
   ## Content
   The following sources acted as guidance for understanding. No code was taken directly for use in this project.


   * Learning how to use linear gradients. This was used to develop the look of a notepad with re-occurring lines. (https://www.w3schools.com/css/css3_gradients.asp), (https://codepen.io/ceg9498/post/creating-lined-paper)
   * FlexBox guidance/re-fresh. (https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
   * Intro to canvas in js to create the hangman image. (https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial)
   * Canvas responsive. (https://stackoverflow.com/questions/34772957/how-to-make-canvas-responsive)
   * Clearing the canvas. (https://stackoverflow.com/questions/2142535/how-to-clear-the-canvas-for-redrawing)
   * Understanding event listeners. (https://www.w3schools.com/js/js_htmldom_eventlistener.asp)
   * Change mouse pointer on hover for menu list items (https://www.w3schools.com/cssref/pr_class_cursor.asp)
   * Understand the toggle class method to utilise in menu activation. (https://www.w3schools.com/howto/howto_js_toggle_class.asp)
   * Set js rules dependent on screen size. (https://www.w3schools.com/jsrEF/met_win_matchmedia.asp)
   * Wrap entire game in a initialise function to eliminate glabal variables. (https://www.youtube.com/watch?v=_4V4yUxGng8)
   * stackoverflow used for generalised queries during development.



   ## Media 
   * All images were obtained from Unsplash.
      - Image for the backgound wood effect (jon-moore-5fIoyoKlz7A-unsplash.jpg).
      - Image of the mountain doodle which shows on large screen viewings (nicolas-pinilla-GcDr6ZIzbIw-unsplash.jpg).
   * Audio was taken form YouTube videos
      - Sound on correct answer (https://www.youtube.com/watch?v=403gX7TnhTQ)
      - Sound on incorrect answer (https://www.youtube.com/watch?v=RZEsfS1rGyY) - modified using Audacity
      - Sound on getting word correct (https://www.youtube.com/watch?v=ytjxf9YNJ-0) - modified using Audacity
      - Sound on getting word correct (https://www.youtube.com/watch?v=na-a3lLB13Q&t=16s) - modified using Audacity


   ## Acknowledgements
   * Thank to my Mentor (Spencer Barriball) for his feedback and guidance.
   * The Code Institute Slack community for helping with any and all queries.
