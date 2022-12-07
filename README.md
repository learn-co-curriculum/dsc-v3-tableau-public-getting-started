# Tableau Public I - Getting Started 

## Introduction
In this lesson we will learn the first steps for getting started with Tableau Public. First, you will create a Tableau account and download Tableau to your computer. Then, we will launch the Tableau environment and explore the user interface. All of this begins at the Tableau __Start page__. Learning the core components of the Tableau Start page will build a foundation to begin creating visualizations and dashboards in the upcoming labs.

## Learning Objectives
* Download and install Tableau Public
* Identify and recognize the core components of the Start page
* Connect to a data source to create and save a new Tableau workbook

## Download and Install Tableau Public

### 1. Create a Tableau Account
To use Tableau Public, visit the [Tableau website](https://public.tableau.com/s/) and select the button  __Sign Up for Tableau Public__ in the red rectangle, pictured below.
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-1.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
</div>


### 2. Download Tableau
* Once you have created and signed into your account, [follow this link](https://www.tableau.com/products/public/download) and select __Download Tableau Public__ (pictured below in the red rectangle). 
* Follow the prompts to download and install Tableau Public to your computer.
* Finally, restart your computer and launch the Tableau environment from your desktop.
<br>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-2.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
</div>

## Core Components of the Start Page
When Tableau opens, you will be on the __Start page__. It should look like the image below.
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-3-start.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
</div>


From the Start page, you can:
* connect to data sources to create new Tableau __workbooks__
* open existing workbooks
* find Tableau resources like videos, tutorials, blogs, and sample data sets

In the image below, each of the components of the Start page are labeled with a number. Use the guide below the image to learn about each component.
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-4-start.png" alt="This is the alt-text for the image." height=350/>
</td></tr></table>
</div>

### 1. Tableau icon
On the top left of the Start page you will find the __Tableau icon__ (1).
The Tableau icon will create a new notebook _without_ first connecting to a new data source if you are on the Start page. It will perform other functions in different areas of the Tableau interface, which we will cover in the __Data Source page__ section below.

### 2. Connect
Displays data connection options, for example:
* __To a File__ which allows you to connect to a local file based data source. This could be files such as Microsoft Excel spreadsheets, CSV files, and JSON files. Tableau can even extract tabular data from spreadsheets on PDF files

* __To a Server__ which allows you to connect to __remote storage options__ like a Google Drive. You can also connect to relational databases via Data and and Web Data connector.

### 3. Open
* Displays the locations where Tableau work can be retrieved and edited.
* Right now, it is empty because we have not created any workbooks yet.
* In the future, you can __Open from Tableau Public__ to sign into your account and retrieve workbooks from the Tableau Public website.

### 4. Discover
* __How-to-Videos__ demonstrate how to use Tableau.
* __Viz of the Day__ brings you to Tableau Viz of the Day where you can get inspiration for new visualizations.
* __Resources__ provides links to Tableau's blog, sample data sets, as well the current status of the server pod where your Tableau Public account is hosted.

In  this lesson, we will primarily focus on the __Connect__ and __Discover__ panes of the start page.

<div class="alert alert-success">
<h3>Your Turn: Connect to Data and Create a Workbook</h3>
    <br>
<b>1. Access Tableau Resources from the Discover Pane</b>
    <br>
In the lower right corner of the Discover pane there is a section called <b>Resources (1)</b>. Click on the <b>Sample Data Sets (2)</b> link.
    <br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-5.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
            </center>
</div>    
<br>
    
<b>2. Download Superstore Sales Data</b><br>
    The <b>Superstore Sales</b> data set is one that we will be working with in future lessons, so take a moment to download it now by selecting the link pictured below. When you click on the link a dialogue box will open to chose the location to save the file. For ease of access, choose the <b>Datasources</b> folder in the <b>My Tableau Repository</b> directory (<b>__Documents/My Tableau Repository/Datasources/Sample - Superstore.xls</b> was automatically created when you installed Tableau). If Sample - Superstore.xls already exists in your /My Tableau Repository/Datasources directory, it is OK to overwrite it.
    <br>
<div>
        <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-6.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center> </div>
<br>

<b>3. Connect to Data to Tableau</b><br>
Next, we will navigate to the <b>Connect pane (2)</b> in the upper left-hand corner of the screen, directly below the <b>Tableau icon (1)</b> and select  <b>To a File > Microsoft Excel(3)</b>. 
    <br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-7.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="height: 400px;"/>
    </td></tr></table> </center>
</div>    
<br>
Then, use the Open dialogue box to retrieve <b>Documents/My Tableau Repository/Datasources/en_US-US/Sample - Superstore.xls</b>. 
    <br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/open-dialogue.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>    
<br>

<b>4. Launch the Data Source Page</b><br>
After completing the steps above, Tableau will launch the <b>Data Source page</b>. Now, Your screen should look something like this:
    <br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/lesson1/tab-1-8.png" alt="Image of the sheets tab in the lower left corner of the Tableau Data Source Page, with the Left Pane and Canvas visible." alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>    
<br>
    </div>

## Summary
In this lesson we created a Tableau account and downloaded and installed Tableau Public.
Then, we identified the core components of the __Start page__. Next, we used the __Discover pane__ to locate Tableau Public __Resources__ and download and the __Superstore Sales__ data set. Finally we used the __Connect__ pane to retrieve the downloaded dataset and create a new __Tableau workbook__. If possible, keep Tableau open as you move on to the next lesson so we can move right into describing the Data Source page. 

In the next lesson, we will explore more elements of the Tableau Public interface by identifying and describing the core components of the __Data Source page__. Then, we will launch the Tableau workspace and begin creating worksheets.
