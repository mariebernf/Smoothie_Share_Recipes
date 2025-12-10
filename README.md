# Smoothie_Share_Recipes
Smoothie recipe sharing app

## Description

Smoothie Share is a web application where users can create, share, and find smoothie recipes. It is user friendly, and its easy navigation means users can easily sign up or login. When logged in users can add new smoothies. Users can only add, edit and delete their own recipes when logged in. They can not change other users recipes. Smoothie ingredients are shown only for logged in users. This will encourage people to sign up.

## Project requirments

The project requirements are to create and deploy a data centric web application using Django. Users must be able to log in and perfum CRUD operations, Create, Read, Update and Delete. The site should be user friendly and responsive. It must be deployed on Heroku.

## User stories

| User Story | Requirement Met | Implementation | Screenshot |
|------------|----------------|----------------|------------|
| As a user, I want to create an account easily so that I can access the website's features. | Signup form | Users can create an account through a sign-up form. Once submitted and validated, the user is logged in and can view and add smoothie recipes. | ![Signup Screenshot](docs/Screenshots/SignupSS.jpg) |
| As a user, I want to add my smoothie recipes so I can share them with other users. | Smoothie creation form | Users can add smoothie recipes via a form to input the title, description, and ingredients. | ![Creation Form](docs/Screenshots/CreationFormSS.jpg)|
| As a user, I want to edit my smoothie recipes. | Edit functionality | Users can edit only the smoothie recipes they created. | ![Edit Form](docs/Screenshots/EditSS.jpg) |
| As a user, I want to delete my smoothie recipes. | Delete functionality | Users can delete only the recipes they created. | ![Delete Form](docs/Screenshots/DeleteSS.jpg) |

## Features

## Future Features

## Design

### Colour scheme

### Typography

### Wireframe

## Technologies used

## Tools used

## Deployment

**Deployment steps:**

**Forking the Repository:**

**Cloning the Github Respository:**

## Testing

# Lighthouse reports:

# W3C Markup Validation

# W3C CSS Validator 

**Manual testing:**

**Features:**

**When logged in users can:**

## Bugs and Fixes

**Bug:** *The smoothie app had no signup view.*

**Cause:** *The signup view was referenced in smoothies/urls.py, but did not exist in smoothies/views.py. Django could not find the function, so the app failed to load.*

**Solution:** *Add signup view to smoothies/views.py using Django's built in UserCreationForm.*

**Result:** *The signup page and form are now visible (yet to be functional.)*

---

**Bug:** *Page not found (404) after login.*

**Cause:** *No redirect URL was specified.*

**Solution:** *Added (*LOGIN_REDIRECT_URL = '/'* and *LOGOUT_REDIRECT_URL = '/'*) to settings.py.*

**Result:** *Users are now redirected to the mainpage of the app after login/logout.*

---

**Bug:** *Footer was showing in the middle of the page.*

**Cause:** *Page layout did not push the footer to the bottom of the page.*

**Solution:** *Added full-height layout to style.css.*

**Result:** *Footer now appears at the bottom of the page, with social media icons.*

---
**Bug:** *Heroku deployment issues.*

**Cause:** *Used the wrong app name and database.*

**Solution:** *Used the correct app name and set up PostgreSQL.*

**Result:** *App deployed successfully.*

---

## Credits

