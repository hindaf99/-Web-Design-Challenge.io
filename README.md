# Web-Design-Challenge


# Background
Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

# Before You Begin

1- Create a new repository for this project called Web-Design-Challenge. Do not add this homework to an existing repository.

2- Clone the new repository to your computer.

3- Inside your local git repository, add your html files, as well as your assets, Resources and visualizations folders. Your index.html should be the landing page that the user first sees.

4- Push the above changes to GitHub or GitLab.

5- Deploy to GitHub Pages.

# Latitude - Latitude Analysis Dashboard with Attitude
For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting weather data. In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

# Website Requirements
For reference, see the "Screenshots" section below. 
The website must consist of 7 pages total, including:

- A landing page containing:

   -- An explanation of the project. 
   -- Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

- Four visualization pages, each with:

  -- A descriptive title and heading tag. 
  -- The plot/visualization itself for the selected comparison. 
  -- A paragraph describing the plot and its significance.

 - A "Comparisons" page that:

  -- Contains all of the visualizations on the same page so we can easily visually compare them. 
  -- Uses a Bootstrap grid for the visualizations.

        The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

- A "Data" page that:

  -- Displays a responsive table containing the data used in the visualizations.

       The table must be a bootstrap table component. Hint

       The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here

The website must, at the top of every page, have a navigation menu that:

- Has the name of the site on the left of the nav which allows users to return to the landing page from any page. 
- Contains a dropdown menu on the right of the navbar named - --  - "Plots" that provides a link to each individual visualization page.
-  Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page. 
-  Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

Finally, the website must be deployed to GitHub pages. When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.
Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

# Considerations

- You may use the weather data or choose another dataset. Alternatively, you may use the included cities dataset and pull the images from the assets folder.
-  You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
-   You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
-    Be sure to use a CSS media query for the navigation menu. 
-    Be sure your website works at all window widths/sizes.
-     Feel free to take some liberty in the visual aspects, but keep the core functionality the same.



# Screenshots
This section contains screenshots of each page that must be built, at varying screen widths. These are a guide; you can meet the requirements without having the pages look exactly like the below images.

# Landing page
Large screen:

![image](https://user-images.githubusercontent.com/83431185/145302786-15502cc1-0ba7-496d-8075-49b61ae0ebaa.png)

Small screen:

![image](https://user-images.githubusercontent.com/83431185/145302805-0b7ffe41-477b-479d-bea6-76427e9c7d29.png)


# Comparisons page
  Large screen:

![image](https://user-images.githubusercontent.com/83431185/145302875-01c49d71-a3ac-486a-91be-7ebc1f183ba3.png)

Small screen:

![image](https://user-images.githubusercontent.com/83431185/145302894-e462df90-7cc9-4cce-b3f1-fcf6387d122a.png)


# Data page
 Large screen:

![image](https://user-images.githubusercontent.com/83431185/145302972-1c30f911-6fee-4f66-8dee-f10264d31e35.png)

Small screen:

![image](https://user-images.githubusercontent.com/83431185/145303052-1b04b749-e83c-468b-a877-d3280cb8479a.png)

# Visualization pages
 You'll build four of these, one for each visualization. Here's an example of one: Large screen:

Small screen:

![image](https://user-images.githubusercontent.com/83431185/145303109-8472ab2f-8360-4d7b-b87b-3327d45c591a.png)

Navigation menu Large screen:

Small screen:

![image](https://user-images.githubusercontent.com/83431185/145303129-b8ece4cf-bba3-4995-b1ae-b90dcea51edc.png)

# Navigation menu
Large screen:

![image](https://user-images.githubusercontent.com/83431185/145303295-8e6c176c-e6bf-4ec9-99ae-7c5711911f23.png)

Small screen:

![image](https://user-images.githubusercontent.com/83431185/145303316-cd58710e-9140-4de6-8cce-74fea9dfbac2.png)

