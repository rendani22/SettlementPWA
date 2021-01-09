# SettlementPWA
Progressive web app for the Settlement application

Project structure: 

wwwroot: 

css : You will find the app.css file. This is where all the css for the application is. It would be best if we can keep all css code in the css folder. 

root:  

favicon for web, icon on browser tab  

Icon-512 for when the app is downloaded on a mobile device 

Index is the main file, if you want to link any css or js file to the project, this Is the page for it.  

Pages: 

Forms: Index.razor HTML code for the form that will be used by the data captures. When designing use the sample questions they gave you, I’ll later on add the code to make it dynamic. Please make sure that all different types of questions are designed. (User classes). 

Login: Login.razor code for the login page, css for this is currently on app.css. 

Shared: 

LoginLayout.razor: Layout that’s used for the login page 

MainLayout.razor: Layout that’s used for the rest of the application with NavMenu.razor 

NavMenu.razor: HTML code for the sidebar. 
