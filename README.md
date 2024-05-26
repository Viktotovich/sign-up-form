# sign-up-form
This is a test sign-up form using CSS Pseudo-classes, and other elements. The goal is to attain a fully functioning page that validates the data visually on the frontend, before sending it to the backend.
For obvious reasons, this will not have any form of an attempt to validate, obfuscate, or hash passwords - as this is purely a front-end test project.


Latest Update: Made responsive on mobile, at the sacrafice of some contents. It looks extremely basic, like a 2012 based intranet site. However, functionalities like pwd validation with JS - still function as normal.

On Desktop, the project is a success. Visual queues are provided, and it feels nice to interact with.

Despite of how simple it looks, I did run into many problems with this project:

1) Positioning the error messages
2) Stopping the second flex container from always overflowing
3) Making it look nice on non-Desktop screens (semi-failed)

To fix 1) I had to use careful positioning, and it ended up making the code cluttered and terrible to look at. However, it looks quite nice on display, and doing it this way has helped avoid content overflow, and unexpected shifts of content due to visual queues being displayed / changing.

To handle 2) and 3)I used media queries on smaller screens, and adjusted the font sizes. A fix that you might feel would work is height 100% - but it wont, as it was the first idea that was implemented. The contents of the content box overflow, and even flex-wrap: wrap caused some troubles. The solution was to calculate things in such a way that it would fit the container.

In retrospect, I would have rather used an actual img element rather than an image background with CSS - that way, I could've adjusted the size a lot better and it *might* have allowed the content to be adjusted for mobile better.

The implementation for smaller screens would've been so much better and easier: hide the large image, and keep the banner on mobile - while positioning the sectors as columns.

Well, we live and learn. This mistake caused a lot of trouble down the line.


If there is an advice I would give to my past-self working on this project, it would be to:

-Re-visit flex and specifically flex-basis before starting the project.
-Use a different color scheme (that won't feel 2012-corporate-esque)
-Read documentation rather than spending hours on brute-force implementation

Things done right:
-Font, font-color, and the general feel
-The layout and how it is an eye candy at parts
-The initial HTML layout before starting with CSS - it made it atleast 10 times easier to work through everything
-JavaScript implementation
-Visual queues (although they might come off as aggresive)

Overall, I would say that I need to keep on practicing more and more to get better. Each mistake made is a mistake less in the future.

-Vlad,
16:14, 26 May 2024