# checklist-bachelor-project
A checklist with TODO's for my Bachelor's project, since it is easier for me to keep the list somewhere and see my progress so far.


## Part 1: Login - Register Form ✅

- [x] Login working (by default in APEX)
  - [x] Link login process to SM_USERS
  - [x] Make a "Forgot Password" field
  - [x] Make the application send a verification code on the email
    
- [x] Make SQL table for users (SM_USERS)

- [x] Finish Register Page
  - [x] Add field for confirm password
  - [x] Validations
  - [x] Create Authentication scheme in APEX Shared Components
      
 ---    

## Part 2: Create new Post Form ✅
- [x] Make all buttons functional
  - [x] Make pin appear on location selector
  - [x] ❗️Fix bug where you can't like/unlike posts after you closed map and "create new post" form
  - [x] **OPTIONAL:** Make warning messages if the mandatory fields are not filled.

## Part 2.5: Post functionality ✅
- [X] Add "Comment" section (can't believe I forgot about this...)
  - [x] When clicked, open the post to another page, where you can also see the location of the picture

---

## Part 3: Bird AI Picture Detector ❌
- [x] Create .py script with the API
  - [X] ❗️Fix bug where it accepts only .jpg/.jpeg files
- [X] Make the tunneling thingy for ngrok
- [ ] Make PL/SQL Dynamic Action 
  - [ ] Make a section on posts where the bird species is shown

---

## Part 4: Statistics ❌
- [x] Create map section to see location of every post on platform
- [x] ❗️Fix bug where the dates are not showing in order...(clearly it's something from the SQL query)
- [ ] Tie API results to "Most seen 5 bird species" stats
- [x] ~Use post coordinates to compute closest city~  **this was a bit vague, I will explain in the following checked items what I did**
- [x] Find API for reversed geolocation
- [x] Create Dynamic Action in PL/SQL which calls the API
  - [x] Add locations to "Top 5 locations" stats
 
---

## Part 5: Feedback and report functions ✅
- [x] Add feedback condition
  - [x] Add function that updates the bird showed on post
  - [x] Make the app send notifications to the user who got their post deleted/changed 
- [x] Add report function
- [x] Make validations

---

# PROGRESS: 29/32 (~ 90% DONE) ❌
