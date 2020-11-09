## Storage Account Configurations

=> **Step - 1**

1. go to Storage Account.

![Screenshot (535)](https://user-images.githubusercontent.com/46487696/98469980-a8158f00-2208-11eb-9ad2-3f05b66465ee.png)

2. Networking: default configurations

![Screenshot (536)](https://user-images.githubusercontent.com/46487696/98470008-d5fad380-2208-11eb-808c-6bfc4f6fba78.png)

3. Data Protection: Turn on SOFT DELETE for BLOBS AND FILE SHARES

![Screenshot (537)](https://user-images.githubusercontent.com/46487696/98470020-f165de80-2208-11eb-8d00-ac685324e475.png)

![Screenshot (538)](https://user-images.githubusercontent.com/46487696/98471110-2590cd80-2210-11eb-9628-8f8dbde3df14.png)


Here,  

4. Advance :

![Screenshot (539)](https://user-images.githubusercontent.com/46487696/98471126-380b0700-2210-11eb-87a0-d22e4beeebe1.png)


Now create the container,
5. Go To Container, option you will see inside your storage account

![Screenshot (540)](https://user-images.githubusercontent.com/46487696/98472470-4f9abd80-2219-11eb-9a3c-28f3994389e3.png)

When you will access it, it will show "AUTHORIZATION FAILED" because At starting we didnt provide any network and our default setting is "SELECTED NETWORK" Which include no network connection. thats why the error comes.

6. Go to "FIREWALLS AND VIRTUAL NETWORKS" and Select "ALL NETWORKS"

![Screenshot (547)](https://user-images.githubusercontent.com/46487696/98472560-d780c780-2219-11eb-8d23-1a3224b154e0.png)

after this when you will access it again it will give the access to the container.

![Screenshot (543)](https://user-images.githubusercontent.com/46487696/98477999-aa81e400-221c-11eb-8823-b20b5d35d4cd.png)

7. Now you can add any data just go to "UPLOAD" AND select data what you want from your local machine.

![Screenshot (544)](https://user-images.githubusercontent.com/46487696/98478471-e1f09080-221c-11eb-980c-8fb88426bbfb.png)

8. Now if you copied the link and try to run it, it will show you an error because access level is set to a private.
go to "CHANGE ACCESS LEVEL" and change it too BLOB or CONTAINER.

![Screenshot (545)](https://user-images.githubusercontent.com/46487696/98481141-27fa2400-221e-11eb-9f40-ef5fb4e2abf8.png)

