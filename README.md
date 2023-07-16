
<H1 align = "center"> Baisakhi AI </H1>


#### `Datasets from:`  [fao](http://www.fao.org/statistics/databases/en/) ; [Kaggle](https://www.kaggle.com/)
#### `Demo Video:` (https://youtu.be/9P8y4eir8bo) 


    
# Problem Statement
<p>
  <h3>Crop Guidance and Farmers Friend</h3>
 In a world where the demand for food is increasing due to a growing population, the need for innovative agricultural solutions has become more crucial than ever. Small towns and rural areas have witnessed a surge in individuals turning to farming in order to meet the rising demand for crops. However, traditional farming methods alone are unable to fulfill the requirements of modern agriculture, which necessitates high-yield, high-quality, and efficient production. This made us to do this project in this super hackathon. </p> 
  
# Our Solution
<p>
The core functionality of the platform lies in its ability to analyze vital soil parameters and provide personalized crop recommendations. By inputting **crucial information such as soil pH, nutrient levels, and climate conditions, the AI algorithms process and interpret the data to generate a comprehensive list of crops best suited to the specific land conditions**.

This process takes into account various factors critical to successful crop cultivation, including water requirements, temperature tolerance, and potential yield. By leveraging historical data spanning the past two decades, the AI models have been trained to accurately predict future trends, enabling farmers to make informed decisions regarding their crop choices.

The platform acts as a reliable and intelligent partner, empowering farmers to select crops that align with market demands and consumer preferences. By adapting to shifting consumer trends, farmers can optimize their profitability and ensure their products remain competitive in the ever-evolving agricultural landscape.

To streamline the entire crop cultivation process, the platform includes a MetaMask wallet feature. This integrated functionality allows farmers to conveniently purchase the recommended crop seeds directly through the platform. By eliminating the need for separate transactions or additional steps, farmers can save time and resources, enabling a smoother and more efficient farming experience.
Additionally, We've also included a web-3 based transaction for farmers to buy the seeds for recommended crop using ethereum

</p>

## `Implementation`

### The implementation of this project using the Django framework and scikit-learn library involved the following steps:
<ol>
  <li>Created a new Django project and built a form in Django that allows farmers to input their soil parameters and submit the data to the application.</li>
  <li>Used scikit-learn to train a machine learning model on a dataset of soil parameters and corresponding crop recommendations imported from Kaggle.</li>
  <li>Created a view in Django that takes the soil parameters from the form and uses the trained model to generate a recommended crops.</li>
  <li>Display the recommended crops to the farmer on a web page, along with information about the suitability of each crop for the given soil conditions with it's yeild given the land under cultivation.</li>
  <li>Used the Django middleware for handling security and authentication for the project.</li>
  <li>Finally Deployed the project on a web server and make it available for farmers to use.</li>
</ol>

## `Key Features`
<ol>
  <li>Soil parameter input: Farmers can input data such as soil pH, nutrient levels, and climate conditions, into a web form, which will be stored in a database.</li>
  <li>Crop recommendations: Using machine learning algorithms, the system analyzes the soil parameters and generate a list of crops that are best suited to those conditions.</li>
  <li>Security and Authentication: The system has built-in security and authentication features to ensure that only authorized users can access the data and the system.</li>
  <li>Easy deployment: The system is easy to deploy on a web server, making it accessible to farmers all over the world.</li>
  <li>Scalability: The system is built in a way that allows for easy scalability, so that it can handle an increasing number of users and data sets.</li>
  <li>Customizable: The system is customizable and can be easily tailored to the specific needs of different regions and farming communities.</li>
  <li>User-friendly: The system is designed with a user-friendly interface, making it easy for farmers to use and navigate.</li>

</ol> 


## `Tech Stack`
<ul>
  <li>Scikit-learn</li>
  <li>django</li>
  <li>Python</li>
  <li>Python Virtual Env</li>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>BootStrap</li>
  <li>Javascript</li>
  <li>Polygon</li>
  <li>Ethereum</li>
  
  
</ul>  


## `Installation`

```console
# Clone the project
$> git clone https://github.com/arnavgupta2003/BaisakhiAI.git

# Deploy a Python virtual Environment
$> virtualenv myEnv
$> myEnv\Scripts\activate

# Install Project Requirements
$> pip install -r requirements.txt

# Migrate the project
$> python manage.py migrate

# Start the Development Server
$> python manage.py runserver
      
      
```

`Check Output`

Access the project on https://127.0.0.1:8000
 

 

## `Upcoming Features`
<ol>
   <li>Data visualization: The system will provide farmers with an easy-to-understand visualization of the crop recommendations and soil parameters, making it easy for them to understand the information.</li>
  <li>Data Management: An admin interface that allows authorized users to add, edit, and delete data from the database, making it easy to maintain and update the system.</li>
  <li>Help Section: The system will connect farmers with other experts in this field which also includes other farming communities across the world.</li>
  <li>
  We have added yet another animal husbandry feature that can be expanded upon in the future. All Challenges faced in Animal husbandary and animal farming will be adressed and best possible solution for different environments will be exported via AI/ML
  </li>
  <li>
  In order to prevent scams and fraud, we will also be developing new features that can record and track Delivery.
  </li>
  
</ol>  

# Conclusion
<p>
  Baisakhi AI is a powerful tool that can help farmers improve their crop selection and increase their chances of a successful harvest. By analyzing soil parameters and providing recommendations based on factors such as water requirements, temperature tolerance, and potential yield, the system can assist farmers in making informed decisions about the crops they choose to grow.

The system's features such as soil parameter input, crop recommendations, crop suitability, data visualization, data management, security and authentication, easy deployment, scalability, customizable and user-friendly interface make it an ideal solution for farmers all over the world.

In conclusion, Baisakhi AI has the potential to revolutionize the way farmers make decisions about their crops, by providing them with accurate and relevant recommendations. By optimizing crop selection, farmers can improve their profitability and sustainability, while reducing costs and labor. This can ultimately contribute to the sustainable development of the agricultural sector, benefiting farmers and society as a whole.
</p>

# Screenshots
![ScreenShot 1](https://github.com/navinajk/Baisakhi.ai/blob/main/s1.jpg)

![ScreenShot 2](https://github.com/navinajk/Baisakhi.ai/blob/main/s2.jpg)

![ScreenShot 3](https://github.com/navinajk/Baisakhi.ai/blob/main/s3.jpg)

![ScreenShot 4](https://github.com/navinajk/Baisakhi.ai/blob/main/s4.jpg)

<p align=center> --- EOF --- </p>
