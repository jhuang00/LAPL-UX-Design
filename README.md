# Heuristic Evaluation

## Feeding the Mind

With the COVID-19 pandemic, we have entered a period of time when people are facing instability and uncertainty. As Los Angeles continues to be in a state of lockdown, more people are experiencing negative emotions such as anxiety and fear. Although middle-aged women are not usually under the spotlight of the social realm of discussion, they are a group that cannot be neglected. Focusing on the happiness of middle-aged women, I hope to, in this project, explore a way of providing an outlet of the real world. By improving the user experience, it can make sure these users can find the process of using the product enjoyable and that the overall experience brings happiness.

## Analysis of Website: [Los Angeles Public Library](lapl.org)

The Los Angeles Public Library (LAPL) is a public library system that serves residents in LA, serving the largest population among all publicly funded library systems in the United States of over 18 million residents. Holding more than 6 million volumes, the LAPL system provides books, zines, periodicals, computer access, and audiovisual materials freely to the residents. The LAPL website contains information digitally that can be accessed and viewed by the users.

The LAPL website needs to be accessible and easy to understand for all users, including the users we are focusing on — middle-aged women.

![LAPL website homepage screenshot](lapl-screenshot-home.png) 

In the heuristic evaluation, I will use Jakob Nielsen's 10 general principles for interaction design for this analysis.

I will use severity ratings to aid the heuristic evaluation. 

### Severity Ratings in Heuristic Evaluation (from [Nielson Norman Group](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/))
The severity of usability problems can be rated from a 1 to 3 scale as follows:
Rating  | Importance  |
:---: | :---  |
1  | Cosmetic problem only: need not be fixed unless extra time is available on project  |
2  | Minor usability problem: fixing this should be given low priority  |
3  | Major usability problem: important to fix, so should be given high priority  |


#### Usability Heuristic #1: Visibility of System Status
>The system should always keep users informed about what is going on, through appropriate feedback within reasonable time.

**Rating: 2**
* The LAPL website has appropriate and prompt response when the user hovers over something that is clickable. For example, the menu would expand when the user hovers over a tab. A tab would change color to show its responsiveness. A link would be underlined to show it is clickable.
<img src="lapl-screenshot-uh1-hoverresponse.png" alt="LAPL screenshot - heuristic 1 - appropriate feedback" width="80%">

* However, the user needs to have experience with web products, and have good vision in order to detect every function. For some functions, the website has low visibility of the system status since the icon is too small, so it is difficult for the user to spot the possible actions they can perform.
<img src="lapl-screenshot-uh1-icontoosmall.png" alt="LAPL screenshot - heuristic 1 - low visability" width="80%">

**Recommendation:**
* Some feedback should have increased visibility, such as a more drastic change of colors.

* Some functions should be more visible for users to find in order to make use of those functions; for example, a filter bar on the left of the screen should have more visible \[+\](for expanding) and \[-\] [-] (for collapsing) icons.


#### Usability Heuristic #2: Match Between the System and the Real World
>The system should speak the users' language, with words, phrases and concepts familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order.

**Rating: 2**
* The LAPL website follows real-world conventions in general. For example, the main page has a collection of information and makes use of a menu bar to contain shortcuts to subpages. The main page also serves as an eye-catching page of the product that allows user to decide if there are contents that catch their eyes.

* The website has too much information, which can be overwhelming to the user. If a user is not used to viewing a digital site with loads of information, the user can be confused. It is different from a more traditional form of media or books that it presents too much information on one page.

**Recommendation:**
* The website should consider putting less information on one page, so that every feature can be presented in a more conspicuous way. Otherwise, some good features can be neglected by the users who need them.

* Consider mimicking an actual library, or the status of an actual book - this would enhance the user experience for elder users as they would be more used to a skeuomorphic design.


#### Usability Heuristic #3: User control and freedom
>Users often choose system functions by mistake and will need a clearly marked "emergency exit" to leave the unwanted state without having to go through an extended dialogue. Support undo and redo.

**Rating: 1**
* Being a website that exists within a web browser, it naturally has the function of going back to a page that the user has previously browsed, therefore allowing the user to "exit" the current page quite easily.
<img src="lapl-screenshot-uh3-backtopage.png" alt="LAPL screenshot - heuristic 3 - undos in browser" width="80%">

