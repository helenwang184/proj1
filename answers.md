# Q0: Why is this error being thrown?
There is no controller to the pokemon table. 

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
The databases are filled with pokemons when we run rake db:migrate. They are all wild pokemons without trainers.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It is a button that links to the method capture in routes.

# Question 3: What would you name your own Pokemon?
Nihaoma

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
@trainer_path() with the argument of current_trainer

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
flash[:error] shows the error message on the simple form since we just did render :new to remake the page

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
