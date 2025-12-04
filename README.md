# Smoothie_Share_Recipes
Smoothie recipe sharing app

## Description

## Project requirments

## User stories

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


## Credits

