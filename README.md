# recipes-website

**To run the code** 
* Download and extract the zip file
* Put the folder inside xampp folder in a folder named htdocs
* Run XAMPP through XAMPP control panel ( start Apache and MySQL )
* Open phpmyadmin on your localhost and import the attached sql file "log_test.sql" which is our database that contains all tables
* Open the folder with VS code
* Open config folder --> conn_database.php and make sure of the name of the database "log_test" 
* Include the path of conn_database.php. ex: 'C:\xampp\htdocs\folder_name\config\conn_database.php'
* Now you can type localhost followed by the folder name that you have put in htdocs in your url. ex: localhost:8080/folder_name

**To use our website** 
1) first of all if you are chef or admin you can simply write the username and password no need to signup

   username :admin password:admin     
   username:chef password: chef 
   
   but if you are a user you need to signup then go to sign in page and put the username and password to enter our homepage
   you can just login with username:user password:user or username :m password:m, they are accounts that we aleady created if you don't want to signup 

2) in our home page you can see at the top of it the nav bar which can direct you to many pages to allchefs, all recipes, contact us which will talk about each of them and also you can see the logout button to redirect you to the sign in page

3) in our home page also you can see the cateogries of recipes (Breakfast-Lunch-Beverages-Desserts-Snacks-Salads) when you press on any of them you redirect to the all recipes page containing the recipes according to the cateogry you pressed on it

4) in all recipes you can also filter by the most popular or most viewd according what stored in the database and sort from A-Z or Z-A or the default recipes and finally you can search on any text and it will find from all the recipes where this text you are searching for and only display the recipes that contain this text

5) if you press on the button view recipe  it will redirect you to the page of recipe details according what recipe you pressed the button of it

6) if you press on all chefs from the nav bar it will direct you to page containg all the chefs and if you want to know more details about any chef you can press on details that exist in any chef card that direct you to the page containing more details about the chef you pressed on it 

7) if you press on contact us it will direct you to page containing a card that you fill it with the username and email and the comments you want to write and if you clicked the submit button the details you filled will send to the admin page

8) in the admin page you can either click on show comments button that will show a table contain all the comments any user added with the details of that user and you can also add a new chef by filling all his details in the add new chef card and after you press the button of add chef , a new chef will be added automatically the all chef page and if you pressed on details you can also see the details of this chef as the normal scenario

9) in the chef page (that i mentioned before that you can enter it by username and password of chef chef) you can add a new recipe by filling all the details of the recipe and after you click on add recipe button it will automatically add a new recipe to the all recipes page and you can also press view recipe to see the details of the recipe as the normal scenario 

**Note:** you can logout from any page in our website by the logout button that in the top right of any page and the nav bar included in all the page except the admin and chef page but you can logout from them


