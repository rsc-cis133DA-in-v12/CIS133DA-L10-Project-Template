# Lesson 10 Project
The computer company client is pleased with the layouts you've created for them so far. This week, the company would like you to focus on creating visual elements for viewers using HTML and CSS to display "cards" side-by-side with more in-depth descriptions about the services they provide. Since the client's users and employees will access the website on different personal devices, they'd like you to use what you learned about responsive web design to make sure the layout of the page looks good for mobile, tablet, and larger devices.

## Project Prep
1. If you haven't done so already, clone the repo to your computer within your course folder.
2. Open the repo within VS Code. You can open this `readme.md` file within VS Code to view the project directions there. 

   > **TIP:** Right click on the file and choose the `Open Preview` option.
3. If there are files and folders present other than this `readme.md` file, take some time to familiarize yourself with the files within the repo so you know where they are located. This will help you when asked to use them within the project directions.

   > **TIP:** Before beginning any work on the project, read through all the steps to understand what you will be doing.

<br>

***
**IMPORTANT: Be sure to Save and Sync your work to GitHub regularly, applying appropriate Commit comments as you go.**
***


## Adjust the Template

> **ASSIGNMENT TIP**<br>As you work on the styling for this assignment and future assignments, you should load the web page within your browser instead of using the preview window in VS Code. Then use the built in developer tools to simulate the different viewports that each CSS file will target. As you make adjustments to your CSS, see how it looks in the different viewports. Review the [Responsive Web Design](https://riosalado.coursearc.com/content/cis133da-in-v12/lesson-10-css-at-rules-and-media-queries/responsive-web-design/) page in Lesson 10 for information on how to use the browser tools if needed. 

1. Open the template.html file from your Lesson 10 Project Repository.
2. Add the necessary viewport metadata so the viewport width is equal to the device width and that the initial scale is set to 1.
3. Modify the existing link to the external Default stylesheet to include a media query that detects when the device is larger than 900px.
    > **TIP:** When you first load the page and look at the different viewport sizes the styles should disappear entirely except for a viewport larger than 900px since there are no mobile or tablet styles.
4. Create a link for an external Mobile stylesheet titled `mobile_style.css`. You will be creating the actual CSS file later in the project. For now, just create the link. Add a media query to the link that will load this mobile stylesheet for any device that is **smaller than 450px**.
5. Create a link for an external Tablet stylesheet titled `tablet_style.css`. You will be creating the actual CSS file later in the project. For now, just create the link. Add a media query to the link that will load this tablet stylesheet for any device that is **smaller than 900px**.
    > **TIP:** You must think through how to properly apply the tablet CSS file. If the media query is not designed correctly, it will override the mobile version and the mobile file will never be used.

## Create the Services Page
1. Save a copy of the Template to your Lesson 10 Repo folder as: **services.html**
2. Open the newly created services.html file.
3. Update the HTML comment to add your section number and the lesson number.
4. Update the metadata with the following: 
    - Change the title to: **Our Services**
    - Define the author using your first and last name.
    - Add a minimum of 5 keywords appropriate for the page content.
    - Add an appropriate description.
5. Apply the **active** class to the "Services" link.
6. Within the Main section, insert three separate DIV elements. These will serve as "cards" that will be defined visually with CSS later on. Apply a class to each div so that you can target them with your CSS. Within each div, include the following elements:
    - an image element that will display a 100px by 100px image. The image files for these elements can be found in the images directory within your Lesson 10 repository.
    - a heading that displays the name of the service.
    - a paragraph that contains a brief description of the service.
7. Use the following information for each of the three cards:
<table>
    <tr>
        <th>Image File</th>
        <th>Service Name</th>
        <th>Service Description</th>
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
1. If necessary, open the `default_style.css` file.
2. Update the multi-lined comment to add your MEID as the Author, course and section number, and current lesson number.
3. Above the Footer Styles, add appropriate selectors, ids, or classes to style each div group to look like a "card" using the following steps. Refer to the example below as a guideline.
    1. Display two cards side-by-side horizontally.
    2. Apply a white background color to the container.
    3. Push the cards away from each other by the same value on all sides.
    4. Add the following styles to the card images:
        - Float the image to the left of the container. 
        - Apply a bright background color of your choosing.
        - Increase the white space so the background color is clearly visible on all sides of the element.
        - Adjust the width of the element to be 100px.  
        - Push the elements to the right of the card images by 5px.
    5. Remove the margin from the second-level heading and paragraphs.
    6. Increase the white space for the second-level heading and paragraphs for overall readability.
    7. Adjust the font size of the second-level heading and paragraphs so that the text fits within the container.

Compare your image to the following example - your colors may vary:

### Example Project

![Screenshot of example Services page](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L10-example1.png)

## Create a Responsive Design
Be sure to save your changes to your styles. Now would be a good time to Sync your project to GitHub if you have not done so recently.

At the beginning of this project, you identified the breakpoints for your responsive design when you added your media queries. You set them at 450px for mobile, and 900px for tablets. As you learned in this lesson, using set values for breakpoints is not best practice. Rather, you should examine your website and determine at what point your design falls apart. This is where you should define your breakpoints. Using the skills and techniques covered in this lesson on the [Responsive Design](https://riosalado.coursearc.com/content/cis133da-in-v12/lesson-10-css-at-rules-and-media-queries/responsive-web-design) page, determine at least 2 breakpoints for your web page. One should be aimed at mobile users, and one should be aimed at those using tablet devices.

1. Create two copies of the `default_style.css` file.
    - Rename one file to `mobile_style.css` and the other file to `tablet_style.css`.
2. Within the default styles, add a comment to identify the breakpoint value for this stylesheet, i.e., at what point will this stylesheet be used.
3. Within the mobile styles and tablet styles, add a comment at the top explaining when the CSS file will be loaded by the browser.
4. Style the main division element so that it is the full width of the viewport for mobile devices and tablets.
5. Apply appropriate changes to the navigation bar so that each link is clearly visible for mobile devices and tablets.
6. Apply appropriate changes to the display of your card elements so that they fully display for all devices.
7. Change the background-color for the footer in each of your stylesheets. This is so that your Instructor can easily view your breakpoints and media queries.
    - If needed, you may make adjustments to your HTML to make your design exactly how you want it. 
    - Add comments at the beginning of each section to explain what changes you made to make the content look good and why you made the changes you made.

### Example Project Showing 3 Different Breakpoints
***Your breakpoints may be different, so your site may look different. The footer color has been adjusted to visually confirm the application of each media query.***

![Screenshot of example Services page](https://raw.githubusercontent.com/rsc-cis133DA-in-v12/CourseResources/main/L10-example2.png)
    
## Submit the Project
Once you have completed your project, you need to let your instructor know that it is ready to be graded. This is done by submitting the Repo URL to the assignment in RioLearn.

   > **TIP:** If you need a refresher on how to submit your work, view: [Submitting Assignments & Viewing Feedback](https://riosalado.coursearc.com/content/cis-public/git-github-and-vs-code/submitting-assignments-and-viewing-feedback).
1. Review your work and make any necessary updates. Save the file. You can either select **FILE>SAVE** or use the keyboard shortcut **CTRL+S**.
2. **Sync** the changes and apply a final **Commit** that says: `Completed final review and updates before submission.`
3. Verify that all files appear on GitHub.

   > **TIP:** You can view any of your repos by going to the GitHub organization for the course - [RSC-CIS133DA-IN-V12 Organization](https://github.com/rsc-cis133DA-in-v12). Once you are viewing the class organization, you should see all of the Repos that you have accepted assignment invitations for. It is recommended that you bookmark this page for future reference. Push (i.e., sync) the files on your computer with GitHub to ensure all files are uploaded to GitHub for your instructor to view.
4. Right-click the link to your repository and select **Copy Link Address**.
5. Go to the Assessing Your Learning page in your RioLearn lesson, and click the link to submit the assignment. Paste the link to your repo in the assignment submission box.
