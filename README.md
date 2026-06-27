# Multilingual Dental Clinic Website

Sitio web de una clinica dental construido con Astro y componentes reutilizables.
El contenido esta disponible en espanol, ingles y catalan e incluye paginas de
tratamientos, reserva de citas y documentos legales.

## Caracteristicas

- Rutas completas en `es`, `en` y `ca`.
- Paginas individuales para endodoncia, implantes, ortodoncia,
  odontopediatria, estetica y rehabilitacion oral.
- Formulario de citas y componentes compartidos para cabecera, hero, servicios
  y pie de pagina.
- Generacion estatica con Astro para reducir JavaScript y mejorar tiempos de
  carga.
- Integracion de componentes Vue cuando la interfaz necesita interactividad.
- Configuracion de despliegue para Vercel.

## Estructura

```text
src/
  components/       componentes compartidos
  layouts/          layout base y metadatos
  pages/
    es/             contenido en espanol
    en/             contenido en ingles
    ca/             contenido en catalan
```

## Stack

- Astro 7
- Vue 3
- CSS
- Vercel

## Desarrollo local

Requiere Node.js 22.12+.

```bash
npm ci
npm run dev
```

Verificar el build de produccion:

```bash
npm run build
npm run preview
```

## Consideraciones de produccion

El formulario debe conectarse a un servicio de correo o CRM con validacion del
lado servidor, proteccion anti-spam y tratamiento de datos acorde con la
regulacion aplicable. El repositorio no contiene credenciales ni datos de
pacientes.
