## POST /notes
Action: create<br />Create a new note<br />Parameters:
```
  title: string
  description: string
  reminder: boolean
  status: string
  category: string
```
Response:
```
  success: 200
  error: 400
```


## GET /notes/{id}
Action: getOne<br />Get a single note<br />Parameters:
```
  id: string
```
Response:
```
  success: 200
  error: 404
```


## GET /notes
Action: getAll<br />Get all notes<br />Parameters:
```
  none
```
Response:
```
  success: 200
  error: 404
```


## PUT /notes/{id}
Action: update<br />Update a note<br />Parameters:
```
  id: string
  title: string
  description: string
  reminder: boolean
  status: string
  category: string
```
Response:
```
  success: 204
  error: 400
```


## DELETE /notes/{id}
Action: delete<br />Delete a note<br />Parameters:
```
  id: string
```
Response:
```
  success: 200
  error: 400
```


