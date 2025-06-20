# Simple_Postman_API_test

# Trello API Test Collection (Postman)

This project contains automated API tests written in Postman for the [Trello REST API](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/). 
The tests cover key Trello operations such as creating boards, lists, and cards using public API endpoints.

## 📦 Files Included

- `trello-api-tests.postman_collection.json` – Postman collection with test requests
- `trello-environment.postman_environment.json` – Environment file with variables like `API_KEY`, `TOKEN`, `BOARD_ID`, etc.
- `.github/workflows/postman.yml` – GitHub Actions file for CI automation with Newman

## 📌 Prerequisites

- Node.js and npm installed
- Postman or Newman installed
- A Trello account and [API key/token](https://trello.com/app-key)
