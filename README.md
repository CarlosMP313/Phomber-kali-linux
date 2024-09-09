# Guía Rápida para Usar PH0MBER

PH0MBER es un marco de trabajo OSINT (Open Source Intelligence) diseñado para cubrir todas tus necesidades de recolección y reconocimiento de información. Esta herramienta te permite obtener datos como números de teléfono, direcciones IP, información de dominios, entre otros, desde diversas fuentes públicas.

## Instalación

### Clonar el Repositorio

Para instalar PH0MBER, primero clona el repositorio desde GitHub:

```bash
git clone https://github.com/s41r4j/phomber.git
```

### Navegar al Directorio

Accede al directorio clonado:

```bash
cd phomber
```

### Instalar Dependencias

Accede al directorio clonado:

```bash
pip3 install -r pyproject.toml
```

Alternativamente, si prefieres instalar PH0MBER directamente desde PyPI:
```bash
pip install phomber
```

**Usando Docker**
También puedes ejecutar PH0MBER con Docker:
 1. Descarga la imagen más reciente:
```bash
docker pull sinawic/phomber:latest
```
 2.Corre PH0MBER en un contenedor:
```bash
docker run --rm -it sinawic/phomber:latest
```

## Actualización

Para actualizar PH0MBER, si estás en el directorio del proyecto, simplemente ejecuta:
```bash
git pull
```

Para actualizar desde PyPI:
```bash
pip install --upgrade phomber
```

Y para actualizar la imagen Docker:
```bash
docker pull sinawic/phomber:latest
```

## Uso Básico

PH0MBER puede ser ejecutado de varias maneras:

### Ejecución desde el Código Fuente
Asumiendo que estás en el directorio de PH0MBER:
```bash
python3 phomber.py
```

### Ejecución desde la Instalación con Pip
Si instalaste PH0MBER vía pip:
```bash
phomber
```
### Ejecución con Docker
Para correr PH0MBER con Docker:
```bash
docker run --rm -it sinawic/phomber:latest
```
## Comandos Principales

PH0MBER ofrece una variedad de comandos para recolección de datos. Aquí algunos de los más importantes:

- **help**: Muestra el menú de ayuda.
- **exit/quit**: Salir del framework.
- **dork**: Muestra un query dork de Google aleatorio.
- **check**: Verifica la conexión a Internet.
- **number**: Realiza una búsqueda inversa de números de teléfono.
- **ip**: Realiza una búsqueda inversa de direcciones IP.
- **whois**: Realiza una búsqueda inversa de información WHOIS.
- **dns**: Realiza una búsqueda inversa o normal de DNS.
- **username**: Busca un nombre de usuario en múltiples sitios web y plataformas sociales.


## Ejemplo de Uso
Para realizar una búsqueda inversa de un número de teléfono específico, usa:
Para correr PH0MBER con Docker:
```bash
phomber number -n +1234567890
```
Reemplaza `+1234567890` con el número que deseas investigar.

## Consejos y Advertencias

- **Uso Responsable**: Esta herramienta debe usarse de manera ética y legal. Asegúrate de cumplir con todas las leyes aplicables y respeta la privacidad de los individuos.
- **Acceso a Internet**: Algunos comandos requieren una conexión a Internet para funcionar correctamente.
- **Ayuda Adicional**: Usa `help <command>` para obtener más información sobre un comando específico.

**Aviso de Responsabilidad:** El uso de esta herramienta debe ser ético y legal. No me hago responsable de la información obtenida ni del uso que se haga de ella. Asegúrate de cumplir con todas las leyes y regulaciones aplicables.














