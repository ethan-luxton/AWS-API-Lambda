# AWS-API-Lambda

* The root URL to the API is https://c9n3lr948a.execute-api.us-west-2.amazonaws.com/getPeople

* The routes are:
    * /getPeople (CREATE)
    * /getPeople/{people_id} (GET ONE)

    ~ TODO:

    * /getPeople (GET ALL)
    * /getPeople/{people_id} (UPDATE)
    * /getPeople/{people_id} (DELETE)

* Inputs for each route are:
    * CREATE: JSON body containing a person with the following properties:
        * name
        * age
        * favColor
    * GET ONE: Use route /getPeople/{people_id}, as a GET request, and replace {people_id} with the ID of the specific table item.

* Outputs for each route are:
    * CREATE: 200 Status return with the JSON object that was created
    * GET ONE: The JSON object with all properties of the requested person

~ TODO: 

* Inputs and Outputs for:
    * /getPeople (GET ALL)
    * /getPeople/{people_id} (UPDATE)
    * /getPeople/{people_id} (DELETE)

## UML

![.UML](https://i.imgur.com/iPABNNc.png)

