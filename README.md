# Weather API

A simple Flask-based Weather API that fetches weather data from a third-party API (Visual Crossing) and caches the results using Redis. This project demonstrates how to work with external APIs, caching mechanisms, environment variables, and rate-limiting.

Project from : https://roadmap.sh/projects/weather-api-wrapper-service
## Features

- Fetch weather data for a given city using the Visual Crossing Weather API.
- Cache the weather data in Redis for 12 hours to minimize API calls.
- Handle errors for invalid cities or unavailable APIs.
- Use environment variables to store sensitive data like API keys and Redis credentials.
- Implement rate limiting to prevent API abuse (e.g., max 10 requests per minute per IP).

---

## Prerequisites

Make sure you have the following installed:

- [Python](https://www.python.org/downloads/) (v3.8 or later)
- [Redis](https://redis.io/download) (local or hosted instance)
- Pip packages listed in the `requirements.txt` file:
  - Flask
  - Redis
  - requests
  - python-dotenv
  - flask-limiter

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/weather-api.git
   cd weather-api

