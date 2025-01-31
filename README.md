.<a name="readme-top"></a>
 <div align="center"><a href="https://github.com/Benawi"><img src="https://github.com/Benawi/Benawi/assets/21217148/de823737-5f7f-4de8-b62e-3fe88c238eab"/></a>

 </div> <div align="center">🛰Blog App  🚀</div>

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [📖 Blog App ](#-ruby-group-capstone---catalog-of-my-things-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Run localy](#run-localy)
    - [Run Tests ](#run-tests-)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

# 📖 Blog App <a name="about-project"></a>
A Blog app is similar to a classic blog website. With a fully functional website that shows the list of posts and empowers readers to interact with them by adding comments and liking post
The project is a repository consisting of the following files:

- Ruby files
- Rails files
- Ruby linters file

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>
  <ul>
     <li>
      <a href="https://www.ruby-lang.org/en/">
      <img align="center" width="19" height="auto" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Ruby_logo.svg/198px-Ruby_logo.svg.png?20101129171534" alt="rubylogo" />
      Ruby
      </a>
    </li>
    <li>
      <a href="https://rubyonrails.org/">
      <img align="center" width="19" height="auto" src="./rails-red-logo.svg" alt="ruby logo" />
      Rails
      </a>
    </li>
    <li>
      <a href="https://www.postgresql.org/">
      <img align="center" width="19" height="auto" src="https://wiki.postgresql.org/images/3/30/PostgreSQL_logo.3colors.120x120.png" alt="postgreSQL logo" />
      PostgreSQL
      </a>
    </li>
  </ul>
  
</ul>

###  Key Features <a name="key-features"></a>

- [x] Display Users, posts, comments on posts, likes on posts
- [x] Create a new app
- [x] Processing data in model
- [x] Validations and Model spec.
- [x] Setup and controllers.
- [x] The project has a Postgres database set up
- [x] Create and run the necessary migration files.
- [x] Table and column names match the [ERD](https://github.com/microverseinc/curriculum-rails/blob/main/blog-app/images/blog_app_erd.png) diagram with [developed](https://github.com/Benawi/Blog-App/assets/21217148/5b403dca-d56b-4a66-bc96-58efbf0d7eae)
        

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

### Prerequisites

In order to run this project you need:

- [Ruby](https://www.ruby-lang.org/en/) installed and running. To get more information, read the [installation instructions](https://github.com/microverseinc/curriculum-ruby/blob/main/simple-ruby/articles/ruby_installation_instructions.md).
- You should be able to use [IRB](https://en.wikipedia.org/wiki/Ruby_(programming_language)#Features).
- First of all, make sure you have both `Ruby` & `Rails` installed on your machine
 (else You can install `Rails` just with this simple command  ```gem install rails```)
### Setup

Clone this repository to your desired folder

```
  git clone https://github.com/Benawi/Blog-App.git
  cd Blog-App
```

### Install

Install project dependencies with

```
  bundle install
```
### Run locally
 - Then go to the right folder 
```
$ cd Blog-App
```
```
$ bundle
```
and run to install npm package
```
$ npm install
```

make sure the database is up and running.
```
$ rails db: create
```
When you add a migration file, you can add commands like
```
$ rails db: migrate
```
Run this command line to add some dummy data
```
$ rails db: seed
```

 - Finaly run `rails s` and visit http://localhost:3000/  in your browser!

### Run Tests <a name="run-tests"></a>

Go to your gemfile and add the RSpec gem in the development test group:

 ```
 group : development, test do  
  gem 'rspec-rails'
 end
 ```
Then in your terminal run the command:

 ```
  $ bundle install
 ```
To set up RSpec in your app and create the Spec folder run:

 ```
  $ rails generate rspec: install
 ```
  To run Request specs locally you need just to run the following command in your terminal:
 ```
 $ rspec spec/model/
 $ rspec spec/models/ --format documentation 
 ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>

### 👤 **Habtamu Alemayehu**

- GitHub: [Benawi](https://github.com/Benawi)
- Linkedin: [Habtamu](https://www.linkedin.com/in/habtamualemayehu/)

👤 : **Bwambale**

- GitHub: [@githubhandle](https://github.com/wolterbwambale)
- Twitter: [@twitterhandle](https://twitter.com/BwambaleWolter)
- LinkedIn [LinkedIn](https://www.linkedin.com/in/bwambale-benny-wolter/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>
- [ ]  Integration specs for Views and fixing n+1 problems.
- [ ]  Add Devise.
- [ ]  Add authorization rules.
- [ ]  Add API endpoints.
- [ ]  API documentation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, [issues](https://github.com/Benawi/Blog-App/issues), and feature requests are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give me ⭐️ If you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- I wanted to take a moment to express my sincere gratitude for the opportunity to work with you all on this project.
- Microverse, thank you for providing the structure, guidance and community to help me level up my skills as a developer. The experiential learning model has been invaluable in improving my coding abilities and collaboration skills. I appreciate the code reviews and feedback to help me write cleaner, more professional code..

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
