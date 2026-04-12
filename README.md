# SAHIBA Chain Store CRM

Wholesale garment sales CRM for managing chain store accounts (Soriana, Comercial Mexicana, etc.) in Mexico.

## Stack
- Single-file React/Babel app
- Live SQL Server data via ngrok tunnel + Netlify serverless proxy
- Google Drive product images via Apps Script
- Netlify auto-deploy from GitHub

## Structure
```
chain-crm/
  public/
    index.html          # Main app
  netlify/
    functions/
      query.js          # SQL API proxy function
netlify.toml            # Netlify config
```

## Netlify Settings
- **Base directory:** `chain-crm`
- **Publish directory:** `chain-crm/public`
- **Functions directory:** `chain-crm/netlify/functions`
- **Environment variable:** `SAHIBA_API_TOKEN`

## Users
| Name | Role | PIN |
|------|------|-----|
| Jessie | Admin | 1234 |
| Ingrid | Salesperson | 5678 |
| Cynthia | Salesperson | 9012 |
| Sonia | Salesperson | 3456 |
| Almacen | Warehouse | 7890 |
