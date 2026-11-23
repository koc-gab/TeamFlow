# TeamFlow

Reszponzív, magyar nyelvű csapatmunka- és projektkezelő alkalmazás Angular 20.3-mal, Tailwind CSS-sel és JSON Server backenddel.

## Indítás

Node.js 20.19+ (vagy 22.12+) és npm szükséges. A két szervert külön terminálban indítsd:

```powershell
# 1. terminál — backend
cd server
npm install
npm start
```

```powershell
# 2. terminál — frontend (a projekt gyökérmappájából)
npm install
npm start
```

- Frontend: <http://localhost:4200>
- JSON Server API: <http://localhost:3000>

A frontend a `http://localhost:3000` végpontot használja. Az adatbázis módosításai a `server/db.json` fájlba kerülnek. Az eredeti kezdőadatok visszaállítása előtt mentsd el az aktuális adatbázist, majd futtasd:

```powershell
cd server
npm run reset
```
