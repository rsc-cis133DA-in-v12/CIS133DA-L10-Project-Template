# Lesson 10 Project
The computer company client is pleased with the layouts you've created for them so far. This week, the company would like you to focus on creating visual elements for viewers using HTML and CSS to display "cards" side-by-side with more in-depth descriptions about the services they provide. Since the client's users and employees will access the web site on different personal devices, they'd like you to use what you learned about responsive web design to make sure the layout of the page looks good for mobile, tablet, and larger devices.

## Project Prep
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 

   > **TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.

   > **TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.
4. In your CSS subfolder create two new CSS files named: **mobile_style.css** and **tablet_style.css**

<br>

## Create the Services Page

> **ASSIGNMENT TIP**<br>As you work on the styling for this assignment and future assignments, you should load the web page within your browser. Then use the built in developer tools to simulate the different viewports that each CSS file will target. As you make adjustments to your CSS, see how it looks in the different viewports. Review the **Responsive Web Design** page in Lesson 9 for information on how to use the browser tools if needed. 

1. If necessary, open the Template from your Lesson 9 folder.
2. Add the necessary viewport metadata so the viewport width is equal to the device width and that the initial scale is set to 1.
3. Modify the existing link to the external Default stylesheet to include a media query that detects when the device is larger than 900px.
    > **TIP:** When you first load the page and look at the different viewport sizes the styles should disappear entirely except for a viewport larger than 900px since there are no mobile or tablet styles.
4. Create an link for the external Mobile stylesheet to:
    1. Apply a media query to load the mobile style CSS for any device that is smaller than 450px.
5. Create an link for the external Tablet stylesheet to:
    1. Apply a media query to load the tablet style CSS for any device that is smaller than 900px.
    > **TIP:** You must think through how to properly apply the tablet CSS file. If the media query is not designed correctly, it will override the mobile version and the mobile file will never be used.

6. Save your changes and then save a copy of the Template to your Lesson 9 folder as: **services.html**
7. Open the Services page from your Lesson 9 folder, if necessary.
8. Update the metadata with the following: 
    1. Change the title to: **Our Services**
    0. Define the author using your first and last name.
    0. Add a minimum of 5 keywords appropriate for the page content.
    0. Add an appropriate description.
0. Apply the **active** class to the "Services" link.
0. Within the main section, remove the second-level heading and paragraph of placeholder text.
0. Create the structure for "cards" you'll define visually with CSS, using appropriate HTML elements, classes, or ids.
    - Create a section to group the following:
        - An image.
        - A heading.
        - An explanation of the services provided.

## Style the Services page
1. Within the default style's CSS file, add a comment at the very top of the document about why you think 900px was chosen as the size to implement the CSS file. **HINT:** Think about the RWD principle about media queries being driven by content.
0. Style the mobile view and tablet view to:
    - Style each element appropriately with font information, color, box model, etc. Each section of the page (e.g. header, footer, main, etc.) should be visually defined. While color is one option, it is not the only option. 
    - Add comments at the beginning of each section to explain what you edited to display elements appropriate for the mobile and tablet files.
    - Utilize the selectors from the default styles as a basis.
        - You may need to modify the values of the properties to get things to look right and potentially add/remove other properties. 
    - Style the wrapper division element so that it is the full width of the viewport for mobile devices and tablets.
    > **TIP:** You can use the **Color Selection Tool** to generate different color schemes for each view. Note that you normally would not apply different color schemes to the different views in real world scenarios, but for the assignment, you will be required to do so to create additional visual differences between the three views.
