# beusalons
npm run watch ( use this script to start the server)

url:- http://localhost:8010/api/v1/user/detail
method:GET
response:- {
    "success": true,
    "message": "Data Fetch Successfully",
    "data": [
        {
            "userId": 3,
            "averageBillValue": 850,
            "noOfOrders": 2,
            "name": "Ankita"
        },
        {
            "userId": 2,
            "averageBillValue": 966.6666666666666,
            "noOfOrders": 3,
            "name": "Ramesh"
        },
        {
            "userId": 1,
            "averageBillValue": 650,
            "noOfOrders": 5,
            "name": "Rahul"
        }
    ]
} 

///////////////////////////////////////////////////////////////
 url:-  http://localhost:8010/api/v1/user/update
method:PUt
response:- {
    "success": true,
    "message": "Successfully Updated",
    "data": []
}
