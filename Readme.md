# EZLOGIC - Educational Website (HTML, CSS, JS)

![image](https://github.com/20100215/EZLOGIC/assets/84717650/c0f39143-bab5-4ca7-8853-0a9a362f074c)

![image](https://github.com/20100215/EZLOGIC/assets/84717650/a9ab64ed-4391-4b38-8ac4-ae860f6a69c5)

![image](https://github.com/20100215/EZLOGIC/assets/84717650/7ace16c9-fa0d-40f9-a26b-afa897805566)


Tested in all screen resolutions from Mobile (> 320x568) to PC (< 1440x900)

NOTES: 

(1) All HTML files have JavaScript codes embedded inside it. No external .js file created.

(2) Contents (texts, image sources, buttons, links) in all webpages are all complete.

(3) All images are placed in \Images folder.
 
Folder contents:
1. index.html - Home/landing page for visitors with site introduction and objectives. (with hyperlinks and button accessing all other pages)

In \Files folder:

2. Lessons.html        - Displays lists of topics available for viewing in accorditions and their discussion and quiz links.
                              This page is made separately for web and mobile versions.
3. About.html          - Contains descriptions about the website and author. Slideshows (JavaScript controlled) are included.
  
4. Contact.html        - Contains a form for visitor feedback and guidelines for tutorial request.

5. Privacy&Terms.html  - Contains descriptions on the Privacy Policy and Terms of Use (Displayed in columns) 

6. Base.css*           - Lists the classes and block/text/media property formatted with their values.

7. ColorTheme.css      - Lists the theme colors used and other property values overriding the previous CSS file.

In \Files\Topics folder** :

8-12. x-x.html         - Contains a brief discussion on the topic with examples enclosed in accorditions.
                              Subtopics in each page can be also be accessed via anchor links in the "Topic Outline" section.
                              Link to quiz is provided at the bottom of the page.

13-17. x-xQuiz.html*** - Contains questions from the corresponding topic with responsive form elements for answering.
                              Upon pressing the submit button, the results (score and comments) will be displayed instantly with
                              page formatting adjustments to emphasize questions correctly and incorrectly answered.

   *.   Part of the Base.css file is taken from and credited to www.w3schools.com for their predefined formatting.
        Some classes and proporties are modified to precisely match with desired website layout.
 
   **.  MathJax expressions are present in some areas within the content, thereby an embedded script to the MathJax
        server is added with minor style adjustments to make the expressions display by inline instead of block.
   
   ***. Quiz layout and checking are made from scratch. No external source code copied.
