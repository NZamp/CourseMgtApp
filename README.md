# CourseMgtApp
A Spring/Java WebApp for managing University Courses, built with the MVC architecture. The users of the application have the ability to:
- Login with their account and view their taught Courses  
- Add an upcoming Course for the next semester or update the information of an existing one
- Have access to a statistical overview of each Course's final grades (Min,	Max,	Mean,	Median,	Skewness,	Kurtosis,	st. Deviation and	Variance) 
- Manage the Students who enrolled in the course:
  - Add, edit or remove a student to/from the Student List 
  - Configure each student's Project and Exam Grades

## Technologies Used
- Java and Springboot for the main code, following the MVC pattern
- MySQL to build a simple database containing the Courses and the Students
- HTML and the Thymeleaf engine to display the Webpage Frontend
- Eclipse for the Projet Development
- JUnit and Mockito to create Unit Tests for the code
- Apache Math API to provide the Course's statistic data

## Screenshots

#### The Main View:

![Screenshot_1](https://github.com/NZamp/CourseMgtApp/assets/25671112/3cfa6960-a420-49cc-b05d-2bcb4e9c1462)

#### Students List of the Course "Software Engineering":

![Students List](https://github.com/NZamp/CourseMgtApp/assets/25671112/655d6e04-fa8c-4baa-8d93-9d86cf5931ba)

#### Enrol a Student to the Course: 

![Enrol a Student to the Course](https://github.com/NZamp/CourseMgtApp/assets/25671112/7ff153c2-e207-47a1-a0ae-a4e5d9db23d6)

#### View the Course's Statistics:

![View the Course's Statistics](https://github.com/NZamp/CourseMgtApp/assets/25671112/d3209096-ade9-4fd8-99b5-fca7c9e0c7d9)
