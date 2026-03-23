# Impurezas Organicas CRM

Microfrontend Vite/React para el formulario de Impurezas Organicas consumido por `iframe` desde `crm-geofal`.

## Dominio productivo

- `https://imp.organicas.geofal.com.pe`

## Variables

- `VITE_API_URL=https://api.geofal.com.pe`
- `VITE_CRM_LOGIN_URL=https://crm.geofal.com.pe/login`
- `VITE_MODULE_SLUG=imp-organicas`

## Desarrollo

```bash
npm install
npm run dev
```

## Deploy Coolify

El `Dockerfile` ya compila este repo en la raiz `/` con `VITE_MODULE_SLUG=imp-organicas`, listo para `https://imp.organicas.geofal.com.pe`.
