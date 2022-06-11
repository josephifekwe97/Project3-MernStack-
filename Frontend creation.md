## create-react-app
` npx create-react-app client`

<span style="color:yellow"> install concurrently. It is used to run more than one command simultaneously from the same terminal window.<span>

`npm install concurrently --save-dev`


<span style="color:yellow"> Install nodemon. It is used to run and monitor the server. If there is any change in the server code, nodemon will restart it automatically and load the new changes.<span>


`npm install nodemon --save-dev`



## Update Package.json file in Todo Directory
![create index file](/Images/UpdatedPackage.json.png)


## Change directory to Cliets
`cd clients`




## Open the Package.json file
 Add "proxy": "http://localhost:5000"

 <span style="color:yellow"> i put   port 3000 in my package.json file<span>


`npm run dev`

### terminal view
![terminal view](/Images/Reactapp%20runing%20terminal%20view.png)



![React app in the brower](/Images/React%20rununing%20in%20the%20browers.png)

 <span style="color:orange">In order to be able to access the application from the Internet you have to open TCP port 3000 on EC2 by adding a new Security Group rule. You already know how to do it. <span>



## Creating your React Components
One of the advantages of react is that it makes use of components, which are reusable and also makes code modular. For our Todo app, there will be two stateful components and one stateless component.
From your Todo directory run

`cd client`

`cd src`

`mkdir components`

`cd components`

`touch Input.js ListTodo.js Todo.js`

`vim input.js`



![vim input.js](/Images/AxiosInputjs.png)

https://github.com/axios/axios "Axios Promise"

Move to the src folder

`cd ..`

Move to clients folder

`cd ..`

Install axios

`npm install axios`


![vim input.js](/Images/AxiosInstall.png)





