# CrickInformer
<br>
CrickInformer is your go-to platform for real-time cricket scores and updates. Leveraging web scraping techniques, we fetch live data from the renowned cricket website Cricbuzz, ensuring you never miss a moment of the action.<br><br>
Key Features:<br>
1- Live Score Updates: Instantly access live scores of ongoing matches right at the top of the screen. Clicking on the live score opens up a comprehensive view of all ongoing matches.<br>
2- Match History: Explore completed matches by clicking on the "All Matches" button, which fetches data from the backend and presents a detailed overview of finished matches.<br>
3- Points Table: Stay updated with the latest standings in cricket tournaments with just a click. The "Points Table" button provides an up-to-date overview of the World Cup standings.<br>
<br>
![Screenshot 2024-06-07 160846](https://github.com/lakshay8088/CrickInformer/assets/107973384/7b92634c-6a30-4af9-bd64-909ad86b5a97)
<br>
<br>
Technology Stack:<br>
Frontend: Angular, HTML, CSS, TypeScript.<br>
Backend: Spring Boot, Java, RESTful APIs.<br>
Data Scraping: Web scraping techniques to extract real-time data from Cricbuzz.<br>
Database: MySQL.<br>
<br>
Workflow:<br>
1- The frontend sends requests to the backend for various operations such as fetching live scores, retrieving match history, or obtaining the points table.<br>
2- The Spring Boot backend processes these requests, executing CRUD operations, business logic etc.<br>
3- For real-time data updates, the Data Scraping Backend continuously scrapes data from Cricbuzz, ensuring the latest cricket information is available.<br>
4- The extracted data is stored in the database for retrieval by the frontend or backend components.<br>
5- The frontend updates its interface based on the received data, providing users with a seamless and up-to-date cricket experience.<br>
6- This architecture ensures separation of concerns, scalability, and reliability, allowing CrickInformer to efficiently deliver real-time cricket updates to its users.<br>

![Screenshot 2024-06-07 162528](https://github.com/lakshay8088/CrickInformer/assets/107973384/e85b24e5-4a5c-41a5-b304-6d5a1cc51d94)
