![](https://img.shields.io/badge/Microverse-blueviolet)


# hello-rails-front-end
A simple react greeting application that consumes rails api. you can find the back-end application [here](https://github.com/Behnam1369/hello-rails-back-end). 


# Requirements for this project
You can find requirements for this project [here](https://github.com/microverseinc/curriculum-rails/blob/main/connect-frontend-frameworks/hello_world_two_apps.md).

## Installation & Usage

To setup the backend local server: 
- Make sure you have `Postgres` and `Ruby` installed. 
- Open the terminal window and clone the repository using this command: `git@github.com:Behnam1369/hello-rails-back-end.git` 
- Open the repo by typing : `cd hello-rails-back-end`
- Install the project's dependencies by running `bundle install` 
- Make sure you have database user called `postgres`.
- Make sure you have a `db.rb` file under the `config` folder and it should be containing `ENV['DATABASE_PASSWORD'] = 'your_password'`.
- run `rails db:create` to create the database.
- run `rails db:migrate` to create the the dchema. 
- run `rails db:seed` to insert greeting records. 
- run `rails s` to start the api endpoint on local server. 


To setup the front-end local server: 
- Make sure you have `node.js` installed. 
- Open the terminal window and clone the repository using this command: `git@github.com:Behnam1369/hello-react-front-end.git` 
- Open the repo by typing : `cd hello-react-front-end`
- Install the project's dependencies by running `npm install` 
- Make sure you have database user called `postgres`.
- run `npm start` to start the application on local server. 
- note: you need to run the front-end application in a port other than default port, as the default port will be used by the back-end server.

## Technologies

- Ruby
- Rails 
- Postgres 
- javascript
- React 
- Redux


## Author


👤 **Behnam Aghaali**

- GitHub: [https://github.com/Behnam1369](https://github.com/Behnam1369)
- LinkedIn: [https://www.linkedin.com/in/behnam-aghaali](https://www.linkedin.com/in/behnam-aghaali)
- Twitter: [https://twitter.com/behnamagh1369](https://twitter.com/behnamagh1369)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Behnam1369/Catalog_of_my_things/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](./LICENSE) licensed.