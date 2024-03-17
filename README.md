# Actix Web Application
#### *By: Matthew Holden*


### Summary

This project containerizes a Rust Actix web application using Docker. 

### Cargo Dependencies

The only additional crate required as a dependancy is the `actic-web` crate.

![image](https://github.com/matthold86/actix_app/assets/114833075/5ab8f248-92e8-4017-9c2e-c1da64c9ae94)

### Main.RS

![image](https://github.com/matthold86/actix_app/assets/114833075/64dacb4e-4cc8-457a-bb51-a9bef0b0a8f6)

### Application Deployed Locally

First, deploy the application locally to see if the `#[actix_web::main]` macro is properly executing the async main function. We bound the function to local port 8080 so that is where the app will be deployed.

![image](https://github.com/matthold86/actix_app/assets/114833075/b6ba883e-2612-417c-9d7b-5c2e6aac15a9)


![image](https://github.com/matthold86/actix_app/assets/114833075/22c961ff-e689-4cfb-86e9-e3157a84f3df)

