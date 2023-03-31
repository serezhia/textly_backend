Start services
1. Create .env/ edit env in system 
    -   SECRET_KEY
    -   PROFILES_DATABASE_USERNAME
    -   PROFILES_DATABASE_PASSWORD

```
# bug(dart_frog)
For everyone service
1. dart_frog build
2. replace root dockerfile with /build/dockerfile

# For build services
docker compose build --no-cache --ssh default  

# For start 
docker compose up
```
