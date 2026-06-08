# Step 1
/accountDetails Endpoint exposes api key in response with Access-Control-Allow-Credentials: true
# Step 2
Adding Origin header and testing if it gets reflected in Access-Control-Allow-Origin
# Step 3
Nothing gets reflected, Trying Origin: null
# Step 4
Access-Control-Allow-Origin: null gets reflected
# sandbox can cause origin header
