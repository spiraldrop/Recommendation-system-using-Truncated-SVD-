# Recommendation-system-using-Truncated-SVD

### About this project

This project touches the surface of how basic recommendation systems work with singular value decomposition (SVD) and the SGD algorithm. 

There are a total of two tasks, but the first one explains the working of the algorithm in much more pedantic detail. In this task, we predict the rating for a given (user_id, movie_id) pair by finding  𝑦̂ 𝑖𝑗. It can be calculated by solving the below equation:

![image](https://user-images.githubusercontent.com/64201589/133935189-ceb57732-7a2e-4734-85a1-a83d5d409305.png)

where we find the best values of bi and cj by solving the below optimization problem:  

![image](https://user-images.githubusercontent.com/64201589/133935207-ed977c10-bac6-4221-b36a-cffb9fb14033.png)

where, ![image](https://user-images.githubusercontent.com/64201589/133935219-b4345bcb-1c41-44f5-ae5d-32509364b0be.png)
 
We start by applying SVD decomposition on an Adjacency matrix which is just a sparse representation of user ratings on movies. Further instructions have been mentioned in the documentation part of the notebook. 

### Link to the files:
https://drive.google.com/file/d/1-1z7iDB52cB6_JpO7Dqa-eOYSs-mivpq/view?usp=drive_open

### Link to the course:
https://www.appliedaicourse.com/course/11/Applied-Machine-learning-course 


