#Servicios a crear


users -> posts

- Retrieve all users: 		GET    /users
- Retrieve specific user: 	GET    /users/{id} -> /users/1
- Create a user: 			POST   /users
- Delete a user: 			DELETE /users/{id} - /users/1

- Retrieve all posts for a user:   	GET   /users/{id}/posts
- Create a post for a user:			POST  /users/{id}/posts
- Retrieve details of a post:		GET   /users/{id}/posts/{id}

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>
		
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>