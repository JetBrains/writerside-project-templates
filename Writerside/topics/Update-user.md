# Update user

<!-- Use multiple <sample> elements inside <request> to provide samples for various programming languages. 
They will be placed in tabs.Developers can use these samples as templates when making requests to this endpoint. -->

<api-endpoint openapi-path="./../openapi.yaml" endpoint="/user/{username}" method="put">

<request>

<sample title="JSON">
{
"id": 10,
"username": "theUser",
"firstName": "John",
"lastName": "James",
"email": "john@email.com",
"password": "12345",
"phone": "12345",
"userStatus": 1
}
</sample>

<sample lang="javascript" title="JavaScript">
const userPayload = {
  id: 10,
  username: "theUser",
  firstName: "John",
  lastName: "James",
  email: "john@email.com",
  password: "12345",
  phone: "12345",
  userStatus: 1
};
console.log(userPayload);
</sample>

</request>

</api-endpoint>
