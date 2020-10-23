# Lambda Foundations

## Module 3 - CSS - Foundations

### Module 3 Project

Today we learned about more about styling in CSS, we also learned about specificity and inheritance. CSS can be a tricky language to master because there are always multiple ways to achieve the same result. While learning it's best to focus on one technique at a time. In this project, we are going to work on our skills by adding the proper spacing to elements. We will be building a mock-order history page for an imaginary web store.

### Getting Started

In order to get started you will need to download this project as a .zip file and open it in VS Code (like Modules 1 and 2). Here are the instructions to do so:

1. Click on the Green button that says Code in the upper right-hand side of the screen.
2. You will see an option at the bottom called Download Zip.
3. You will need to find the place the .zip file is downloaded to. This will usually be the Downloads folder on your computer. Tip: if you are using Chrome, you should be able to click on the download itself in the bottom left-hand corner of your browse, this will open the location of the downloaded file in My Computer or Finder.
4. Double-click on the .zip file itself. Once you unzip the file you should see a Folder or Directory with the name "Web-Foundations-Module-3" next to the .zip file.
5. Either drag and drop the entire folder onto the VS Code icon, OR open VS Code -> click on File > Open -> Find the folder from step 4 -> Click open.
6. Open the index.html file in your browser. In most cases you can drag and drop the HTML file directly to your open browser screen.

### Analyze the Code

Before you open the project, one thing to note. A LOT of code has already been written. This may be overwhelming at first, that's OK! Take a moment and just analyze the code that has already been written. Are there elements that you recognize? Are there elements that you've never seen before? Take note of these things. A major skill in software development is learning to read the code that is already there and figuring out where to insert your own code. We've done that step for you today but as an exercise try and answer the questions below:

1. In `index.html`, replace "Your Name" with your actual name.

2. In `index.css`, on line 53 what do each of the numbers represent for the margin?

   The first 0 represents the top margin, 50px is the right margin, the second 0 is representing the bottom margin and the last number is 10px for the left margin. 

3. In `index.css`, which selector is more specific, line 106 OR line 114? Why?

   The first selector is more specific in this case because display: flex effects both selectors and the child and the second selector and its properties do not contradict the first selector so they would be evenly specific.  Also the second selector seems to be a } and I'm sure what that means but it still likely doesn't effect the first.   

4. In `index.css`, on line 2, what is this CSS property doing?

   Everything is a box. This property is a way to resize those boxes based on margin and padding within the border of the box.

5. In `index.css`, on which line is the total price of the binoculars (`index.html` line 57) being styled?

   The total price is being styled on lines 212-214 in index.css.

### Try it out

For this try it out exercise you will be focusing your attention on `index.css` and making sure the page is properly spaced, and borders look correct. You can find instructions on where to start on line 261. You can also use the following image as a guide. One note: there are many ways to achieve the same style in CSS. Often spacing can be the most difficult part of writing CSS. Don't get overwhelmed thinking about the entire project as a whole. This is a fantastic opportunity to practice breaking down a large problem into much smaller manageable bits. So, take your time and focus on one piece at a time.

[Link to Guide Screenshot](Project/assets/GuideScreenshot.png)

You can also find this Screenshot in the assets folder in this project.

### Go further

In this section, we'd like you to take your learning into your own hands! It is an important skill to be able to find the answers you are seeking on the internet while working on a software project. In today's case, Google will be your friend. We've highlighted some potential Google search phrases, but try to think of how you would word your search on your own.

1. Pseudo classes and selectors. CSS allows us to write styling based on interaction from the user. Research `CSS pseudo-classes`. Utilize the `hover` pseudo-class and change the background color of the elements with the class `sub-nav-item` when a user hovers their mouse over the element.

2. Different color types. CSS allows us to use many different values. Research colors and write the names of three different `CSS color pattern values` below:

1. cornflowerblue, #6495ED, rgb(100,149,237)
2. indigo, #4B0082, rgb(75,0,130)
3. cornsilk, #FFF8DC, rgb(255,248,220)

### In Your Own Words

An impactful technique in learning something new is attempting to reiterate the concepts you just learned from memory in your own words. This allows you to highlight areas you are not comfortable with and could study on a little more. We'll start this exercise off pretty simply. Just remember that this is merely an exercise, there are no right or wrong answers here. Please answer the following question in your own words

1. Name the 4 parts of the box model and describe what each means.

1. content: this is the meat that the box model is surrounding

2. padding: the distance between content and border
3. margin: this is the outer most layer that interacts with other objects on the page

4. border: this is the layer that is between the padding and the margin

2. What does the acronym 'CSS' mean?

Cascading Stylesheet

### Complete the Assignment

Once you are completed with all of the above exercises, find the Folder `Web-Foundations-Module-3` in your Finder or My Computer. Right-click on the folder and select "Compress Web-Foundations-Module-3". This will create a .zip file. Upload this .zip file to Canvas the same way you uploaded your .txt file yesterday.
