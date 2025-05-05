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
  - [ ] **OPTIONAL:** Make warning messages if the mandatory fields are not filled.

## Part 2.5: Post functionality ❌
- [ ] Add "Comment" section (can't believe I forgot about this...)
  - [ ] When clicked, open the post to another page, where you can also see the location of the picture

---

## Part 3: Bird AI Picture Detector ❌
- [ ] Create .py script with the API
  - [ ] Add Python Rest API plugin in application
  - [ ] Make it work
  - [ ] Make a section on posts where the bird species is shown

---

## Part 4: Statistics ❌
- [ ] Create map section to see location of every post on platform
- [ ] ❗️Fix bug where the dates are not showing in order...(clearly it's something from the SQL query) 
- [ ] Tie API results to "Most seen 5 bird species" stats
- [ ] Use post coordinates to compute closest city
  - [ ] Add locations to "Top 5 locations" stats
 
---

## Part 5: Feedback and report functions ❌
- [ ] Add feedback condition
  - [ ] Add function that updates the bird showed on post
- [ ] Add report function
- [ ] Make validations
