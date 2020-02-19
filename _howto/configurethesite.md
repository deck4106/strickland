---
layout: howto
title: How To Configure the Website
---

Below are a few quick steps to help you begin configuring your GitHub site for use with Oral Histories as Data (OHD). 

## Step 1: Make a Template of OHD

- Go to the OHD homepage and click on the "Template" button toward the top right of the page. 
{% include bootstrap/figure.md img="howto/ohd_template.png" caption="" alt="picture of the button that enables user to create a new template in github" class="w-50" %}
- You'll need to then name your repository.
{% include bootstrap/figure.md img="howto/name_repository.png" caption="" alt="image of the field users must fill out in order to create a name for their new template" class="w-50" %}
- Once you've named your repository you'll need to click the "Create Repository From Template" button. 
{% include bootstrap/figure.md img="howto/create_repository_button.png" caption="" alt="picture of the create repository button located at the bottom of the page" class="w-50" %}

## Step 2: Create a New File

- Now you'll need to go into you "data" folder and then into the "transcripts" folder in your repository. 
- Once in transcripts click on "create new file".  
{% include bootstrap/figure.md img="howto/new_file.png" caption="" alt="picture of the create new file button in the newly created repository" class="w-50" %}
- Now you need to name your file according to your transcript. ***THIS 
{% include bootstrap/figure.md img="howto/name_file.png" caption="picture of the required field for naming your new file" alt="" class="w-50" %}

{:.alert .alert-warning}
When you name your file be sure to include the type of file after the name you choose. For example, if it is a mark down file, attach ".md" after the file name. In our case, you'll want to add a ".csv" to the end of the filename. (robert.csv)
- Leave the file open on the page. We'll be adding to it via the next step.

## Step 3: Moving the Transcript to a new GitHub file

- Open your transcript  

{:.alert .alert-danger}
Make sure you open your transcript in a text editor. DO NOT OPEN UP THE CSV IN EXCEL!!! Excel might reformat your timestamps. Here at OHD, we prefer using [Visual Studio Code](https://code.visualstudio.com/), but notepad or textedit (the default text editors on Windows and Mac machines, respectively) will also work. 
- Open the transcript in a text editor. 
- Select the entire text (ctrl + a) 
{% include bootstrap/figure.md img="howto/text_editor.png" caption="transcript selected in text editor" alt="" class="w-50" %}
- Copy and paste it into the new file open you created in step 2. 
{% include bootstrap/figure.md img="howto/github_pasted-transcript.png" caption="completed .csv file" alt="" class="w-50" %}
- Commit the change at bottom of page by scrolling to the bottom of the page and click "commit new file". 
{% include bootstrap/figure.md img="howto/commit_file.png" caption="" alt="" class="w-50" %}
- Below is what the CSV should look like after you've committed it on the GitHub webpage. 
{% include bootstrap/figure.md img="howto/github_csv.png" caption="This is how the CSV should look after you paste it into the new file and commit it." alt="complete and committed csv in github" class="w-50" %}

{:.alert .alert-warning .mb-4}
NOTE: If the CSV has a problem, GitHub will show you an error message that will say: "We can make this file beautiful and searchable if this error is corrected:" After that phrase, they will also point out a line number that is causing the problem. Open the file up by clicking on the pencil icon in the top right of the file area. Go to the line indicated and see if there's an obvious error. If you can't get it fixed, go back to your Google Sheet and see if there's anything to clean up. Even if there is nothing wrong, re-download the file as a CSV, open it in a text editor, then copy and paste it back into the problematic file on GitHub. Hopefully one of these steps clears up the problem. 

## Step 4: Setting up the visualization(s)

{:.alert .alert-info}
OHD offers a way to categorize your transcripts using tags. This is done through two locations: the "tag" column cells in your transcript's CSV and the filters.csv file, which is already provided for you in the structure of OHD. If you are not aware of either of these files, first visit our steps on "[How To Prepare Your Data](prepareyourdata.html)." 

- Open the filters.csv file you created
- Navigate to the "_data" folder 
- Open the "_data" folder and click the pencil icon to edit the file
- Copy and paste the filters.csv you created in the Prepare Your Data tutorial over into the existing content. 
- Alternatively, you can simply edit the CSV file here. (Below is how the file looks when opened with the pencil icon.)
{% include bootstrap/figure.md img="howto/filters_csv2.png" caption="Filters.csv as it looks in a text editor" alt="opened file, ready for editing" class="w-50" %}
- Commit the change at the bottom of the page by clicking the commit button (you can write a message for the commit if you'd like to remember what you've done)
{% include bootstrap/figure.md img="howto/commit_file.png" caption="" alt="picture of the commit button at bottom of page" class="w-50" %}
- However you edited it, the finished CSV should look like the below (with your new tags and descriptions) in GitHub
{% include bootstrap/figure.md img="howto/filters_github.png" caption="CSV after being transferred to GitHub" alt="finished csv after being transferred to github" class="w-50" %}
- Once you generate the website with your next step, your finished visualization will look something like this: 
{% include bootstrap/figure.md img="howto/visualization.png" caption="finished OHD visual" alt="picture of finished visualization" class="w-50" %}

## Generate Your Site

- Go to the settings button at the top right of your repository page
{% include bootstrap/figure.md img="howto/settings_button.png" caption="" alt="settings button homepage of repository" %}
- Scroll down to the "GitHub Pages" section
- Change source dropdown button from "none" to "master" and copy the URL they give you. 
{% include bootstrap/figure.md img="howto/source_button.png" caption="" alt="picture of source drop down menu" class="w-50" %}
- It will take several minutes for the new website to build, while your waiting go back to the main page and click the "edit" button on your repository page
{% include bootstrap/figure.md img="howto/edit_button.png" caption="" alt="picture of the edit button above your repository" class="w-50" %}
- Add the copied url to the website section and click "save" 
{% include bootstrap/figure.md img="howto/url.png" caption="" alt="picture of save button" class="w-50" %}
- This will let you easily access the generated site whenever you come to edit the page. 
- Check out your new site by clicking on the link. Refresh if nothing shows up. Congratulations on setting up your own oral history site!

