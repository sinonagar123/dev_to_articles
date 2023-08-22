
**HTTP** is Hypertext Transfer Protocol.

**HTTP** is designed to enable communication between clients and servers. **HTTP** works as request-response between client and server.

 HTTP methods

- _**GET**_
- _**POST**_
- _**PUT**_
- **_HEAD_**
- _**DELETE**_
- _**PATCH**_
- _**OPTIONS**_
- _**CONNECT**_
- _**TRACE**_


Two most common http methods are
**GET** and **POST**


![http method](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ew8c7th8xnl2d7m62mxp.jpeg)

## **GET Method**

Appends data to the URL in the form of name or value pair.
Request data from a specified resource. A GET Request is used to request information from a resource such as a
website, a server, or an API.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/we0ayut3vsn7ztndu0ps.jpeg)

## **POST Method**

Web server accepts data included in the body of the message.
Send data to server to create/update a resource.It Creates a new Resource on the backend (Server). We send data to the server in the request body.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xdohy16huvw9rnqa59gz.jpeg)

Now what is the difference between _**GET & POST Method**_


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/l65lhuau1unp3te20u4j.jpeg)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nv6esp0irunxtrm3ve5l.jpeg)

## **PUT Method**

Send data to server to create/ update a resource
Only difference between put method is calling same **_PUT_** request multiple times will always produce the same result. But **_POST_** requests repeatedly have same resource multiple times.Using this, we can update an existing resource by sending the updated data as the content of the request body to the server.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dd4y0cra1hcm16goapgr.jpeg)

## **HEAD Method**

The _**HEAD**_ method is similar to the
**_GET_** method. But it doesn't have any response body. Only difference between **_HEAD_** method is make the request but not return **_GET_** Method make request and return. So if it mistakenly returns the response body, it must be ignored.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vh9yavltd8oc4ysypg9f.jpeg)

## **DELETE Method**

The _**DELETE**_ method deletes a resource. Regardless of the number of calls, it returns the same result

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/iqorqy7t55ymxr7qu2xn.jpeg)

## **PATCH Method**

Similar to **_PUT_** , **_PATCH_** updates a resource, but it updates data partially and not entirely.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/f0bbreoslapn8hrlgnhb.jpeg)

## **OPTIONS Method**

Describe the communication options for target resource. It used to get information about the possible communication options for the given URL or an asterisk to refer.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dylxzm6t5mxwq0122igz.jpeg)

## **CONNECT Method**

Used to start a two way communication with the requested resources.The **_Connect_** Method is for making end to end connections between a client and a server. It makes a two way connection like a tunnel between them.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/y7dkffo948q3bbu1s0rk.jpeg)

## **TRACE Method**

Used to perform a message loop back test that tests the path for target resource. Useful for debugging purposes.The **_TRACE_** Method is for diagnosis purposes. It creates a loop-back test
win the same request body that the client sent to the server before, and the successful response code is 200


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dbbtfz6jkfevu2maqte1.jpeg)
