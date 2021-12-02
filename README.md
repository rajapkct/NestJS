# NestJS
This Repository contains the features of nestJS


Nest CLI : 
  This is the Tool to generate and runnibg our Nest projects.
  
Main Dependancies : 
  1. @nestjs/common  : contains classes, functions etc that we need from Nest.
  2. @nestjs/platform-express : Lets Nest use Express JS for handling http requests.
  3. @reflect-metadata : Helps to make decorator works
  4. typescript : We write Nest app with typescripts.

Nest doesnot have the feature to handle http requext/response directly. It uses either Express or Fastfy to achieve httpe requst/response.

![image](https://user-images.githubusercontent.com/30463735/144346396-bd958fc2-5cec-44cd-b24c-3328c31b82bd.png)

Parts of Nest: 
  1. Controller : Handles the request, process and send the response.
  2. Services   : Handles data access and business logic
  3. Modules : Groups the together code
  4. Pipes : Validates the incming data
  5. Filters : Handles errors that occurs during request handling
  6. Gaurds : Handles authentication
  7. Interceptor : Adds extra logic t incoming request or outgoing response 
  8. Repository : Handles data stored in a DB

