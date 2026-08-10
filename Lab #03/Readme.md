# /accountDetails Endpoint exposes api key in response with Access-Control-Allow-Credentials: true
# Adding Origin header and testing if it gets reflected in Access-Control-Allow-Origin
# Nothing gets reflected, Trying Origin: null
# null does not get reflected
# trying subdomains with http protocol
# origin reflected!!
# searching for vulnerable parameter for xss
# fonud: 
`http://stock.0a6400ff0408133a800803fa00fa0018.web-security-academy.net/?productId=<script>alert(1)</script>&storeId=1`