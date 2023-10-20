# Where-s-My-Water

This project was for UF AI days hackathon and won First Place with 10,000 dollars prize money, and Most Popular Project with 1000 dollars prize money from among 46 projects and 400+ participants

Video Demo Link: https://youtu.be/KFEhOcZ3WAw


DevPost Link: https://devpost.com/software/where-s-my-water-apgu2q



Inspiration


Water constitutes 71 percent of our Earth, yet only 3 percent of Earth's water is freshwater. Of the freshwater, only 30 percent of it is groundwater, which is the primary source for human drinking water. Human activities, such as sustained groundwater pumping and pollution can lead to groundwater depletion and can affect groundwater quality. Not only is our source of drinking water affected, but the quality of the land is affected as well. For example, groundwater depletion can lead to surface water bodies, such as lakes, drying out. The rate at which we are using and treating groundwater prompted us to wonder about the future of groundwater resources in the United States. The Data Source We Used: link

What it Does


“Where's My Water!” is an online web application designed to address the issue of groundwater depletion and use generative AI to visualize and predict trends in groundwater in the United States by utilizing USGS groundwater data. The first aspect of our project involves the use of the Stable Diffusion open source library and image generation. We will prompt users to visualize a lake or well that is under groundwater depletion and generate the image for them to understand one of the major effects of this problem. We left this portion of the project in Google Colab in case users would like to specify in the prompt a particular lake or well in their state. For example, we used Lake Mead for Prompt A. We hope that allowing users to visual groundwater depletion for the surface water bodies they know best will show how serious the issue is. The second aspect of our web application is our groundwater future prediction dashboard. This aspect of our project is accessed through our website, and users are prompted to enter a year and state and see groundwater predictions for the chosen state in the United States.

How We Built It


We constructed “Where's My Water!” using Google Colab. For the image generation portion of our project, we relied on the open source library called Stable Diffusion to help us generate images of lakes and wells undergoing groundwater depletion. To create our groundwater future prediction dashboard, we used the Google Earth Engine API to display a map of the United States. To create our AI model, we used tensorflow and keras to train and fit our model based on a dataset from USGS groundwater data collection sites. To display our dashboard in our website, we used flask and the ngrok API.

Challenges We Ran Into


The first challenge we ran into was the fact that some data entries in our USGS dataset were missing key information about groundwater depth, site information, or dates. Before we could start training our data, we had to make sure it was cleaned. Another challenge we ran into was ensuring our model gave accurate results. When we initially ran the model, we were not satisfied with its accuracy. Thus, we had to add more code to normalize the data and improve the quality of the results we were receiving. We also had to learn how to navigate new technologies such as Google Colab, Tensorflow, and Earth Engine to ensure our project is functional which posed a learning curve for our team.

Accomplishments We're Proud Of


First and foremost, we are proud that our team is fully female. We hope that working on this project and presenting our idea to the judging panel inspires other women to get involved with computing, artificial intelligence, and Earth science as these are all fields in which women are severely underrepresented. Secondly, we are proud that our project provides a solution which does not exist yet. Prior to starting our project, we conducted extensive research to see if there were other projects which addressed groundwater depletion with artificial intelligence. We saw a void in the industry to combine soil, water, and ecosystem sciences with computing and artificial intelligence, and we hope that this project starts the conversation to combine both fields to benefit our people and our planet. Lastly, we are also proud of how quickly our team was able to adapt and learn about new technologies to make the project functional.

What We Learned


We learned how to use Google Colab, Google Earth Engine, Tensorflow, NVIDIA SMI, and open source libraries to make our project function, but we also learned how to work collaboratively in a team and meet deadlines to ensure our project was submitted on time.

What's next for Where's My Water!


We hope to improve our model to give more accurate results. We also hope to expand our dataset to include more states by working with the USGS to increase the number of reporting sites which are available in the United States. We hope that this project sparks the conversation about the importance of protecting our water resources, and that our project can be used to discuss the future of our water resources with the general public and science community.

Acknowledgements


Dr. James Jawitz- Soil, Water, and Ecosystem Sciences; Dr. James Bonczek- Soil, Water, and Ecosystem Sciences; Dr. Heather Enloe- Soil, Water, and Ecosystem Sciences; Dr. Mary Lusk- Soil, Water, and Ecosystem Sciences; Dr. Andy Ogram- Soil, Water, and Ecosystem Sciences; Dr. Raquel Dias- Microbiology; Dr. Laura Castro Cruz- Computer and Information Science and Engineering; Professor Lisha Zhou- Computer and Information Science and Engineering; Dr. Sanethia Thomas- Computer and Information Science and Engineering; Professor Cheryl Resch; Girls Who Code at UF; Women in Computer Science and Engineering at UF; the United States Geological Survey; NVIDIA
