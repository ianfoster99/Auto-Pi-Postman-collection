# Auto Pi Postman collection  
  
Postman collection for [Auto Pi](https://www.autopi.io) based on [Auto Pi API](https://api.autopi.io)  
  
## Importing the collection  
  
* Install [Postman](https://www.postman.com/downloads)  
* File..Import. Select the File tab and drag the AutoPi.io API.postman_collection.json file into the window and then click Import  
  
You will now see a *AutoPi.io API* collection in the left hand pane.  
![Collection](https://user-images.githubusercontent.com/14953385/106211915-6b32b600-61c1-11eb-9208-0f22fa81b1a8.png)

## Get a token      
* Expand the *auth* node and click on *auth login create*   
![UserNode](https://user-images.githubusercontent.com/14953385/106211172-2bb79a00-61c0-11eb-9c40-6c796e29c688.png)      
    
* Enter the username and password you use to login into https://www.autopi.io   
![UserNamePassword](https://user-images.githubusercontent.com/14953385/106211517-dd56cb00-61c0-11eb-84af-542ce170677f.png) 

* Click the blue *Send* button  
* Copy the token from the section below  
![Token](https://user-images.githubusercontent.com/14953385/106211467-c31ced00-61c0-11eb-85a0-7b8b96d7efbe.png)  
    
## Apply token  
 * Right click on the *Auto Pi.io API* collection in the left hand pane and choose edit  
 ![Edit](https://user-images.githubusercontent.com/14953385/106211629-ff504d80-61c0-11eb-8074-c8df4972f5b2.png)
 
 * Click the Authorization tab  
 * Change *Type* to *Bearer Token*  
 * Paste your token in the Token field and click Orange *Update* button  
![Token](https://user-images.githubusercontent.com/14953385/106212124-d1b7d400-61c1-11eb-88af-7d600160595b.png)
  
## Test    
* Expand the auth/user node and choose 'Reads and updates UserModel fieldsAccepts GET, PUT, PATCH methods.' and click the Blue Send button 
  
You should see information from your account  
![AccountDetails](https://user-images.githubusercontent.com/14953385/106212249-16436f80-61c2-11eb-964a-c1c9148afdfc.png)