* If users are redirected to a new page in a new tab, they can still access the previous tab/tabs by clicking on them.
<img src="lapl-screenshot-uh3-browsertabs.png" alt="LAPL screenshot - heuristic 3 - changing between tabs" width="80%">

**Recommendation:**
* Consider letting the menu bar with the drop-down list be consistently fixed on every page, so that users can easily go to the pages they have been to before.


#### Usability Heuristic #4: Consistency and standards
>Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform conventions.

**Rating: 2**
* The website follows many design conventions and standards, which makes it intuitive for the user. For example, the search bar is located on the top right of the page (consistent with the convention that search bars are usually shown on the top right or middle), with a text box and a magnifying class icon (universally used for search icon).

* There are some minor issues that can potentially make the user confused. For example, in the "Schedule Your Pickup" page, the menu on the right has collapsing and expanding icons. They are against user experience convention: the arrow should be pointing down when the list is collapsed and up when the list is expanded.
<img src="lapl-screenshot-uh4-inconsistency.png" alt="LAPL screenshot - heuristic 4 - inconsistency with convention" width="80%">


**Recommendation:**
* Some details should be redesigned to make the user experience more smooth and intuitive. As little as the direction of arrows can change how the user thinks and behaves.

#### Usability Heuristic #5: Error prevention
>Even better than good error messages is a careful design which prevents a problem from occurring in the first place. Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action.

**Rating: 3**
* There is lacking error prevention for the user logging in. For example, when the user tries to put more digits in the text box intended for only 4 digits (of phone number), there is no error message stopping the user. Therefore, the user may waste time on figuring out what has been wrong with out the system's warning.
<img src="lapl-screenshot-uh5-noerrorprevention.png" alt="LAPL screenshot - heuristic 5 - lacking of error prevention" width="80%">

**Recommendation:**
* Add error prevention to prevent users from going to the next step while inputting the wrong information and spending time figuring out their mistake.


#### Usability Heuristic #6: Recognition rather than recall
>Minimize the user's memory load by making objects, actions, and options visible. The user should not have to remember information from one part of the dialogue to another. Instructions for use of the system should be visible or easily retrievable whenever appropriate.

**Rating: 2**
* There is a lot of redirection of links to other websites (some difficult to tell what it specifically does). Users can easily lose track of which website they should be on. The new links are often opened in a new tab, so users may be confused about when they should go back to the previous page or search for the other tabs.
  * For example, when the user tries to schedule a pickup from a library branch, they are redirected to https://curbside.capiratech.com/?code=laplcaus. It is difficult to remember which library this is, etc. since there is no explicit indication.
<img src="lapl-screenshot-uh6-redirection.png" alt="LAPL screenshot - heuristic 6 - redirection of site" width="80%">

**Recommendation:**
* This is more about how ample and complicated the LAPL system is. The site can improve by making the tabs with links redirection more visible and more organized.


#### Usability Heuristic #7: Flexibility and efficiency of use
>Accelerators — unseen by the novice user — may often speed up the interaction for the expert user such that the system can cater to both inexperienced and experienced users. Allow users to tailor frequent actions.

**Rating: 2**
* The flexibility of the LAPL website is low, and users are not able to tailor frequent actions. However, the shortcuts provided by the website browser might be sufficient for experienced users to perform many actions efficiently.

**Recommendation:**
* Consider adding flexibility or making more accelerator available to users with good browser compatibility.


#### Usability Heuristic #8: Aesthetic and minimalist design
>Dialogues should not contain information which is irrelevant or rarely needed. Every extra unit of information in a dialogue competes with the relevant units of information and diminishes their relative visibility.

**Rating: 3**
* The LAPL website provides too much information on each page that the user can easily get confused or lose their focus. This drastically diminishes the relative visibility of units of information.

* The design, aesthetically, is quite old-fashioned compared to modern design trends. It does not provide a visually pleasing experience to users, which can cause fatigue.

**Recommendation:**
* It would be good to redesign the website after creating a style guide that references modern design methods. It is also important to take note of the idea of minimalist design, and redesign the website with better presentation of information.


#### Usability Heuristic #9: Help users recognize, diagnose, and recover from errors
>Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution.

**Rating: 2**
* There are hardly any error messages displayed on the website, which is in fact not efficient. It makes the user more difficult to recover from an error. For example, when the user clicks on "search" or "filter" without typing anything in the search bar, it will still take the user to the next page. It can therefore cause confusion.

