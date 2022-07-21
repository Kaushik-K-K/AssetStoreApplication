# AssetStoreApplication

#signin

POST - http://localhost:8080/api/auth/signin

{
    "usernameOrEmail" : "admin@gmail.com",
    "password" : "admin"
}

#AssetStore

Authentication Type -Bearer token


GET - http://localhost:8080/api/asset   

GET - http://localhost:8080/api/asset/1001

POST - http://localhost:8080/api/assets

{
        "id": 1004,
        "assetname": "nokia",
        "storedetails": [
            {
                "storeid": 2008,
                "storevalue": 30000
            },
            {
                "storeid": 2007,
                "storevalue": 40000
            }
        ]
    }
    
PUT - http://localhost:8080/api/asset/1001

{
        "id": 1004,
        "assetname": "samsung",
        "storedetails": [
            {
                "storeid": 2008,
                "storevalue": 32000
            },
            {
                "storeid": 2007,
                "storevalue": 42000
            }
        ]
    }
    
DELETE - http://localhost:8080/api/asset/1001

