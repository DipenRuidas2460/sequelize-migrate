# sequelize-migrate

check status:- npx sequelize-cli db:migrate:status

down/delete :- npx sequelize-cli db:migrate:undo --name 20230927094652-create-user.js

create seeder for all :- npx sequelize-cli db:seed:all

particular data add seeder:- npx sequelize-cli db:seed --seed 20230927101630-add-employee.js


delete seeder data particular file :- npx sequelize-cli db:seed:undo --seed 20230927101630-add-employee.js