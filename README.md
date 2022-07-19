# WeatherAPI---CSharpProject Primary Codebase 
Example to use in-built Web-API based on weather by Dotnet using weather API. Following are the steps to create project.  
## Get Started 
1. Create a repository on GitHub and clone it into your local system. 
2. Move inside the directory. 
3. Execute the following list of commands
     
    ``` bash
    dotnet --version 
    ```

    Check the version of dotnet, update if required
    
    ``` bash 
    dotnet new 
    ``` 

    Create new dotnet project 
    
    ``` bash 
    dotnet new webapi -n <app_name>
    ```
    Create webapi based project 
4. Move inside the app, open Startup.cs and remove <app.UseHttpsRedirection();>
5. Open terminal and run command 

    ``` bash 
    dotnet run 
    ``` 

    Run the dotnet project 
6. Open web browser and search - http://localhost:5000/weatherforecast 
