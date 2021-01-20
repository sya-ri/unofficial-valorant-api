# unofficial-valorant-api
Unofficial Valorant API by scraping data from the Valorant Tracker Network page

# Authentication and Rate Limits
All rate limits are the same for every endpoint, so in general you have **200 Requests every 2 Minutes**. Your rate limit is based on your IP so you don't need an API Key for authentication.
If you exceed rate limit you will get following JSON with 429 Status Code:
```json
{
    "status": "429",
    "message": "You reached your Rate Limit, please try again later"
}
```
# Documentation
The documention for the API is available under https://docs.henrikdev.xyz/valorant-api.html

# Endpoints
- The base url is https://api.henrikdev.xyz
- Available endpoints are:
  - /valorant/v1/profile/{name}/{tag}
  - /valorant/v1/matches/{name}/{tag}
  - /valorant/v1/match/{match-id}
  - /valorant/v1/rank/{name}/{tag}
  - /valorant/v1/puuid/{name}/{tag} [BETA]
  
# Projects using this API
- https://github.com/Henrik-3/valorant-labs
- https://github.com/OblivionGhoul/KannaKamuiBot
- VALORANT DE Discord Rolesystem

# Usage
- ✅ 1000 Successful profile requests

Also would be happy if you give the project a star and give credit when you use it.
If you have any questions write on Discord: Henrik3#1451
