<div align="center">

  <img src="https://github.com/ogiogiovictor/hello_rails/blob/master/murple_logo.png" alt="logo" width="140"  height="auto" />
  <br/>

  <h3><b>Recipe-APP-Rails</b></h3>
</div>
# Budget App - Ruby on Rails

Budget App is a mobile web application where you can manage your budget: you have a list of transactions associated with a category, so that you can see how much money you spent and on what.

## :hammer: Preview

- Under construction

## :hammer: Built With

- Ruby on Rails
- TailwindCSS

To get a local copy up and running follow these simple steps:

**First Steps**

1. Clone it using git command:
```ruby
git clone https://github.com/rebel216/budget-app.git
```

**Run in development (locally)**

1. Install gem files and dependencies:
```ruby
bundle install
```
```ruby
npm install or yarn install
```
2. Setup you database.yml with your own postgres's password or create a PASS_POSTGRES environment variable 
```ruby
  password: <%= ENV["PASS_POSTGRESQL"] %>
```
4. Setup db and seed file
```ruby
rails db:setup
```
```ruby
rails db:seed
```
5. Run server
```ruby
rails assets:precompile
```
```ruby
rails server
```


**Run tests**

1. To run all tests in the project
```ruby
rspec
``` 
If you wanna run a certain test file
```ruby
rspec spec/test_file_path
```

## :blue_book: Learning Objectives

- Use ruby gems as software packages system.
- Install Ruby on Rails framework.
- Understand Rails RESTful design and router.
- Use controllers to handle requests and render empty views.
- Use params from browser request in a safe way.
- Use preprocessed html file with embedded Ruby code.
- Use layouts and templates for shared content.
- Use database migration files to maintain database schema.
- Use validations for models.
- Secure app from n+1 problems.
- Understand what ORM is.
- Write SQL queries with ActiveRecord.
- Set up associations between models.
- Build a webapp that requires the user to log in.
- Use devise gem for authentication.
- Limit access to webapp resources based on authorization rules.
- Analyze in writing why you have made a coding choice using one structure over another.

## Authors

👤 **NeerajBhardwa**

- GitHub: [@NeerajBhardwaj](https://github.com/rebel216)
- Twitter: [@NeerajBhardwaj](https://twitter.com/rebel216)
- LinkedIn: [NeerajBhardwaj](https://www.linkedin.com/in/neerajbhardwaj216/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/rebel216/budget-app/issues).

## :grey_exclamation: Acknowledgments

- [Microverse](https://www.microverse.org/)
- [SnapScan Design Guideline](https://www.behance.net/gallery/19759151/Snapscan-iOs-design-and-branding?tracking_source=)

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](LICENSE) licensed.

