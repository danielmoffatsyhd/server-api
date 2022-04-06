# server-api
API for the Contact Management Application 


## 
| API                           | Description                       | Params            | Request body      | Response body                 |
|------------------------------	|-----------------------------------|-------------------|-------------------|-----------------------------	|
| GET /contacts                 | Get all contacts                  |                   | None      	    | Array of contacts             |
| GET /contacts/{id}            | Get contact by ID              	| id                | None   	        | contact details              	|
| POST /contacts                | Add a new contact            	    |                   | body          	| body                         	|
| PUT /contacts/{id}            | Update an existing contact        | id                | body              |                               |
| DELETE /contacts/{id}         | Delete a contact               	| none              | None    	        | None                         	|


# Collection

Find postman collections within the collections dir

## Run
```
npm start
```
