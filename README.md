# ONDAS - Buscador de Noticias Musicales (1925-1935)

![Project LexiMus](https://img.shields.io/badge/Proyecto-LexiMus-orange)
![Universidad de Salamanca](https://img.shields.io/badge/Universidad-Salamanca-blue)
![Estado](https://img.shields.io/badge/Estado-Activo-green)

## 📖 Descripción

Buscador interactivo de noticias musicales de la revista **ONDAS** (1925-1935), la primera revista española dedicada a la radiodifusión y su programación musical. Este proyecto forma parte de **LexiMus: Léxico y ontología de la música en español** (PID2022-139589NB-C33).

**🔗 Ver el buscador:** [https://leximususal.github.io/ONDAS/](https://leximususal.github.io/ONDAS/)

## 🎯 Características

Las trasncripciones se han realizado de forma automática con Claude, con revisión y supervisión humana. En una primera fase se revisaron los primeros números procesados, para asegurar la validación y calibrar el prompt de uso. Posteriormente se fueron revisando de forma aleatoria los números, para asegurar un porcentaje válido de transcripción. Se estima que el error es menor al 5%, pero al tratarse de transcripciones realizadas por IA aconsejamos cotejar las fuentes con las originales conservadas en la BNE.
La ventaja de nuestro repositorio es que no tiene errores típicos de OCR, propios de la prensa histórica, y por ello la cantidad de datos que podemos recuperar es mayor (aunque haya que ir posteriormente a las Hemerotecas digitales para verificar que todo ha sido bien procesado).
Estos datos se han usado dentro del proyecto para análisis computacionales (distant reading), pero dada la gran calidad de las transcripciones se ha decidido compartir estos números para poder realizar también una lectura atenta y cercana.

## 🚀 Uso

1. Abre [index.html](https://leximususal.github.io/ONDAS/) en tu navegador
2. Usa la barra de búsqueda para encontrar términos específicos
3. Filtra por año (1925-1935) usando los botones laterales
4. Filtra por tipo de contenido (ópera, concierto, radio, etc.)
5. Ordena los resultados por fecha, tipo o relevancia
6. Navega entre páginas usando la paginación inferior

## 📁 Estructura del Proyecto

```
ONDAS/
├── index.html           # Interfaz web del buscador
├── ondas_data.json      # Base de datos con 23,689 artículos
└── README.md            # Este archivo
```

## 🔍 Sobre ONDAS

**ONDAS** fue una revista semanal española publicada entre 1925 y 1935, pionera en la cobertura de la radiodifusión y la programación musical radiofónica en España. La revista incluía:

- Programaciones detalladas de **Unión Radio** (EAJ-7) y otras emisoras
- Críticas de estrenos operísticos y conciertos
- Información sobre intérpretes, compositores y directores
- Reseñas de música clásica, ópera y zarzuela
- Noticias sobre la tecnología radiofónica emergente

## 🎓 Contexto Académico

Este recurso es parte del proyecto **LexiMus: Léxico y ontología de la música en español** (PID2022-139589NB-C33), desarrollado por:

- **Universidad de Salamanca**
- **Instituto Complutense de Ciencias Musicales**
- **Universidad de La Rioja**

## 📝 Metodología

1. **Digitalización**: Transcripción de 472 números de ONDAS (1925-1935)
2. **Procesamiento**: Análisis con Python y NLP, Claude
4. **Extracción**: Identificación de secciones y artículos
5. **Visualización**: Interfaz web interactiva

## 🛠️ Tecnologías

- **HTML5/CSS3**: Interfaz responsive
- **JavaScript ES6**: Lógica de búsqueda y filtrado
- **JSON**: Almacenamiento de datos
- **Python 3**: Procesamiento del corpus

## 📧 Contacto

Proyecto **LexiMus** - Universidad de Salamanca
[https://leximus.usal.es/](https://leximus.usal.es/)

## 📜 Licencia

Este proyecto se distribuye bajo licencia académica con fines de investigación. Pero no olvides citar esta página correctamente.

## 🙏 Reconocimientos

- Hemeroteca Digital de la Biblioteca Nacional de España
- Unión Radio Madrid (EAJ-7)
- Revista ONDAS (1925-1935)

---

**Generado el**: Enero 2026
**Corpus**: 1.742.470 palabras. | 472 números procesados |
