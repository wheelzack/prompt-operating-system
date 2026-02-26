# API Endpoints

## Authentication
POST /api/auth/signup  
POST /api/auth/login  

## Modules
GET /api/modules  
GET /api/modules/{module_id}

## Run Prompt
POST /api/run

Request:
{
  "module_id": "RESEARCH_001",
  "inputs": {}
}

## Credits
GET /api/credits  
POST /api/credits/consume
