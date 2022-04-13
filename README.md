## **POST /notes**
 __Action: create__ <br/>
 **Create a new note** <br/>
 Parameters:
 ```js
 - title: string <br/> 
 - description: string <br/> 
 - reminder: boolean <br/>
 - status: string <br/>
  - category: string
 ```
 Response: success: 200, error: 400



## GET /notes/{id}
### Action: getOne
### Get a single note
### Parameters: id: string
### Response: success: 200, error: 404


## GET /notes
### Action: getAll
### Get all notes
### Parameters: none
### Response: success: 200, error: 404


## PUT /notes/{id}
### Action: update
### Update a note
### Parameters: id: string, title: string, description: string, reminder: boolean, status: string, category: string
### Response: success: 204, error: 400


## DELETE /notes/{id}
### Action: delete
### Delete a note
### Parameters: id: string
### Response: success: 200, error: 400


