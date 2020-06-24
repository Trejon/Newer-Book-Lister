# Book Lister

A simple single page book application using vanilla javascript to access a Rails API backend. Uses devise for a basic login to store JSON Web Tokens for each users session. Created for users to keep a library of their favorite books, add them to lists and review them.

## Installation

To install Book Lister, fork the repo and cd into the backend and run bundle install. Run 'rails db:migrate' to set up the database. If you choose to use the seed data, run 'rails db:seed'. Finally to get the backend up and running, run 'rails server'. After setting up the backend, in a new terminal window cd into to the project root. Once in the root, cd into the frontend. Once in the frontend folder, open index.html. This will open the application in your browser and it can connect to the backend api.

```bash
cd into the backend folder
bundle install
rails db:migrate
rails db:seed [optional]
rails s
open new terminal
cd into project root
cd into frontend 
open index.html
```

## Usage


If you seeded the database you can look in the seed file for user login information. Otherwise, create a new user and you can start adding to your collection. Create a list and from there you can add multiple books onto it. Once a book is added you can also add reviews for them.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
