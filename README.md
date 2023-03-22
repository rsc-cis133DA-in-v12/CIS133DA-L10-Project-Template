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

> **ASSIGNMENT TIP**<br>As you work on the styling for this assignment and future assignments, you should load the web page within your browser instead of using the preview window in VS Code. Then use the built in developer tools to simulate the different viewports that each CSS file will target. As you make adjustments to your CSS, see how it looks in the different viewports. Review the **Responsive Web Design** page in Lesson 9 for information on how to use the browser tools if needed. 

1. If necessary, open the Template from your Lesson 9 folder.
2. Add the necessary viewport metadata so the viewport width is equal to the device width and that the initial scale is set to 1.
3. Modify the existing link to the external Default stylesheet to include a media query that detects when the device is larger than 900px.
    > **TIP:** When you first load the page and look at the different viewport sizes the styles should disappear entirely except for a viewport larger than 900px since there are no mobile or tablet styles.
4. Create an link for the external Mobile stylesheet to:
    1. Apply a media query to load the mobile style CSS for any device that is smaller than 450px.
5. Create an link for the external Tablet stylesheet to:
    1. Apply a media query to load the tablet style CSS for any device that is smaller than 900px.
    > **TIP:** You must think through how to properly apply the tablet CSS file. If the media query is not designed correctly, it will override the mobile version and the mobile file will never be used.
0. Save your changes and then save a copy of the Template to your Lesson 9 folder as: **services.html**
0. Open the Services page from your Lesson 9 folder, if necessary.
0. Update the HTML comment to add your section number and the lesson number.
0. Update the metadata with the following: 
    1. Change the title to: **Our Services**
    0. Define the author using your first and last name.
    0. Add a minimum of 5 keywords appropriate for the page content.
    0. Add an appropriate description.
0. Apply the **active** class to the "Services" link.
0. Within the Main section, create an HTML layout structure for "cards" you'll define visually with CSS later on. Utilize the appropriate HTML elements complete the following:
    1. Display an image.
    0. Display the name of the service using an appropriate heading.
    0. Add a description of the service.
    0. Group the image, service name, and description in a generic container.
0. Create two other cards to display a total of three cards.
0. Insert the following as information for each appropriate card:
<table>
    <tr>
        <th>Image File</th>
        <th>Service Name</th>
        <th>Service description</th>
    </tr>
    <tr>
        <td>computer.png</td>
        <td>Computer Diagnostic & Repair</td>
        <td>We can evaluate your PCs to provide: physical cleaning, malware and antivirus solutions, hard drive replacement, and data recovery.</td>
    </tr>
    <tr>
        <td>presentation.png</td>
        <td>Business Consultation</td>
        <td>We will work with you to find custom solutions for your office set-up design including network, servers, phones and internet solutions.</td>
    </tr>
    <tr>
        <td>cloud-data.png</td>
        <td>Secure Cloud Backup</td>
        <td>We take care of cloud backup solutions for our customers, including free support, and built-in spam and virus scan filters.</td>
    </tr>
</table>

## Style the Services page
1. Within the default styles, add a comment to identify the breakpoint. **HINT:** Think about what you learned about the RWD principle: media queries are driven by site content.
0. Above the Footer Styles, add appropriate selectors, ids, or classes to style the card layout you created for the services page.
    1. Change the display of the card division elements so that two cards will appear side-by-side.
    0. Float the image to the left of the container.
    0. Apply a background color to the image and adjust the padding so the background color is clearly visible on all sides of the element.
    0. Remove the margin from the second level heading and paragraphs.
    0. Apply any additional CSS to apply background colors, margins, padding, margins, etc. to display as cards. See the example below *Note that the example is a rendering and that your cards may not appear the exact same.
    
    ![]()


## Style the Mobile and Tablet Views
1. If necessary, open the mobile and tablet style sheets.
0. Style each section of the page (e.g. header, footer, main, etc.) so that each section visually defined. While color is an option, to visually define each section, utilize appropriate font information, color, box model, etc. to make the changes obvious.
0. Add comments at the beginning of each section to explain which elements you edited.
0. Utilize the selectors from the default styles as a basis.
    >**TIP:** You may need to modify the values of the properties to get things to look right and potentially add/remove other properties. 
0. Style the wrapper division element so that it is the full width of the viewport for mobile devices and tablets.
    > **TIP:** You can use the **Color Selection Tool** to generate different color schemes for each view. Note that you normally would not apply different color schemes to the different views in real world scenarios, but for the assignment, you will be required to do so to create additional visual differences between the three views.

## Submit the Project
Before you submit your project:
1. Save your files and apply any final commits to your work.
0. Push (i.e., sync) the repo on your computer with GitHub to ensure all files are uploaded for your instructor to see.
0. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [CIS133DA Course Organization](https://github.com/rsc-cis133DA-in-v12). You can bookmark the page for future reference. 
0. Open the Pull Requests tab within GitHub (or using the GitHub Extension within VS Code).
0. In the comment field, 
   - Type in your instructor's username with an `@` before. See the course announcements for their username to use. 
   - Put a note to your instructor that the assignment is ready to grade.
0. Click on the `Comment` button to finalize and submit your assignment to GitHub for review.
0. Lastly, submit the Project to your **Gradebook** using the steps within **Assessing Your Learning** in Lesson 10.