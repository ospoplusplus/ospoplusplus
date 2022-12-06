---
name: Adding an Event to the Website
about: Use this Issue Template to get a checklist instructing you how to add an event
title: ''
labels: ''
assignees: ''

---

- [ ] Go to https://github.com/ospoplusplus/ospoplusplus/tree/main/static/images/events  
- [ ] Create new branch
     - [ ] Click on the main button at the top left of the page
     - [ ] In the Find or create a branch field type a name for the branch using - or _ instead of spaces (e.g.: new_event)
     - [ ] Click on Create branch: new_event from ‘main’
- [ ] Add the image of the event to the repository
     - [ ] Download the slide you created as a .png 
     - [ ] Rename the image on your computer to cc-yyyy-mm-dd.png (where yyyy is the year of the event, mm is the month and dd is the day) cc - stands for community call and wp stands for workshop.
     - [ ] Go back to Github and on the left click on Add file
     - [ ] Then click on Upload Files
     - [ ] Drag and Drop the image in the space provided 
     - [ ] In the Commit changes section type a title describing what you are doing (e.g. Adding image for a new event) you can also add an optional description.
     - [ ] Click on Commit changes
- [ ] Create a new event
     - [ ] In the list of folders and files click on content -> events
     - [ ] On the left click on Add file
     - [ ] Then click on Create new file - a new text file will open on screen.
     - [ ] On top of the text file there is a text box saying Name your file… type here cc-yyyy-mm-dd.md (where yyyy is the year of the event, mm is the month and dd is the day) cc - stands for community call and wp stands for workshop.
     - [ ] Copy and paste the following text in the file, including the - - - at the top and excude the ". Replace the information included in ( ). Delete the ( ) after populating the information.

     "---
    
     title: (insert title)
    
     type: redirects
    
     redirect: "(eventbrite link)"
    
     image: "/images/events/(cc-yyy-mm-dd.png)"
    
     date: (yyyy-mm-dd)
    
     draft: false
    
     tags: ["OSPO"]
    
     "---
    
     (Short event description - 1 sentence)


     - [ ] At the bottom of the page Name your commit and provide an optional extended description
     - [ ] Click on Commit new file
- [ ] Create a pull request
     - [ ] Click on <> Code button on the top left of the page.
     - [ ] You will see an orange box with the name of the branch you created. 
     - [ ] Click on the Compare & pull request button within that box
     - [ ] Give the pull request a Name - you can keep the pre-populated event name
     - [ ] Write a description of what you have changed in the Leave a comment text box. 
     - [ ] On the right, click on Reviewers and select Diren and Clare from the list
     - [ ] Click on the Create pull request button
