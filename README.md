![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | ProGrad Premier League




![sql](https://user-images.githubusercontent.com/58466121/76389844-3c85d400-6392-11ea-875f-8cd9676219b2.JPG)


![1 2](https://user-images.githubusercontent.com/61002120/76416050-5807d380-63c0-11ea-8d52-9e8750e800f9.png)

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


### Note:

Use the below code to retreive the connection details from mysql.properties to establish connection
```
public static Properties loadPropertiesFile() throws Exception {
	Properties prop = new Properties();	
	InputStream in = ConnectionManager.class.getClassLoader().getResourceAsStream("jdbc.properties");
	prop.load(in);
	in.close(); 
	return prop;
}
```    

**Sample Output**

> List of all skills 
> 1) All Rounder 
> 2) Batting 
> 3) Bowling 
> 4) Wicket Keeping Batting 
