# 15-TRAIN-ME-app


## Table of Contents 
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [question](#questions)


### Inspiration:

Projects play a key role in your journey to becoming a full-stack web developer. As you enter the last phase of the boot camp, you’ll begin to apply for development jobs. If you want to land interviews, your portfolio must feature high-quality deployed examples of your work—-and you can use your finished projects for that very purpose.

As your first opportunity to show employers your collaborative skills and coding abilities, this particular project will be a focal point of your portfolio. Employers want to see what you can do, but they also want to see how you work with other developers. The more examples of deployed collaborative work you have in your portfolio, the more likely you are to get an interview and a job.

[Heroku Deployment](https://trainme2getfitapp.herokuapp.com/login)

![trainme2getfit herokuapp com_](https://user-images.githubusercontent.com/85536828/136316758-90a6cf3a-fcc8-4e3f-bc7f-c4b5911af93d.png)

## Installation:

From no clone, build on own. Assumes NodeJS has been installed on machine.

```

npm init

```
Follow prompts.

```
npm install mysql2

npm install express

npm install express-handlebars

npm install express-session

npm install sequelize

npm install connect-session-sequelize

npm install bcrypt

```

For security use dotenv to protect credentials. Seeds for clone and generic data.

```

npm install dotenv

npm install seeds


```

For setups from clone

```
npm install

cd db/

mysql -u <your_mysql_user_name> -p

source trainme_schema.sql;
source trainme_alter_schema.sql;
exit

npm start

```
## Usage:

A demonstration of MVC architecture using Javascript and SQL languages to promote an app for enterpernuers in the fitness industry that want a simple app to track and communicate with clients.

#### User Story:
```
As a personal trainer I want to be able to create new clients
SO THAT my business can grow.
As a personal trainer I want to be able to login to see my list of clients
SO THAT I may track their progress
AS a personal trainer I want to be able to update client information
SO THAT progress is marked and support based on data 
As a personal trainer I want to be able to delete clients
SO that do not continue to show up in dashboard
As a personal trainer I want to be able to send clients notes via preferred method of email or SMS
SO that the client is free to use preference outside of APP
As a personal trainer I want to be able to assign workouts to clients for different days of the week
SO that the client is supported in working towards their goals.
As a personal trainer I want to be able to update workouts for clients
SO that they feel engagement and strive to meet their goals
As a personal trainer I want to be able to create a client diet
As a personal trainer I want to be able to login and click on a client profile and see their workout and diet
SO that I may anaylze their progress and help client reach personal goals
As a personal trainer I want to be able to add a additional workout or diet information
SO that I may continue to grow and improve.
```

#### Structure:

Clients :First name, last name, age(birthdate) (auto update by date??), height, initial weight, email, phone number (okay to receive texts??), initial start date saved by automation

Updateable items: email, goal weight, workout, dietary, goals, location, comments

Future feature Set Client as Inactive, "soft delete"
             

## License:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contributors:
 [Adam N](https://github.com/adam-niggebrugge)

 [Erica B](https://github.com/unicorninvirgo)

 [Joseph B](https://github.com/Genius2k21)

 [Skylar H](https://github.com/Skylar-Harwell)

 [Ufuoma E](https://github.com/uekemike)

            

## Questions
If you have any questions about the repo, open an issue or contact us directly at one of the below emails. 

### Email Address:

5. [Email Adam](mailto:adam.niggebrugge@gmail.com)

Copyright 2021 &copy;
