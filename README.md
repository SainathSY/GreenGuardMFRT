<h1>Green Guard</h1>

Green Guard is a web application for plant leaf disease detection. The application uses deep learning models to predict the presence of disease in plant leaves based on images uploaded by users. The goal of the application is to help farmers and gardeners identify plant diseases early and take appropriate action to prevent crop losses.

<h2>Getting Started</h2>

To use Green Guard, simply visit our website [https://greenguardmfrt.azurewebsites.net/] and upload an image of a plant leaf. The deep learning model will analyze the image and provide a prediction of whether the leaf is healthy or diseased, as well as information about the specific disease and remedies if applicable in both English and Kannada languages.You can make use of the images in the folder 'Plant_Images_For_Tesing' for testing the website.

<h2>Built With</h2>

Green Guard is built using the following technologies:

Python

Flask

TensorFlow

HTML/CSS


<h2>Website Tour</h2>


![Screenshot (319)](https://user-images.githubusercontent.com/93444827/235931720-f77b2911-5f4f-46a0-9a89-0a638d9d0942.png)

![Screenshot (320)](https://user-images.githubusercontent.com/93444827/235931810-5ac8fa51-0770-4c78-9073-d28c1ad113e8.png)

<h3>Prediction</h3>

![Screenshot (321)](https://user-images.githubusercontent.com/93444827/235931918-a58bedeb-002b-47b0-ac22-abfb36634580.png)

<h3>Disease Name</h3>

![Screenshot (322)](https://user-images.githubusercontent.com/93444827/235932089-7c35843a-ad3b-4b47-b286-68ce55826044.png)

<h3>Remedies in English</h3>

![Screenshot (323)](https://user-images.githubusercontent.com/93444827/235932244-7d14f6e8-c9db-4806-bdd4-7fcd5b893762.png)

<h3>Remedies in Kannada</h3>

![Screenshot (324)](https://user-images.githubusercontent.com/93444827/235932335-3e50d466-1843-42cc-ab9e-4146d364947c.png)


<h2>Deployment</h2>

Used the Azure App Service to deploy the flask app developed. The image shows that the app is up and running.

![Screenshot (325)](https://user-images.githubusercontent.com/93444827/236186295-f3b6e34d-780e-40bf-9455-075e3084ec97.png)

Used Azure CosmosDB for MongoDB Service to store and fetch remedies for the diseased plants. The image shows that the database is online.

![Screenshot (326)](https://user-images.githubusercontent.com/93444827/236186624-eb0f324f-0096-429e-b3e1-5e957d0c025b.png)


<h2>Link for the Deep Learning Model built</h2>

https://colab.research.google.com/drive/1hfPsmKR7XzrRFlmtojoOVD3OfGwbhbFv?usp=sharing


<h2>Link for project demonstration video</h2>

https://youtu.be/P3UFT2JcH_c


<h2>Acknowledgments</h2>

We would like to thank the developers of TensorFlow and Flask for their excellent open-source projects.

We would also like to thank the research community for their work in the field of plant leaf disease detection, which has helped us build a more accurate model.
