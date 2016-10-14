## Questions

1. What is the difference between new and create for a model?
create creates an instance of model that is saved to the database, while new
also creates an instance of the model, it is not saved to the database, just the
local environment.

2. What command combined with new will emulate the same behavior as create?
By calling save, the instance of model created in new will be updated to the database
as create would do.

3. What is the default integer column that exists on every table but we did NOT define?
datetime? It appears to be in the schema for all the models I created.

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(name: 'Kira')

5. How did you like this homework in comparison with the previous homeworks?
I honestly feel like I am behind in the class because I don't understand how to
put MVC syntax together. I should come to OH. This homework would have been more
fun if I could finish it in a reasonable amount of time.
