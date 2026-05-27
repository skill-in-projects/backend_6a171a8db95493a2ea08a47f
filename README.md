# FoodRoute - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_6a171a8db95493a2ea08a47f_user:STUwKefYZlf1ao6jTb%262wALPKegnd%21V9@ep-snowy-lab-aqwlkw3l.c-8.us-east-1.aws.neon.tech:5432/AppDB_6a171a8db95493a2ea08a47f?sslmode=require`

## Web API

**WebApi URL:** https://webapi6a171a8db95493a2ea08a47f-production.up.railway.app

**Swagger API Tester URL:** https://webapi6a171a8db95493a2ea08a47f-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
