# Test Task for company Sputnic

```Create a GET endpoint /api/prices that returns a JSON list of products (id, title, price).
When the `currency` parameter (RUB, USD, EUR) is provided, return the price converted (RUB = 1; USD = 90; EUR = 100) and formatted ($1.50, €2.00, 1 200 ₽).

Use Laravel 8+ and Laravel Resources. The response must be in JSON format.
```


# Run:
1. cd backend
2. make get-env
3. composer install --ignore-platform-reqs
4. sudo make up
5. sudo make first-run

# Swagger
        - ./vendor/bin/openapi app -o ./resources/swagger/v1/openapi.json
