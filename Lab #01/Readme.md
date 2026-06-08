# Step 1 
/accountDetails Endpoint exposes api key in response with Access-Control-Allow-Credentials: true
# Step 2 
Adding Origin header and testing if it gets reflected in Access-Control-Allow-Origin
# Step 3 
Origin: blabla.com => Access-Control-Allow-Origin: blabla.com
Response Body:
` "username": "wiener",
  "email": "",
  "apikey": "l9htYZrH1kuBTKa3hhGChyuJibHeFyr7",
  "sessions": [
    "CMwhRLykfEa2fc739bvkMC8lPYaRNWRQ"
  ]`
# Classic CORS Misconfiguration
