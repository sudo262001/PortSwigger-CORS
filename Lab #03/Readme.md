# Step 1

/accountDetails Endpoint exposes api key in response with Access-Control-Allow-Credentials: true

# Step 2

Adding Origin header and testing if it gets reflected in Access-Control-Allow-Origin

# Step 3

Nothing gets reflected, Trying Origin: null

# Step 4

null does not get reflected

# Step 5

trying subdomains with http protocol

# Step 6

origin reflected!!

# Step 7

searching for vulnerable parameter for xss

# fonud:

`http://stock.0a6400ff0408133a800803fa00fa0018.web-security-academy.net/?productId=<script>alert(1)</script>&storeId=1`# Step 1
/accountDetails Endpoint exposes api key in response with Access-Control-Allow-Credentials: true

# Step 2

Adding Origin header and testing if it gets reflected in Access-Control-Allow-Origin

# Step 3

Nothing gets reflected, Trying Origin: null

# Step 4

null does not get reflected

# Step 5

trying subdomains with http protocol

# Step 6

origin reflected!!

# Step 7

searching for vulnerable parameter for xss

# fonud:

`http://stock.0a6400ff0408133a800803fa00fa0018.web-security-academy.net/?productId=<script>alert(1)</script>&storeId=1`
