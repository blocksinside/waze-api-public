## API Accessible with the following link
https://rapidapi.com/blocksinside/api/waze-api/
## API Reference

#### Get alerts

```http
GET /alerts
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `bottom-left` | `string` | Coordinates Bottom Left (you can get them from google maps) |
| `top-right` | `string` | Coordinates Top Right (you can get them from google maps) |
| `limit` | `string` | Amount of entries you want the api to return |

#### Instructions for Providing Coordinates in a Rectangular Shape


To define a geographical area for data retrieval, you need to specify coordinates in a rectangle shape. Follow these steps:

1. Open Google Maps and navigate to the desired location.

2. On the left side of the map, click to select the bottom-left corner of the rectangle you want to define.

3. Copy the coordinates provided by Google Maps.

4. Paste the copied coordinates into the `bottom-left` parameter when making the API request.

5. Move to the top-right side of the map.

6. Click to select the top-right corner of the rectangle.

7. Copy the coordinates provided for the top-right corner.

8. Paste the copied coordinates into the `top-right` parameter when making the API request.

By following these steps, you will effectively create a rectangle within which the scraper will retrieve all relevant data.



