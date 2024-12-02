# Learning Laravel Roadmap Week 1-2
- This week we will go on through initial setup and laravel basics
- ## Week 1: Foundation and Setup
	- ### Development Environment Setup
		- #### For both API and Web developers
			- Install Laragon [1] or Laragonzo [2] (preferred)
				- For Laragon
					- Just Install the full edition
				- For Laragonzo (Preferred and Updated)
					- Enable php, apache, mysql, heidisql, git portable, nodejs
			- Then add the laragon to the path (This will add all the binaries to be used from the terminal)
				- Just click Menu > Tools > Path > Add Laragon to Path.
		- #### For API developers
			- install Postman [3] or ApiDog [4] or Bruno [5]
    - ### Links:
        - [1] Laragon : [https://laragon.org/download/index.html](https://laragon.org/download/index.html)
        - [1] Laragon Docs : [https://laragon.org/docs/](https://laragon.org/docs/)
        - [2] Laragonzo : [https://github.com/husnilkhatimi/laragonzo](https://github.com/husnilkhatimi/laragonzo)
        - [3] Postman : [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
        - [4] ApiDog : [https://apidog.com](https://apidog.com)
        - [5] Bruno : [https://www.usebruno.com](https://www.usebruno.com)
	
    <hr>

	- ### PHP and Laravel Fundamentals
		- #### Master PHP basics (if not already known) [1]
			- Just look into it lightly related to OOP and how php works
		- #### Try out creating and running a blank laravel project [2]
			- Create a laravel project using laragon/ laragonzo
			- Create a laravel project using command line (preferably use the built in terminal of the laragon else use cmd or powershell or windows terminal)
			- View the output in the browser
				- Find out the way to view the output in the browser
		- #### Learn how the env files work
			- .env file is present on the root directory of the laravel project
			- You just need to look into it, or ask chat gpt to explain the content of your .env file (if the .env file is not present use .env.example file)
		- #### Understand Laravel project structure [3]
			- Briefly look into the structure of the laravel project, where things go and what is included in the basic laravel project
		- #### Learn about Composer and package management [4]
			- Learn the basic composer commands
			- Try out installing basic composer packages as Laravel debugbar
		- #### Study how to create the laravel controller
			- Write the controller to
				- show the view of the todo app
				- create the controller for create, edit and soft delete as well as restore
		- #### Study Laravel's routing system [5]
			- View how routing works in laravel
			- Create a routes for todo application
				- View (index)
				- Create
				- Edit
				- Delete (Softdelete)
				- Recover deleted entry
		- #### Explore Laravel views [6]
			- Learn how to create views
			- Create the view for todo app, single paged which has list of todos, create function, edit function and soft delete function with strikethrough ~~Example~~ and undo delete button
			  id:: 674d6903-e4c3-4a0b-adc8-8cae0311dfa1
		- #### Explore Blade templating engine [7]
			- Learn about creating component views
			- Learn about blade template components
			- Update the view with the templating engine
				- For button different view
					- Create atleast one dynamic template blade which accepts variable and uses it
				- For nav bar a different view (if any)
		- #### Explore how the models work [8]
			- Learn how to work with eloquent ORM
			- Create relative models for your todo projects
		- #### Explore how the migration and seeders work [9]
			- Explore how to create migrations
				- Create the database structure using the migration
			- Explore how to create seeders
				- Create seeders for the model thats related to above migration
		- #### Practice creating basic routes and controllers [10]
			- Learn the interlink the routes to the controllers
				- There should be atleast 4 routes but must be more than 4 in all cases
				- The controller logic should be well coded and with proper comments before the code
	- ### Links:
		- [1] Learn PHP from : [https://www.w3schools.com/php/](https://www.w3schools.com/php/)
		- [2] Installing laravel project using laragon/laragonzo  : [https://www.wikihow.com/Install-Laravel-Using-Laragon](https://www.wikihow.com/Install-Laravel-Using-Laragon)
		- [2] Installing laravel through command line : [https://laravel.com/docs/10.x](https://laravel.com/docs/10.x)
		- [3] Read the docs about Laravel project structure : [https://laravel.com/docs/10.x/structure](https://laravel.com/docs/10.x/structure)
		- [4] Read about basic composer commands and how to install packages in laravel : [https://medium.com/hello-laravel/the-most-useful-php-composer-commands-f6554c157447](https://medium.com/hello-laravel/the-most-useful-php-composer-commands-f6554c157447)
		- [4] Laravel debugbar : [https://github.com/barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar)
		- [5] Routing in laravel : [https://laravel.com/docs/10.x/routing](https://laravel.com/docs/10.x/routing)
		- [6] Learn about laravel view: [https://laravel.com/docs/10.x/views](https://laravel.com/docs/10.x/views)
		- [7] Learn blade templates here: [https://laravel.com/docs/10.x/blade](https://laravel.com/docs/10.x/blade)
		- [8] Learn how the model and view work together : [https://www.cloudways.com/blog/models-views-laravel/](https://www.cloudways.com/blog/models-views-laravel/)
		- [8] Learn the eloquent : [https://laravel.com/docs/10.x/eloquent](https://laravel.com/docs/10.x/eloquent)
		- [9] Learn the migration and seeders : [https://laravel.com/docs/10.x/migrations](https://laravel.com/docs/10.x/migrations)
		- [9] Impressive blog about laravel migration and seeders: [https://medium.com/grevo-techblog/lavarel-migration-seeding-b093a68990cd](https://medium.com/grevo-techblog/lavarel-migration-seeding-b093a68990cd)
		- [10] Learn about the overall integration: [https://www.cloudways.com/blog/laravel-crud/](https://www.cloudways.com/blog/laravel-crud/)
	
    <hr>

	- Requirements
		- Each team member are expected to create a repository of their own name appended with TODO
			- i.e. the name of the repository will be "ChandanShakya-TODO"
		- The commits message should be descriptive
	
	- Create a repository under the NCCSSoftware organization, under the Team InternWeb
		- Link : [https://github.com/orgs/NCCSSoftware/teams/internweb](https://github.com/orgs/NCCSSoftware/teams/internweb)
	<hr>
	
	- Deadline: December 15, 2024, 00:00 (i.e. before Sunday 13th, Nepal Time +5:45)
	
	- Take your time
		- Ask for help on discord
		- Ask mentors on Mentor visits
