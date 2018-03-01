# REST API
How to create REST API

## Basic flags
```json
{
    "status": true,
    "message": "string",
    "data": []
}
```
+ status: boolean, Specifies the state to return the data
+ message: string, Message to the user
+ data: array, Return the data if any

## key format
```json
{
    "status": true,
    "message": "string",
    "data": [
    	{
            "userId" : 111,
            "fullName" : "Adam",
            "age" : 5
        }
    ]
}
```
The first letter of the second word must be large .. Do not use _ to connect words

Correct label | Wrong label
---|---
userId | user_id
fullName | full_name