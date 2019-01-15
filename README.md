# MARVEL CINEMATIC UNIVERSE
## CONSOLE APP
 
### PROJECT INFORMATION:
Console application with information (database) about Marvel Universe movies.
Application can be accessed by users with three levels of authorization.
As database it uses txt.
 
### USED TECHNOLOGY
            	- Programming language: Java 8
            	- IDE: JetBrains IntelliJ 2018.3 X64

### SETUP	
Not special setup needed, just run program from IDE.
 
### ENTITIES:
1. USERS  
2. MOVIES
3. DIRECTORS
4. ACTORS
5. CHARACTERS
 
### ROLES:
There will be three levels of authorization: Administrator, Moderator and User.

	All Users (administrator, moderators and users) can:
* Can read movie information
* Can set rating 0-10
* Can add to favorite list
* Can get movie list sorted by date of release
* Can get movie list sorted by rating
* Can get all movie list of one director
* Can get all movies of one actor
* Can get all movies where character shows up

Additionally:

1. Administrator
	* Can create, read, update and delete user information and delegate roles
	* Can create, read, update and delete movies
	* Can create, read, update and delete directors
	* Can create, read, update and delete actors
	* Can create, read, update and delete characters    
2. Moderator
	* Can create, read, update and delete movies
	* Can create, read, update and delete directors
	* Can create, read, update and delete actors
	* Can create, read, update and delete characters

## Authors

* **Dragan Kocić** - *Initial work* - [gagister](https://github.com/gagister)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
