![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | ProGrad Premier League




![sql](https://user-images.githubusercontent.com/58466121/76389844-3c85d400-6392-11ea-875f-8cd9676219b2.JPG)


![1 2](https://user-images.githubusercontent.com/61002120/76415418-2d694b00-63bf-11ea-9f97-3c19b5cd1981.png)

The IPL is the most-attended cricket league in the world and ranks sixth among all sports leagues.IPL has players with unique skills. IPL helped players to potray their skills and provided opportunity to play international cricket. Your first module is to display all the skills in the application. Mysql is used as the database and the application uses JDBC API to connect with the database. 
Specification: 
 


## Progression 1:
Create `Main.java` with main method Create Skill.java domain class with below attributes, 
• skilld - Long 
• skillName - String 

## Progression 2:
Include getter and setter method for all the attributes Include constructor with below arguments public Skill(skilld, skillName)

## Progression 3:
Create `SkillDAO.java` with below methods to handle all database related operations
`public List< Skill > listAll Skills ()` - Method used to fetch all the skills from skill table and returns the list of skills. Display the skills in ascending order based on name. 

_DAO Layer - Data access layer provides the gateway to create, reterive, update or delete any data in the database. All database related operations will be performed in this layer._

**Sample Output**
> List of all skills 
>> 1) All Rounder 
>> 2) Batting 
>> 3) Bowling 
>> 4) Wicket Keeping Batting 
