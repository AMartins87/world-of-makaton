## **WORLD OF MAKATON**

This project is for educational purposes only.

The purpose of the World of Makaton website is to introduce more people to this wonderful and easy to learn sign language which supports children and adults who may have learning difficulties and/or delays, to communicate better.

I wanted to keep the site concise and easy to navigate through as there are multiple pages out there that are good as they contain lots of information about the subject but they are not very easy to navigate through and lots of important pieces of information are scattered over several pages.

World of Makaton gives the user a taster of this form of communication and it gives an external pointer to a TV programme which I'd highly recommend as it will help with learning the sign language in form of fun and play. 


![Mock up image](wireframes/mockup.JPG)

<a></a>
## **FEATURES:**


- **Navigation:**
    - Navigation links are on top of each page on every screen size to take the user to a different page of the website.
          - It allows the user to easily navigate from page to page across all devices as the navbar is in a fixed position even if you scroll through any page.
    - Sections of the navigation bar are: Home, About, ABC, and Sign Up.
        - Each page has a title > Home page - World of Makaton; About - About Makaton; ABC - ABC ... Alphabet; Sign Up - Sign Up.
    - Fonts and colors compliment the overall look of the website and are consistent throughout.

![Navigation bar image](wireframes/navbar.JPG)

- **Home page image:**
    - The header shows the name of the website, using a chosen color of purple shade (#894ac5). 
    - The header's tagline gives the user clear information about what the website is about.

![Home page image](wireframes/home_image.JPG)

- **Footer:**
    - Contains social media links leading to Faceboook, Twitter and YouTube and link to an email in form of icons. The links will open in a new tab to allow easy navigation and avoid using 'back' button to return to the page. The email link will open the user's choice of email software, i.e. desktop mail app/Outlook and the Email
    - Contains copyright information, including year of creation and my name

![Footer image](wireframes/footer.JPG)

- **About:**
    - This section gives the user information about what Makaton (subject of the website) is, how it is used and the best tips on how to start learning it.
    - Image shows the character of Mr Tumbles from CBeebies shows 'Something Special'

![About page image](wireframes/about_page.JPG)

- **ABC:**
    - This page contains images of the Makaton finger alphabet. Every single picture has a thin border to separate each image from each other and again allow better user experience

![ABC page image](wireframes/abc_page.PNG)


- **Sign Up:**
    - Sign up page has a form to collect user's details if they would like to receive news & updates
    - Form collects name, email and selection of newsletter type the user would like to receive
    - Users will be able choose if they would like to get text materials, video tutorials or informations about any running workshops. The user will be asked to submit their name and email address.

![Sign Up page image](wireframes/signup_page.JPG)

<a></a>
## **TESTING**

------
info for me: In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

<a></a>
## **>VALIDATOR TESTING**

-   HTML (No errors were returned when passing through the official W3C validator 
        [Home page](https://validator.w3.org/nu/?doc=https%3A%2F%2Famartins87.github.io%2Fworld-of-makaton%2Findex.html)
        [About page](9https://validator.w3.org/nu/?doc=https%3A%2F%2Famartins87.github.io%2Fworld-of-makaton%2Fabout.html)
        [Abc page](https://validator.w3.org/nu/?doc=https%3A%2F%2Famartins87.github.io%2Fworld-of-makaton%2Fabc.html)
        [Sign Up page](https://validator.w3.org/nu/?doc=https%3A%2F%2Famartins87.github.io%2Fworld-of-makaton%2Fsign_up.html)
-   CSS (No errors were found when passing through the official ![Jigsaw validator](http://jigsaw.w3.org/css-validator/validator$link)

<a></a>
## **UNFIXED BUGS**

-   Yellow warning showed up on ABC page due to the whole page section not having a heading element. There is no need to use a heading element as the page contains only images of the finger alphabet. 

<a></a> 
## **DEPLOYMENT**

    The site was deployed to GitHub pages. The steps to deploy are as follows:
    1.  In the GitHub repository, navigate to the **Settings** tab, then **Pages** section
    2.  From the **Source** section drop-down menu, select the **Branch:main**
    3.  Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
    4.  Now this site is live and published at (https://amartins87.github.io/world-of-makaton/)

<a></a>
## **CREDITS**

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.


- **Content**
    - My main point of reference for the written content was [Makaton website](https://makaton.org) to double check I wasn't going to write an incorrect data and information.  

    - The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

- **Code**
    - The select option code was advised to use by my mentor Maria Hynes as I couldn't implement a 'required' attribute to my previous checkbox option without using a javascript. 

- **Media**
    - [Home page image](https://www.theschoolrun.com/sign-language-and-makaton-in-schools) obtained via google search for Makaton signing language relating images as there were none on royalty free sites. / https://www.shutterstock.com/image-photo/brother-sister-learn-sign-language-home-450847297
        
"This project is for educational purposes only". 
The photos used on the home and sign up page are from This Open Source site
The images used for the gallery page were taken from this other open source site
Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!

## **BUGS**

-   Right at the beginning my page wasn't loading all the style changes. I realised I forgot to link the style.css file with the index.html file. Once I linked it, all was fixed.

-   When I ran the code through a validator, an error popped up on my sign_up.html page in my '.form-section'. I have had set the target="_blanket" and it had strangely worked - a new page opened up in a new window. However the correct value is target="_blank". 