**Recommendation:**
* Set more error messages, that can help users recognize, diagnose, and recover from errors. For example, if the user try to search from the Library Catalog without inputting anything, stop them before entering the search (to avoid the uneccessary "No search results found").


#### Usability Heuristic #10: Help and documentation
>Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on the user's task, list concrete steps to be carried out, and not be too large.

**Rating: 2**
* Help is provided through a "How Do I" page, documenting potential problems listed and organized in FAQ format. The page provides answers to those questions from "How do I get a library card?" to "How do I download e-materials?", which are very helpful to users. However, some inexperienced users could potentially still be confused because the answers are too succinct for them.
<img src="lapl-screenshot-uh10-helpdoc.png" alt="LAPL screenshot - heuristic 10 - help and documentation page" width="80%">

**Recommendation:**

* To accommodate for all users, the help and documentation can be more detailed, providing step-by-step guidance to users that may need help.


-----


## Analysis of APP: Los Angeles Public Library (link to download provided [here](https://www.lapl.org/app))

The Los Angeles Public Library APP is another official virtual way to access the LAPL system. It is a mobile APP designed to be accessed on a smartphone; the LAPL promote this APP on its website with "Take the Los Angeles Public Library Everywhere You Go!" Therefore, the APP is meant to provide a convenient and accessible way to interact with the LAPL system. The main functions of the APP include:
* Searching the library catalog and reserve items,
* Managing your checkouts and holds,
* Accessing your digital library card, and
* Viewing upcoming events at your local library
at the palm of your hand.

The LAPL APP should be designed for all its library patrons as potential users.

<img src="lapl-app-screenshot-home.png" alt="LAPL APP homepage screenshot" width="50%">

In the heuristic evaluation, I will use Jakob Nielsen's 10 general principles for interaction design for this analysis.

I will use severity ratings to aid the heuristic evaluation. 


#### Usability Heuristic #1: Visibility of System Status
>The system should always keep users informed about what is going on, through appropriate feedback within reasonable time.

**Rating: 2**
* The LAPL APP is quite responsive from the point of view of a user. When a page loads, there would be a loading icon in the middle of the screen to indicate that something is happening.

* The loading time is a bit long compare to other APPs - this is related to the server, internet connection, etc.

**Recommendation:**
* It would be better if the loading time is shorter - the shorter the better - the more responsive, the more likely a user is going to stick on the APP!


#### Usability Heuristic #2: Match Between the System and the Real World
>The system should speak the users' language, with words, phrases and concepts familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order.

**Rating: 1**
* The icons are clear since they illustrate the meaning of quite well. In this way, the user can be well informed by the icon and the description down below what page they are clicking into.
<img src="lapl-app-screenshot-uh2-familiarillustrations.png" alt="LAPL APP screenshot - heuristic 2 - familiar illustrations to users" width="40%">

**Recommendation:**
* The presentation can be more dynamic - the real world often present information dynamically. For example, there can be more layers of information, which is consistent with the user's understanding of systems.


#### Usability Heuristic #3: User control and freedom
>Users often choose system functions by mistake and will need a clearly marked "emergency exit" to leave the unwanted state without having to go through an extended dialogue. Support undo and redo.

**Rating: 3**
* Users, for the most part, can easily go back to the previous page. However, in the case when a page is loading, the user is stuck on the page, unable to go back or perform any action if they want to "exit" the situation. This is problematic when the page is taking a long time to load.
<img src="lapl-app-screenshot-uh3-loading page.png" alt="LAPL APP screenshot - heuristic 3 - unable to go back from the loading page" width="40%">

**Recommendation:**
* Allowing the user to leave the page and go back when a page is loading is an essential feature that needs to be fixed quickly for this APP. Make sure that the user always have a way out (without having to restart the APP)!


#### Usability Heuristic #4: Consistency and standards
>Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform conventions.

**Rating: 2**
* In general, the APP is simple that it provides icons that the user can click on. However, upon clicking, some icons will redirect the user to a web link, while others results in a page in the APP.

**Recommendation:**
* It would be better to indicate whether a link will direct the user to a page built in the APP or a webpage before the user clicks on it. Also, the APP can be more consistent by building more built-in functions in the APP.


