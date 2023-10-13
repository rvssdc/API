# JSON API  


API endpoint that will insert and extract data in the database


## API
Endpoints


Describe the
available endpoints, their functions, and the required parameters.


 


## Request
JSON Payload postName
{
  "lname":"hortizuela",
   "fname":"manny"
}
JSON Payload printName
It does not require a request

JSON Payload updateName:
Request payload:
{
  "id":1,
  "lname":"wick",
   "fname":"john"
}

JSON Payload deleteName:
Request payload:
{
  "id":1
}

## Response
JSON Payload postName
Response payload:
{
         "status":"success","data":null
}

JSON Payload printName
Response payload:
{
         "status":"success","data":["lname":"hortizuela","fname":"manny","lname":"licayan","fname":"arnold"]
}

JSON Payload updateName:
Response payload:
{
         "status":"success","data":null
}

JSON Payload deleteName:
Response payload:
{
         "status":"success","data":null
}
 


## Usage


{
  "postNameRequest": {
    "url": "https://your-api-url.com/postName",
    "method": "POST",
    "payload": {
      "lname": "hortizuela",
      "fname": "manny"
    }
  },
  "printNameRequest": {
    "url": "https://your-api-url.com/printName",
    "method": "GET"
  },
  "updateNameRequest": {
    "url": "https://your-api-url.com/updateName",
    "method": "PUT",
    "payload": {
      "id": 1,
      "lname": "wick",
      "fname": "john"
    }
  },
  "deleteNameRequest": {
   



## License
NO LICENSE

## Contributors
MR. MANNY HORTIZUELA


## Contact
09667446469
kymrussel.delacruz@student.dmmmsu.edu.ph
