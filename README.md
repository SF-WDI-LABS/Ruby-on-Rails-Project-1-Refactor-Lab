<img src="https://user-images.githubusercontent.com/4304660/33075409-3386be38-ce7e-11e7-8461-3d25496ec02f.png" height="100px">   

## Ruby on Rails Project 1 Refactor

![](https://media.giphy.com/media/l0HlGmv4WqldO9c5y/giphy.gif)

*In this lab you will be using your skills and tools learned in Ruby on Rails to refactor your Project 1 javascript application*

## Expectations

This weekend lab is not intended to be a complete reproduction of your Project 1 codebase in Ruby.  We would like you to translate your database, model, controller, and views to the best of your ability.  You may focus on an inside-out or outside-in approach to achieving MVP - it is your choice.


### Views
Create clean, efficient, DRY views using Ruby on Rails' `erb` files.  Store your imags locally in the `assets/images` folder whenever possible.  Integrate your current front end experience to the best of your ability with the Ruby on Rails convention of separated views for each action. If you are feeling adventurous, delve into introducing `Javascript`, `JQuery`, and any other technology covered into your front-end.  

### Controller
Create a straightforward, minimalist controller.  Utilize a private method to sanitize parameters when possible.  Also consider adding a `before_action:` to find a user or other model for `update`, `show`, and `destroy`. Create clean code that is easy to read and takes advantage of Ruby's vast expanse of methods.

### Models
Create **validations** of your data in the model folders before database accepts the user input.  If you are implementing **auth**, strong validations for username/email and password are required.

Try writing methods within your model files that help you format your data easier when it comes to rendering in the view.  

### Database
Implement your Project 1 associations in Ruby on Rails with **Postgres**.  Given your experience working with **Mongoose**, is there a better alternative structure in **Postgres**?  Feel free to give it a try.  Try to seed better data with **FFaker**.

## Coding approach
You may work with your previous partner, form a new team to tackle a previous project, or work individually.  Notice and recognize the challenges that come with all three decisions.  

Create a list of your priorities as far as functionality and stick to that list!  You may add flair and pizazz if you feel, but know that MVP is still the main goal.



## Deliverables

This lab will be due @ 9:15, Monday, November 27th.  Create a repository with the name of your poject 1 application with `-ROR-Refactor` as a suffix as the name.  This will be an evaluated assignment.

We expect to see a strong resemblance of your previous work in Project 1 within this refactor.  

If you decide create to approach this weekend lab with a inside-out approach, we expect to see proper utilization of `partials`, `forms`, `asset-pipeline` ordering, and an overall pleasing experience.

If you are working with the inside-out approach, we would like to see a rock-solid database with strong relationship structures, useful model validations, and a functioning controller.  

We recognize that you may not have enough time to reach full MVP with the same level of quality you achieved with Project 1. You will have less time and experience with Ruby on Rails than you did with Javascript and Node/Express/Mongoose.  This last lab will challenge you to approach and tackle what you feel is necessary to hae a working **PROTOTYPE** on a platform made for fast and straightforward application development.  

## Challenges
1. Host your Ruby on Rails refactor on [Heroku](https://devcenter.heroku.com/articles/getting-started-with-rails5), [AWS](https://github.com/SF-WDI-LABS/how-to/blob/master/hosting-ror-on-aws.md) or another free hosting site.

2. Integrate image hosting, mailers, or action-cable dispatching to make your site more dynamic in the ways it interacts with its users.
3. Finish All of your User Stories Sprints from your Project 1 documentation within this project.
4. Visit family and friends and catch up while working on this lab.
