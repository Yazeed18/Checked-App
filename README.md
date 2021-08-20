Simple to do list app that allows users to create, read, update and then delete items on their list. Hence, "Checked" to signify finishing off their to do list since there is no better feeling than finishing your tasks you planned. 

This app was made using a django backend to create the Todo Model. This model consists of 3 main headings to be used when making each of the tasks. They are Title, Description and a completed boolean (i.e True or False). 
The REST framework was then set up along with CORS to manage the headers to be used when setting up the tasks. This also brings about CRUD operations that can be done using the Todo model in the backend. 
After the backend and the API are all set, ReactJS was then used to create the frontend along with bootstrap for designing so that there is a user friendly way to making the tasks and items on the App. 
Lastly, Axios was utilised to help facilitate ease in requesting Data from the API, returning data from the API and performing actions using the Data in the React frontend.

Below highlights the CRUD operations of the Checked App.

Create: 

![Todo_Create](https://user-images.githubusercontent.com/45414646/130195712-d679d368-29c5-41f0-a4e3-6df237417698.gif)

Read:

![Todo_Read](https://user-images.githubusercontent.com/45414646/130195730-13067891-43ee-44f5-8382-b3c5d994f36e.gif)

Update:

![Todo_Update](https://user-images.githubusercontent.com/45414646/130195732-c2ebeea9-267b-4981-91f9-cea35be7e267.gif)

Delete:

![Todo_Delete](https://user-images.githubusercontent.com/45414646/130195729-7c221c2a-e6a2-42ee-8542-e051621ccbaa.gif)
