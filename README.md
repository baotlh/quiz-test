# Mongodb-quiz-test

Structure of 'restaurants' collection:
```
{
  "address": {
     "building": "1007",
     "coord": [ -73.856077, 40.848447 ],
     "street": "Morris Park Ave",
     "zipcode": "10462"
  },
  "borough": "Bronx",
  "cuisine": "Bakery",
  "grades": [
     { "date": { "$date": 1393804800000 }, "grade": "A", "score": 2 },
     { "date": { "$date": 1378857600000 }, "grade": "A", "score": 6 },
     { "date": { "$date": 1358985600000 }, "grade": "A", "score": 10 },
     { "date": { "$date": 1322006400000 }, "grade": "A", "score": 9 },
     { "date": { "$date": 1299715200000 }, "grade": "B", "score": 14 }
  ],
  "name": "Morris Park Bake Shop",
  "restaurant_id": "30075445"
}
```
You may download the compressed file and uncompress it to find the collection used in our exercises. The collection comprises of 3772 documents.

### Exercises
1. Write a MongoDB query to display all the restaurant which is in the borough Bronx.
2. Write a MongoDB query to display the next 5 restaurants after skipping first 5 which are in the borough Bronx.
3. Write a MongoDB query to display the fields restaurant_id, name, borough and cuisine, but exclude the field _id for all the documents in the collection restaurant.
4. Write a MongoDB query to arrange the name of the restaurants in ascending order along with all the columns.
5. Write a MongoDB query to find the restaurants who achieved a score more than 90.
6. Write a MongoDB query to find the restaurants that do not prepare any cuisine of 'American' and their grade score more than 70 and latitude less than -65.754168.
7. Write a MongoDB query to arrange the name of the restaurants in ascending order along with all the columns.
8. Write a MongoDB query to find the average score for each restaurant.
9. Write a MongoDB query to find the name, address, and grades of the restaurants that have at least one 'A' grade, no 'B' grades, and no 'C' grades.
10. Write a MongoDB query to find the restaurants that have all grades with a score greater than 5 then add field to indicate "Our selected restaurant" value to them.
11. Write a MongoDB query to remove restaurants with average score less than 10. 





