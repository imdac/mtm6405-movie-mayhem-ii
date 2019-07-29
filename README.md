# Movie Mayhem II

## Objective
For this assignment you will be demonstrating your skills and understanding of SQL Queries and the SELECT, INSERT, UPDATE, and DELETE statements by creating queries to retrieves and manipulate data from the Movie Mayhem database.

## Database
For this assignment you will be using the Movie Mayhem database which is provided with repository as the [Movie Mayhem SQL File](movie_mayhem.sql).

## Requirements
The following requirement must be met in order to complete the assignment successfully: 

### 1. Clone the Repository
Clone this repository from GitHub and use the provided file to complete the assignment.

### 2. Import the Movie Mayhem Database
To import the database, using phpMyAdmin, complete the following instructions.

1. Open phpMyAdmin at [http://phpmyadmin.test](http://phpmyadmin.test)
2. Log into phpMyAdmin using the root username and password
3. From the phpMyAdmin homepage, click on the "Import" tab found at the top of the page.
4. Under the "File to import" section, click the "Choose File" button. Choose the `movie_mayhem.sql` file found in this repository.
5. Click the "Go" button found at the bottom of the page. 
6. Once the importing has completed, click on the seussology database which should appear in the list on the left side of page.
7. With the movie_mayhem database selected, click on the "SQL" tab at the top of the page. From this page, you can execute custom SQL commands.

### 3. Create SQL Queries
Create **ONE** query for each of the tasks below. The queries should be saved in the `queries.sql` file.

#### 1. Add a movie to the `movies` table with the following data:

| movie_title | director | year | genre_id |
| :---:       | :---:    |:---: | :---:    |
| 'WALL-E'      | 'Brad Bird' | 2008 | 2       |

#### 2. Using a subquery, add a movie to the `movies` table with the following data:

| movie_title | director | year | genre_title |
| :---:       | :---:    |:---: | :---:    |
| 'Inside Out'  | 'Peter Doctor' | 2014 |  'Family' |


#### 3. Update the year (`year`) to `2015` for the movie with the title (`movie_title`) 'Inside Out'.

#### 4. Using a subquery, update the director (`director`) to 'Peter Doctor' and the genre to 'Romance' for the movie with the title (`movie_title`) 'WALL-E'.

#### 5. Remove all the movies from the director (`director`) 'Peter Doctor'. 


## Submission
1. Create a commit with the message "Completed the Movie Mayhem II Assignment"
2. Push to GitHub
3. Submit the URL to your GitHub Repository in BrightSpace

By making the submission you also agree to the Algonquin College Student Attestation of Academic Integrity below: 

**I hereby declare that the work I submit throughout the duration of this course/program will be my own work.**

**I understand that plagiarism, whether done deliberately or accidentally, is defined as presenting someone else’s work, in whole or in part, as one’s own, and includes the verbal or written submission of another work (for example, ideas, wording, code, graphics, music, and inventions) without crediting that source. This includes all electronic sources (for example, the Internet, television, video, film, and recordings), all print and written sources (for example, books, periodicals, lyrics, government publications, promotional materials, and academic assignments), and all verbal sources (for example, conversations and interviews).**

**I understand that the facilitation of plagiarism, that is, one student sharing his or her work with other students, is also considered an act of plagiarism.**

**I understand that contravening Algonquin College Policy AA 20 - Plagiarism will result in an academic sanction(s) as described in this directive.**