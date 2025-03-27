# ECSE3038_tutorial3
GET /api/fruits → Retrieve all available fruits.

GET /api/fruits/{id} → Retrieve details of a specific fruit.

POST /api/fruits → Add a new fruit (server sets creation_date, defaults available to true).

PATCH /api/fruits/{id} → Update fruit availability, price, or quantity.

DELETE /api/fruits/{id} → Soft delete a fruit (sets available to false instead of removing it).