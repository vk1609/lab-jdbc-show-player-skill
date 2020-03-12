![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | ProGrad Premier League


## Progression 1:

1. **Create a class called as `Main` with main method inside the controller package.**
2. **Create a class called as `Skill.java` inside the model package with below attributes,**
	- Long skilld 
	- String skillName  
3. **Include getter and setter method for all the attributes Include constructor with below arguments public Skill(skilld, skillName)**


## Progression 2:

1. **Create a dao-class called as `SkillDAO.java` inside dao package with below methods to handle all database related operations**
	- ***public List< Skill > listAll Skills ()***
	- The above method used to fetch all the skills from skill table and returns the list of skills.
	- Display the skills in ascending order based on name. 

## Points to remember:
_DAO Layer - Data access layer provides the gateway to create, reterive, update or delete any data in the database. All database related operations will be performed in this layer._



![1 2](https://user-images.githubusercontent.com/61002120/76416050-5807d380-63c0-11ea-8d52-9e8750e800f9.png)


### Note:

Use the below code to retreive the connection details from jdbc.properties to establish connection
```
public static Properties loadPropertiesFile() throws Exception {
	Properties prop = new Properties();	
	InputStream in = ConnectionManager.class.getClassLoader().getResourceAsStream("jdbc.properties");
	prop.load(in);
	in.close(); 
	return prop;
}
```
Create a file called as jdbc.properites. To create a file right click on the application - new - file - name the file as jdbc.properties.
```
jdbc.properties
#JDBC properties entry for MYSQL server
driver = oracle.jdbc.OracleDriver
url=jdbc:oracle:thin:@localhost:1521:xe
username=your_username
password=your_password

```

**Sample Output**

> List of all skills 
> 1) All Rounder 
> 2) Batting 
> 3) Bowling 
> 4) Wicket Keeping Batting 
