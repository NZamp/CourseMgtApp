# CourseMgtApp
A Spring/Java WebApp for managing University Courses, built using the MVC architecture. The users of the application have the ability to:
- Login with their account and view their taught Courses  
- Add an upcoming Course for the next semester or update the information of an existing one
- Have access to a statistical overview of each Course's final grades (Min,	Max,	Mean,	Median,	Skewness,	Kurtosis,	st. Deviation and	Variance) 
- Manage the Students who enrolled in the course:
  - Add, edit or remove a student to/from the Student List 
  - Configure each student's Project and Exam Grades

## Technologies Used
- Java and Springboot for the main code, following the MVC pattern
- MySQL to build a simple database containing the Courses and the Students Registrations
- HTML and the Thymeleaf engine to display the Webpage Frontend
- Eclipse for the Projet Development
- JUnit and Mockito to create Unit Tests for the code
- Apache Math API to provide the Courses' statistic data

## Screenshots

#### The Main View:

![Screenshot_1](https://github.com/NZamp/CourseMgtApp/assets/25671112/fbb7f3d2-a89e-41ed-b3aa-58c10009d2e0)

#### Students List of the Course "Software Engineering":
![Screenshot_2](https://github.com/NZamp/CourseMgtApp/assets/25671112/7a796d9e-fcd5-44a8-ba74-d5477bae4201)

#### Enrol a Student to the Course: 
![Screenshot_3](https://github.com/NZamp/CourseMgtApp/assets/25671112/dcc87481-bd33-424f-8beb-32f7a29c0999)


#### View the Course's Statistics:
![Screenshot_4](https://github.com/NZamp/CourseMgtApp/assets/25671112/a44efd26-aa81-4171-b085-b851d95daa7d)
