#  CINS 3002 - FINAL EXAM

<details>
  <summary>
    🚩 Instructions: Read before proceeding
  </summary>

  1. All functions will be defined in functions.py
  2. All classes will be defined in classes.py
  3. All function calls will be made from main()
  4. All exceptions must be handled
  5. Import whatever packages you need
  6. You must do all type conversions as necessary
</details>


<details>
  <summary>
    ✅ Part 1: 10 pts
  </summary>
  
  - Write a while loop that will generate random integer between 4 and 10 until the user presses 0 (zero)
</details>


<details>
  <summary>
    ✅ Part 2: 20 pts
  </summary>

  - The file movies.txt has data in the format movie id, movie name, movie year and movie rating separated by ;
  - Using option 3,
  - read movies.txt into a multidimensional list
  - ask user to provide movie name
  - look for the movie name in the multidimensional list (use case-insensitive comparision)
  - if found,
    - ask user to enter rating (rating must be integral value between 4 and 10)
    - change the rating for that movie to the user entered value
  - else, print movie not found
  - write the updated list back to the file in the same ; delimited format
  - Handle any and all exceptions
</details>


<details>
  <summary>
    ✅ Part 3: 30 pts
  </summary>

  Dictionary Structure: movies.pkl stores a nested dictionary  
  - the keys of this dictionary are movie IDs in `string` format
  - the value is a dictionary as follows
    - `name` -> movie_name (string)
    - `year` -> movie_year (string)
    - `rating` -> movie_rating (string) 

<details>
  <summary>
    Operations
  </summary>

  1. Unpickle the movies.pkl file which has a dictionary
  2. For the movie Shawshank Redemption, add a new key/value pair, key is `cast` and value is a set with two elements `Morgan Freeman` and `Tim Robbins`
  3. Change Forrest Gump year to 1994 and add actor Gary Sinise to the cast (make sure you don't erase any existing cast)
  4. Change all movie ratings (if available) to integers
  5. Ask the user to input a movie name, if found, ask the user to enter one cast and add the new cast to the movie, without erasing any previous cast
  6. Pickle the modified dictionary to movies2.pkl
</details>
  
</details>


<details>
  <summary>
    ✅ Part 4: 20 pts
  </summary>

- In `classes.py`, create three classes using the diagram provided in Part4 - Inheritance Diagram.pdf 

- In `functions.py` in part4() function body
  1.	Create new pilot object, and call it pilot1
  2.	Create four variables id = `3045`, name = `Harry Wilks`, cert_level = `AUD-L1`, salary = `75000` (Choose your data types)
  3.	Pass arguments id, name, salary, cert_level when you create the object pilot1
  4.	Change pilot1’s salary to 85000
  5.	Get pilot1’s cert_level and print it
  6.	Print all the details of pilot1  
  
  7.	Create new mechanic, call it mechanic1 using id = `3980`, name = `Ian West`, salary = `55000`, specialization = `aerofoil`
  8.	Change mechanic1’s specialization to `wing engineering`
  9.	Get mechanic1’s name and print it
  10.	Print all the details of mechanic1

</details>


<details>
  <summary>
    ✅ Part 5: 20 pts
  </summary>

- Connect to the database movies.db
- Write a CREATE statement that creates a table named movies with 4 columns (you may choose the names for the columns)
  - id is an integer and a primary key
  - name is string
  - year is integer
  - rating is float
- it should not raise any exception
- Open the file movies.txt and read it and insert that data into the table you created using INSERT statements
- Display all the movie data in a nice tabular format sorted by name
- Display the lowest rating
- Display the most recent movie(s) name and rating,sorted by rating in descending order
- Change the rating of the movie, the good, the bad and the ugly to 10
- Change the year of Forrest Gump to 1994
- Delete any movies who have rating lower than 9 and print how many were deleted
- Close the connection

</details>




