# Weather API Service

## How to Run the Project

1. **.env file:**
 
   - create .env file in Weather-API-Service directory.
   - add credentials:
```dotenv
AWS_ACCESS_KEY_ID=...
AWS_SECRET_ACCESS_KEY=...
AWS_REGION=...
S3_BUCKET_NAME=...
DYNAMODB_TABLE_NAME=...
API_KEY=...  # OpenWeatherMap
CACHE_EXPIRATION_MINUTES=5
```

2. **Build the Docker image:**

   ```bash
   docker build -t weather-api-service .

   
3. **Run the Docker container:**

    ```bash
   docker run -p 8000:8000 weather-api-service

## 📝 License
MIT © 2025 Tudor Frumuzachi