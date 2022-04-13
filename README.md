# create
## POST /notes
### Create a new note
### Parameters: title: string, description: string, reminder: boolean, status: string, category: string
### Response: success: 200, error: 400


# getOne
## GET /notes/{id}
### Get a single note
### Parameters: id: string
### Response: success: 200, error: 404


# getAll
## GET /notes
### Get all notes
### Parameters: none
### Response: success: 200, error: 404


# update
## PUT /notes/{id}
### Update a note
### Parameters: title: string, description: string, reminder: boolean, status: string, category: string
### Response: success: 204, error: 400


# delete
## DELETE /notes/{id}
### Delete a note
### Parameters: id: string
### Response: success: 200, error: 400


