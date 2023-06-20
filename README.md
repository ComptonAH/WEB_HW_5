// Task 3
{
    "Film name": ["The Green Mile", "The Shawshank Redemption", "Interstellar", "Shaun of the Dead", "Shrek"],
    "Production year" : [1999,1994,2014, 2004,2001],
    "Country" : ["USA", "USA", "USA,Canada,UK", "UK, France, USA", "USA, Canada, Sweden"],
    "Genre" : ["Drama", "Drama", "Fantasy, Drama", "Horror, Comedy", "Cartoon, Fantasy, Comedy, Advanture"],
    "Budget" : [60000000, 25000000, 165000000,5000000,60000000],
    "World's premier" : ["6 december, 1999", "10 september, 1994", "26 october 2014", "29 march, 2004", "22 april, 2001"]
}
 
// Task 4

{
	"info": {
		"_postman_id": "0c94660d-4f43-485c-8e06-2b14b4223511",
		"name": "Final Task",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "28090660"
	},
	"item": [
		{
			"name": "New Request",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"id\": 69,\r\n    \"email\": \"claire@mawson.com\",\r\n    \"first_name\": \"Leshiy\",\r\n    \"last_name\": \"Intimidating\",\r\n    \"avatar\": \"https://reqres.in/img/faces/67-image-76.jpg\"\r\n}\r\n",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/users",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users"
					]
				}
			},
			"response": []
		},
		{
			"name": "New Request",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"id\": 69,\r\n    \"email\": \"claire@mawson.com\",\r\n    \"first_name\": \"Leshiy\",\r\n    \"last_name\": \"Intimidating\",\r\n    \"avatar\": \"https://reqres.in/img/faces/67-image-76.jpg\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/users/69",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"69"
					]
				}
			},
			"response": []
		}
	]
}
