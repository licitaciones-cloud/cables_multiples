# Cables Múltiples CMSA

Este repositorio contiene el sitio web oficial de Cables Múltiples CMSA.

## Sitio Web

El sitio web está desplegado usando GitHub Pages y está disponible en:
https://licitaciones-cloud.github.io/cables_multiples/

## Contenido

- **Logo**: Logo oficial de la empresa (Logo-CMSA (1).png)
- **Página Principal**: Sitio web simple que presenta la empresa

## Despliegue

El sitio se despliega automáticamente usando GitHub Actions cuando se hacen cambios en la rama `main`. 

### Configuración de Despliegue

1. **GitHub Pages**: Configurado para usar GitHub Actions como fuente
2. **Workflow**: `.github/workflows/deploy.yml` - se ejecuta automáticamente en cada push a main
3. **Dominio**: El sitio está disponible en `https://licitaciones-cloud.github.io/cables_multiples/`

### Pasos para Activar el Sitio Web (Primera vez)

1. **Mergear esta PR a la rama `main`** - Esto activará el workflow de GitHub Actions
2. **Configurar GitHub Pages** en la configuración del repositorio:
   - Ir a Settings > Pages
   - Seleccionar "GitHub Actions" como fuente de deployment
3. El sitio se desplegará automáticamente en `https://licitaciones-cloud.github.io/cables_multiples/`

### Pasos para Actualizar el Sitio (Futuras actualizaciones)

1. Hacer cambios en los archivos del sitio web
2. Hacer commit y push a la rama `main`
3. GitHub Actions automáticamente construirá y desplegará el sitio
4. El sitio estará disponible en pocos minutos

## Estructura del Proyecto

```
/
├── index.html              # Página principal del sitio
├── Logo-CMSA (1).png       # Logo de la empresa
├── .github/workflows/
│   └── deploy.yml          # Configuración de GitHub Actions
└── README.md               # Este archivo
```

## Tecnologías Utilizadas

- HTML5
- CSS3
- GitHub Pages
- GitHub Actions

## Contacto

Para preguntas sobre el sitio web o cambios, contactar al equipo de desarrollo.