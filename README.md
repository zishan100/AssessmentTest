## 1.)User SignUp POST API
http://localhost:8082/api/user/register
client side
#use postman form data to all these parameter 
body:{
  name:"Test",
  mail:"test@m.com",
  pasword:"123456"(pasword should be atleast 6 length),
  image:"upload image",
  DOB:"2000-10-03
}

## 2.)User Login POST API
http://localhost:8082/api/user/login
client side
use postman form  to all these parameter 
body:{
  mail:"test@m.com",
  pasword:"123456"(pasword should be atleast 6 length),
}

## 3.)User Profile GET API
client side
http://localhost:8082/api/user/profile

use postman headers to pass token parameter that you have received in response on sucessfully login
i.e authorization:token


