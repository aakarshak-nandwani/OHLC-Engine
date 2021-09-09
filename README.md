
# OHLC Engine

This project was made using:
- Python 
- Streamlit 





## Acknowledgements

- [JSON to CSV file conversion](https://www.geeksforgeeks.org/convert-json-to-csv-in-python/)
- [OHCL Charts using plotly](https://plotly.com/python/ohlc-charts/)
- [How to use IEX cloud](https://www.youtube.com/watch?v=_INKBveSVec)
- [How to create a Streamlit Dashboard](https://www.youtube.com/watch?v=tx6bT2Sh9R8)

  
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

  
## Contributors

- Aakarshak Nandwani - aakarshak8@gmail.com
- Dhruva Patel - dhruvapatel.2501@gmail.com
- Dhvanil Patel - dhvanilpatel23@gmail.com
- Vaibhav Patel - vaibhavpatel1855@gmail.com
- Lakshita Jain - lakshitajain0809@gmail.com
- Khooshali Kapopara - khooshali.kapopara@gmail.com

  
## Deployment

Pre-requisites to deploy this project 

```bash
pip install streamlit
pip install pandas 
pip install plotly 
```
## Setup & Run 

- Install the required packages and download the complete folder. 
- Run app.py file using the following command in command line within the folder in which you cloned the repository.

```bash
streamlit run app.py 
