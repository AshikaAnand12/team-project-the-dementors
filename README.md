# CheckInn 
#### [Github](https://github.com/gopinathsjsu/team-project-the-dementors/) | [Sprint Sheet](https://github.com/gopinathsjsu/team-project-the-dementors/blob/main/Sprint%20Sheet%20Team%20Dementors-1.xlsx) | [Project Journal](https://github.com/gopinathsjsu/team-project-the-dementors/blob/main/CMPE-202%20Project%20Journal%20(1).docx) | [Project Board](https://github.com/gopinathsjsu/team-project-the-dementors/projects/1)

### Team Members:    
1. Ashika Anand Babu   
2. Ramya Mahesh   
3. Anusha Gangasani    
4. Shruthi Srinivasan

### Tech Stack:
<p>
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="HTML" width="48" height="48"/>
<img src="https://www.vectorlogo.zone/logos/w3_css/w3_css-icon.svg" alt="CSS" width="48" height="48"/>
<img src="https://www.vectorlogo.zone/logos/java/java-icon.svg" alt="Java" width="48" height="48"/>
<img src="https://www.vectorlogo.zone/logos/javascript/javascript-icon.svg" alt="Java" width="48" height="48"/>
<img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg" alt="AWS" width="48" height="48"/>
<img src="https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg" alt="AWS" width="48" height="48"/>
<img src="https://www.vectorlogo.zone/logos/reactjs/reactjs-icon.svg" alt="React" width="48" height="48"/>
</p>

### Project Files:
1. [Architecture Diagram](https://github.com/gopinathsjsu/team-project-the-dementors/blob/main/Architechture%20Diagram.pdf)
2. [Class Diagram](https://github.com/gopinathsjsu/team-project-the-dementors/blob/main/Class%20Diagram.png)
3. [DB Design](https://github.com/gopinathsjsu/team-project-the-dementors/blob/main/updated-database-design.pdf)
4. [Wireframes](https://github.com/gopinathsjsu/team-project-the-dementors/tree/main/Wireframes)
5. [Deployment Diagram] (https://github.com/gopinathsjsu/team-project-the-dementors/blob/main/Deployment.pdf)

### XP values followed: 
1. Communication : Communicated openly on the expectations of each stories, dependencies and implementation methods. We used to meet once in a week on  Mondays, to discuss the status, issues/blockers and what has been worked on till date. Prioritize the features which has more dependency. Highlight Blockers. 
2. Feedback : Every feature was discussed on implementation details and pick the one which suits our project the best. Frequent PR reviews.

3. Simplicity : Implemented only the features that has been asked for. Keep the Backend, UI and Database design simple.

4. Sit together : Debug the issues together and fix it. Give the demo of the features implemented once a sprint.  

5. Pair programming : Architecture design, DB Design, Wireframes and Deployment designs were discussed and finalised on Monday syncup calls.

6. 2-weeks sprint/bi-weekly cycle: We followed two week sprint acitivity and developed the product in 4 sprints. 

### Project Flow:
1. Our web application starts at:
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167717064-89a5ba77-716f-43fe-b29d-dd78848abb06.png">
2. We can register a user or login
3. On login: we are presented with the search page:     <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167717379-7b90a5fe-cc45-41ae-a4d1-3012b4810834.png">    
4. Select your city, rooms, dates and continue search - we are provided an option to select the hotel from list of hotels:     <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167717639-c2f116ec-097b-42e8-bd00-e41b4bec50f9.png">.    
5. Select the hotel of your choice and then select the type of room here:    <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167717774-f1760e38-465e-4f8a-aae8-996ab84da5d8.png">     
6. After selecting the type of room, select the amenities you need and if you would like to book using rewards points:    <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718209-ab0a8272-23ef-458b-b338-8df1dabcbe02.png">    
7. Checkout and confirm booking:    <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718279-419e1901-70d3-4185-966e-31fb99c55b7a.png">    
8. You can manage all your bookings at:     <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718428-cc0c0d2f-35c4-4ada-89c0-e769cae39ce5.png">
9. Edit booking date: <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718628-910d3846-1985-4163-8c76-9e3b4f10a805.png">
10. Delete bookings: <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718745-423f3d16-1461-465b-b973-463ebc679681.png">
11. View your profile: <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718817-c442b126-8935-49a1-9177-7353fdcf8a3b.png">
12. Sign out
13. If you are an employee, login and view all the bookings of a hotel as: <img width="1440" alt="image" src="https://user-images.githubusercontent.com/61357783/167718994-04a312b0-a12a-47fc-8814-820ee69d1813.png">



### Implemented the Backend using: Model View Controller

MVC (Model-View-Controller) is a pattern in software design commonly used to implement user interfaces, data, and controlling logic. It emphasizes a separation between the software's business logic and display. This "separation of concerns" provides for a better division of labor and improved maintenance. Some other design patterns are based on MVC, such as MVVM (Model-View-Viewmodel), MVP (Model-View-Presenter), and MVW (Model-View-Whatever).

The three parts of the MVC software-design pattern can be described as follows:

- Model: Manages data and business logic.
- View: Handles layout and display.
- Controller: Routes commands to the model and view parts.

![model-view-controller-light-blue](https://user-images.githubusercontent.com/90420965/167730264-4d502dd5-1b28-4150-bc79-ea554c05c797.png)

