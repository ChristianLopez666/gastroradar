# GastroRadar

**¿Qué se te antoja hoy?** GastroRadar es un directorio gastronómico de México: ayuda a encontrar restaurantes, fondas y antojitos cerca de ti, y a los negocios de comida a darse a conocer.

🌐 https://tugastroradar.com

## Qué hace

- **Para quien busca dónde comer:** búsqueda por tipo de comida, municipio y cercanía, horarios, formas de pago y empleos en restaurantes.
- **Para negocios de comida:** portal propio para registrarse, completar su ficha (fotos, menú, horarios) y elegir un plan.
- **Para la operación:** panel de administración para revisar negocios, planes y solicitudes.

GastroRadar es un directorio. No es un servicio de reparto ni cobra comisión por pedidos.

## Cómo está construido

Aplicación web propia que corre completa en la plataforma de Cloudflare:

- Cloudflare Workers (aplicación y API)
- Cloudflare D1 (base de datos) y R2 (imágenes)
- Cloudflare DNS y Email Routing

Los datos base de los establecimientos provienen del Directorio Estadístico Nacional de Unidades Económicas (DENUE) de INEGI; los datos operativos los confirma cada negocio.

## Estado

Proyecto en desarrollo activo desde octubre de 2026, con presencia inicial en Sinaloa y alcance nacional en preparación. El código fuente es privado.

## Contacto

Christian López Álvarez, Los Mochis, Sinaloa, México · contacto@tugastroradar.com
