# PicSocial API Documentation

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen?logo=github)](https://YOUR_USERNAME.github.io/picsocial-api-docs)
[![OpenAPI 3.0](https://img.shields.io/badge/OpenAPI-3.0-green.svg)](swagger.json)
[![Static Docs](https://img.shields.io/badge/Docs-Static%20Only-orange)](https://YOUR_USERNAME.github.io/picsocial-api-docs)

<img width="1841" height="899" alt="image" src="https://github.com/user-attachments/assets/9bad82df-842a-4db8-86c6-f02a52e4f66c" />


You can visit **[picsocial-api-docs](https://tanas2k4.github.io/picsocial-api-docs/)**

Static Swagger UI hosted on GitHub Pages  
See the [swagger-static-docs-template](https://github.com/Tanas2k4/swagger-static-docs-template) for step-by-step guidance.

Interactive API docs (view only – no "Try it out" execution).

## Update Docs

1. Replace `swagger.json` with the latest PicSocial API spec.
2. Commit & push:

```bash
git add swagger.json
git commit -m "Update API docs"
git push
```

→ GitHub Pages auto-deploys.
Live URL: https://YOUR_USERNAME.github.io/picsocial-api-docs

Get swagger.json (.NET 9)
Run the app:
```bash
dotnet tool install -g Swashbuckle.AspNetCore.Cli #If it is not already installed
dotnet run
```

Open in browser: http://localhost:<port>/swagger/v1/swagger.json
→ Save as swagger.json → replace in repo.
Local Preview
```bash
Bashnpx serve .
```
