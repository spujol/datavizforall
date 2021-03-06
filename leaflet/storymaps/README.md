# Leaflet Story Maps with Google Sheets and Scrolling Narrative

*By [Ilya Ilyankou and Jack Dougherty](../../introduction/who.md), last updated September 28, 2017*

## Try it
Explore the map or right-click to [view full-screen map in a new tab](https://datavizforall.github.io/leaflet-storymaps-with-google-sheets/)
<iframe src="https://datavizforall.github.io/leaflet-storymaps-with-google-sheets/" width="90%" height=500></iframe>

The map pulls the point data and settings from a linked Google Sheet, which you can explore below or right-click to [view full-screen Sheet in a new tab](https://docs.google.com/spreadsheets/d/1AO6XHL_0JafWZF4KEejkdDNqfuZWUk3SlNlQ6MjlRFM/)
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSqxGs67j80rAPDZdQaS5jI0avn1qs2y5N8fOaeHUGvyrnIwBmWomlfAuujtvPrxtF-5FBZxi_KdTUm/pubhtml?widget=true&amp;headers=false" width="90%" height=500></iframe>

## Features
- Show map points, text, images, and links with scrolling narrative
- Free and open-source code template, built on Leaflet and linked to Google Sheets
- Fork the code and host your live map on the web for free with GitHub Pages
- Geocode location data with US Census or Google, using script inside the Google Sheet
- Easy-to-modify data and map options in Google Sheet tabs or uploaded CSV files
- Responsive design resizes your maps to display inside most mobile devices

## Create Your Own
- A) Fork (copy) the code template and publish your version with GitHub Pages
- B) File > Make a Copy of Google Sheet template, Share, and File > Publish
- C) Paste your Google Sheet URL in two places in your GitHub repo
- D) Modify your map settings in the Options tab and test your live map
- E) Geocode locations in the Points tab

To solve problems, see [Fix Common GitHub and Code Errors](../../github/fix) chapter in this book.

### A) Fork (copy) the code template and publish your version with GitHub Pages

**Before you begin**, this tutorial assumes that you:
- have a [free Google Drive account](http://drive.google.com), and learned the [File > Make a Copy in Google Sheets](https://www.datavizforall.org/spreadsheet/copy) tutorial in this book
- have a [free GitHub account](http://github.com), and understand concepts from the [Modify and Host Code with GitHub](https://www.datavizforall.org/github) chapter in this book

1) Right-click to open this GitHub code template in a new tab: https://github.com/datavizforall/leaflet-storymaps-with-google-sheets

2) In the upper-right corner of the code template, sign in to your free GitHub account

3) In the upper-right corner, click Fork to copy the template (also called a code repository, or repo) into your own account.
The web address (URL) of the new copy in your account will follow this format:
```
https://github.com/USERNAME/leaflet-storymaps-with-google-sheets
```

Reminder: You can only fork a GitHub repo **one time**. If needed, see how to make a second copy in the [Create a New Repo in GitHub](../../github/create-repo) chapter in this book.

4) In your new copy of the code repo, click on Settings, scroll down to the GitHub Pages area, select Master, and Save. This publishes your code to a live map on a public website that you control.

5) Scroll down to GitHub Pages section again, and copy the link to your published web site, which will follow this format:
```
https://USERNAME.github.io/leaflet-storymaps-with-google-sheets
```

6) Scroll up to the top, and click on your repo name to go back to its main page.

7) At the top level of your repo main page, click on README.md, and click the pencil icon to edit this file, written in easy-to-read Markdown code.

8) Delete the link to the current live site, and paste in the link to YOUR site. Scroll down and Commit to save your edits.

9) On your repo main page, right-click the link to your live map to open in a new tab. **Be patient** during busy periods on GitHub, when your website may take up to 1 minute to appear the first time.

### B) File > Make a Copy of Google Sheet template, Share, and File > Publish

1) Right-click to open this Google Sheets template in a new tab: https://docs.google.com/spreadsheets/d/1AO6XHL_0JafWZF4KEejkdDNqfuZWUk3SlNlQ6MjlRFM/

2) Sign into your Google account

3) File > Make a Copy of the Google Sheet template to your Google Drive

4) Click the blue Share button, click Advanced, click to change Private to Anyone with the link > Can View the Sheet. This will make your public data easier to view in your map.

5) File > Publish the Link to your Google Sheet to the public web, so the Leaflet map code can read it.

![Screenshot: File > Publish the link to your Google Sheet](lmwgs-file-publish.png)

6) At the top of your browser, copy your Google Sheet web address or URL (which usually ends in ```...XYZ/edit#gid=0```). Do NOT copy the published URL (which usually ends in ```...XYZ/pubhtml```).

![Screenshot: Copy the Google Sheet URL, not the Publish URL](lmwgs-copy-sheet-url-not-pub-url.png)

### C) Paste your Google Sheet URL in two places in your GitHub repo

1) First, connect your Google Sheet directly to your Leaflet Map code. In your Github code repo, click to open this file: ```google-doc-url.js```

2) Click the pencil symbol to edit the file.

3) Paste your Google Sheet URL into the code to replace the current URL. Do not delete the single-quotation marks or semicolon.

4) Scroll to bottom of page and press Commit to save your changes. Now the Leaflet Map code can locate your published Google Sheet.

5) Next, let's paste your Google Sheet URL in a second place to keep track of it. Go to the README.md file in your GitHub repo, click to open and edit, and paste your Google Sheet web address to replace the existing link near the top. Commit to save your changes.

### D) Modify your map settings in the Options tab and test your live map

In the top-level of your GitHub repo, test the new links to your map and your Google Sheet to make sure they work and point to your versions.

** TO DO - redo GIF **

In your linked Google Sheet, go to the Options Tab and modify these items:

1) Map Title -- insert your own title

2) Map Subtitle -- insert your own version

3) Author Name -- insert your own name, or first name, or initials (will be public)

4) Author Email or Website -- insert your own (will be public), or delete the current name to make it blank

Open the link to your live map in a new browser tab and refresh to see your changes.

### E) Geocode locations and customize new markers in the Points tab

In your new map, our next goal is to add and modify the appearance of a new set of point markers, based on new addresses that you will enter and geocode.

In the Points tab of your Google Sheet:

1) Do NOT delete or rename any column headers. However, you have the option to add new column headers to display in your map table.

2) Geocode your new data inside your Google Sheet by dragging your cursor to select 6 columns of data: Location - Latitude - Longitude - Found - Quality - Source

3) In the Geocoder menu that appears in this Google Sheet template, select one of the geocoding services. If one service cannot locate your data, try the other. Always inspect the accuracy of the Found column.

Open the link to your live map in a new browser tab and refresh to see your changes. If your new markers appear correctly, then delete the existing rows that came with this template.

## Learn more
To solve problems, see [Fix Common GitHub and Code Errors](../../github/fix) chapter in this book.

{% footer %}
{% endfooter %}
