# project-pallet
This application allows a user to post a project he/she has created and get it reviewed by other people. It is built using Django Python framework.

## Live Link
[View Site](https://project-pallet.herokuapp.com/)

## Screenshot

Home:
<img src="https://github.com/TechVictorKE/project-pallet/blob/master/projectpallet/static/img/pallet-home1.png">

Home:
<img src="https://github.com/TechVictorKE/project-pallet/blob/master/projectpallet/static/img/pallet-home2.png">

Profile:
<img src="https://github.com/TechVictorKE/project-pallet/blob/master/projectpallet/static/img/sample-profile.png">

Single post:
<img src="https://github.com/TechVictorKE/project-pallet/blob/master/projectpallet/static/img/singleproject-post.png">


## User Stories

* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* Search for projects 
* View projects overall score
* View my profile page

## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load website | **Website url** | Sign up/Log in|
| Show posts | **Click on post** | See the post close up|
| Search project | **Project name** | Project with username that leads to user's profile|



### Prerequisites

* Python 3.8

## Running the Application
* To run the application, in your terminal:

        $ python3 manage.py runserver
      
        
## Testing the Application
* To run the tests for the class file and check if it functions well:

        $ python3 manage.py test projectpallet
        


## Built With

* [Python](https://www.python.org/) for backend
* [HTML](https://html.com/) for web app structure
* [Bootstrap](https://getbootstrap.com/) and [Javascript](https://www.javascript.com/) for styling
* [Heroku](https://heroku.com)

## Authors

* **Victor  Kibocha** - *Initial work* - [Github](https://github.com/TechVictorKE/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspired by Moringa School
