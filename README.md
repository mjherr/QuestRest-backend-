# QuestRest-backend-

building the backend using Express

first I built the server.js file, installed express and sequelize

next, using sequelize i generated the models needed for the db, thusfar making task.js and user.js

then created seeders to create data in the db for testing/troubleshooting


idea/change log
9/25/2022-
    each created task should have the user id as a foriegn key
    might need to change how we id the tasks, might run into issues with having a unique primary key if more than one person has the same task



if you need the tables/data added to your local db:

add the tables to your database-

sequelize db:migrate

populate db with test data-

sequelize db:seed:all

