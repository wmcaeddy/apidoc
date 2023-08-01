API Call: Generate Secret Code

    Method: GET
    Endpoint: /getcode
    Response Body: JSON object

    json

    {
      "code": 1234567890123456
    }

API Call: Melchior

    Method: POST
    Endpoint: /melchior
    Request Body: JSON object

    json

{
  "secretcode": 1234567890123456,
  "question": "What is the answer?"
}

Response Body: JSON object (Example)

json

    {
      "secretCode": 1234567890123456,
      "answertype": 1,
      "shortanswer": "true",
      "longanswer": "I'm singing in the rain",
      "question": "What is the answer?"
    }

API Call: Balthasa

    Method: POST
    Endpoint: /balthasa
    Request Body: JSON object

    json

{
  "secretcode": 1234567890123456,
  "question": "What is the answer?"
}

Response Body: JSON object (Example)

json

    {
      "secretCode": 1234567890123456,
      "answertype": 1,
      "shortanswer": "true",
      "longanswer": "I'm singing in the rain",
      "question": "What is the answer?"
    }

API Call: Casper

    Method: POST
    Endpoint: /casper
    Request Body: JSON object

    json

{
  "secretcode": 1234567890123456,
  "question": "What is the answer?"
}

Response Body: JSON object (Example)

json

{
  "secretCode": 1234567890123456,
  "answertype": 1,
  "shortanswer": "true",
  "longanswer": "I'm singing in the rain",
  "question": "What is the answer?"
}
