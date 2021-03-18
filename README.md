# task-planner-api-part-2


1. Create a subfolder named add-task and create a file named index.js. The file should export a function implementing the logic for adding a task. It gets two arguments: a context object where you can send the response of your function and the req object where the payload of the request is received. In the req.body object you will get the body of your request with the fields of a task to be created.

![image](https://user-images.githubusercontent.com/48265107/111675666-623a8a00-87eb-11eb-9693-c97226f863a9.png)

2. Given you will deploy your function as a REST endpoint to Azure, you need a file named function.json in the add-task folder with the following contents:

![image](https://user-images.githubusercontent.com/48265107/111676042-c0676d00-87eb-11eb-80d0-f7610af90daf.png)

3. If you are interested in testing your function locally, create a file at the root folder of your project named local.settings.json with the following contents:

![image](https://user-images.githubusercontent.com/48265107/111676148-e4c34980-87eb-11eb-8be6-f8222d463b76.png)

4. Then, run the following command to get a local endpoint for testing your API.

![image](https://user-images.githubusercontent.com/48265107/111676265-01f81800-87ec-11eb-90c1-9c25241e1cba.png)

![image](https://user-images.githubusercontent.com/48265107/111676589-53080c00-87ec-11eb-9530-e99c6fa540b1.png)