#### Usability Heuristic #5: Error prevention
>Even better than good error messages is a careful design which prevents a problem from occurring in the first place. Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action.

**Rating: 2**
* There is no error prevention in the APP. When the user is trying to put in log-in information, there is no warning until the user hits "confirm."

**Recommendation:**
* Put in some error prevention for areas where user input is needed. For example, the text box requiring a 4-digit pin can restrict its input to 4 digits.


#### Usability Heuristic #6: Recognition rather than recall
>Minimize the user's memory load by making objects, actions, and options visible. The user should not have to remember information from one part of the dialogue to another. Instructions for use of the system should be visible or easily retrievable whenever appropriate.

**Rating: 2**
* When the user enters an inner page, there appears to be a "home" icon in the tab bar, allowing the user to go back to the previous page.

* There lacks a menu bar that exist across all pages for which the user can easily check which page they are currently on and where they came from.

**Recommendation:**
* A menu bar can be added on the left of the screen, which provides an overview of which place, or which sub-page the user is on.


#### Usability Heuristic #7: Flexibility and efficiency of use
>Accelerators — unseen by the novice user — may often speed up the interaction for the expert user such that the system can cater to both inexperienced and experienced users. Allow users to tailor frequent actions.

**Rating: 2**
* There is no design of accelerators such that inexperienced or experienced users are faced with the same functionalities.

**Recommendation:**
* Consider adding function that can speed up the interaction for the expert user. However, there are not many functions in the mobile APP, so even without accelerators or shortcuts, the functions can be accessed quite directly.


#### Usability Heuristic #8: Aesthetic and minimalist design
>Dialogues should not contain information which is irrelevant or rarely needed. Every extra unit of information in a dialogue competes with the relevant units of information and diminishes their relative visibility.

**Rating: 2**
* This APP has a minimalist design, with 6 main icons to click into, and 2 icons on the tab bar. It is quite simple and clear. Even using it the first time, the user can quickly grasp its main functions.

* In terms of aesthetic, the use of color is quite random; moreover, the main color go astray the LAPL's official website, which makes it harder for users to form an impression. Also, the APP, in general, lacks aesthetic beauty (although it is not the priority), and it lacks any style that can make it more distinct or memorable.

**Recommendation:**
* While keeping the minimalist design, the APP should be redesigned with a more consistent and attention-grabbing aesthetic and style. The color should be treated with more care. For example, there can be a main color, consistent with the website, and one or more supplemental colors.


#### Usability Heuristic #9: Help users recognize, diagnose, and recover from errors
>Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution.

**Rating: 1**
* In general, messages are clear and concise. They inform the user what the problem is.
<img src="lapl-app-screenshot-uh9-message.png" alt="LAPL APP screenshot - heuristic 9 - error message" width="40%">

**Recommendation:**
* Users may be more familiar to messages displayed in the middle of the screen on a mobile phone. However, messages displayed at the bottom is also clear and distinct.


#### Usability Heuristic #10: Help and documentation
>Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on the user's task, list concrete steps to be carried out, and not be too large.

**Rating: 3**
* There is no help and documentation within the APP for the APP. Even though the APP does not have many functions, it is still necessary to provide guidance or some document for the user to refer to.

* The closest thing to help and documentation provided on this APP is an icon on the tab bar. If the user clicks on it, it provides the options "Call Us" and "Email Us." However, the contact information is not specific to inquiries of the LAPL APP itself, but it is rather for providing information for LAPL in general.
<img src="lapl-app-screenshot-uh10-contactus.png" alt="LAPL APP screenshot - heuristic 10 - contact us" width="40%">

**Recommendation:**

* Help and documentation is necessary! For an APP for a large library system having 18 million potential users, facing every type of user, it would be important to have some form of help that the user can easily refer to. For example, having a 'help' icon at the top right which allows easy access to a help documentation (or a Q&A page) would be good.

-----

### Reference
* Wikipedia: Los Angeles Public Library (https://en.wikipedia.org/wiki/Los_Angeles_Public_Library)
* Nielson Norman Group: 10 Usability Heuristics for User Interface Design (https://www.nngroup.com/articles/ten-usability-heuristics/)
* Nielson Norman Group: Severity Ratings for Usability Problems (https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)
* Los Angeles Public Library (https://www.lapl.org/)
* Los Angeles Public Library App (https://www.lapl.org/app)
