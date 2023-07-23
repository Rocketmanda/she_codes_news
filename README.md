# Amanda Hagaman - She Codes News Project

## About This Project
This Project is a news site with user articles. It focused on Django and also uses HTML, CSS and Python inputs. 

## How To Run This Code
 1. Clone the repo to your local machine - Navigate to the directory of your choice and run the following command: 
   - `git clone https://github.com/Rocketmanda/she_codes_news.git`
  
 2. Set up Virtual Environment:
   - In your terminal, navigate to the folder containing `requirements.txt` file:
     - Mac run the following command: `source venv/bin/activate`
     - Windows run the following command: `venv/Scripts/activate`

 3. Install Django, Migrate, Load Data and Run:
  - `python3 -m pip install -r requirements.txt`
  - `python3 -m pip freeze` to check if install successful
  - `cd she_codes_news` to navigate to where manage.py file is contained
  - `python3 manage.py migrate` to make migrations
  - `python3 manage.py loaddata users` then `python3 manage.py loaddata news` to load the data for the articles
  - `python3 manage.py runserver` to run the server (or jog)

  4. View the She Codes News site: http://localhost:8000/news


## Project Features
  - [X] Order stories by date
  - ![ Screenshot of news articles in published date order ]( )

  - [X] Log-in/log-out: Is no longer accepting my initial user passwords
  - ![ Screenshot of login option ] ( {{ ./relative_path_to_image_file }} )
    
   - [X] "Log-in" button only visible when no user is logged in/"Log-out" buttononly visible when a user *is* logged in: Per above comments, original passwords no longer working. Somewhere along the way this stopped working but I did have it at one stage!
- ![ Screenshot of login] ( {{ ./relative_path_to_image_file }} )

- [X] "Create Story" functionality only available when user is logged in: Tweaked code and now it shows for all users (whether logged in or not)
- ![ Screenshot of 'write new story' form ]( {{ ./relative_path_to_image_file }} )
  
- [ ] Styled "new story" form
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

- [ ] Story images: Almost got there, would love to resolve
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )
  
- [ ] "Account view" page
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )
  
- [ ] "Create Account" page
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

- [ ] View stories by author
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

  

## Additional Features:

- [ ] Add categories to the stories and allow the user to search for stories bycategory.
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

- [ ] Add the ability to update and delete stories (consider permissions - who should be allowed to update or and/or delete stories).
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

- [ ] Add the ability to “favourite” stories and see a page with your favouritestories.
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

- [ ] Our form for creating stories requires you to add the publication date,update this to automatically save the publication date as the day the story was first published (maybe you could then add a field to show when the story was updated).
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )

- [ ] Gracefully handle the error where someone tries to create a new story whenthey are not logged in.
- ![ {{ Description of image }} ]( {{ ./relative_path_to_image_file }} )