# Landing · Asistente de voz para clínicas dentales (AiEvolve)

Página de captación estática (un solo `index.html`, sin build).

- Calculadora de llamadas perdidas y formulario "Pedir demo gratuita".
- El formulario llama a la función `submit_landing_lead` del proyecto Supabase "Crm",
  que crea el contacto, una nota y una oportunidad en el pipeline Sales.
- La clave incluida en el HTML es la clave publicable de Supabase (pensada para ir en el navegador).

## Desplegar en Vercel

Importa este repositorio en Vercel con Framework Preset "Other", sin comando de build
y con el directorio raíz como salida.

## Medir el origen del tráfico

Añade `?utm_source=instagram` (o `llamada`, `email`...) al enlace: el origen queda guardado
en la nota del contacto.
