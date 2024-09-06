# Guía para usar Phomber

Phomber es una herramienta para enumerar números de teléfono a partir de diversas fuentes en línea. A continuación se detalla cómo instalar y usar Phomber en Kali Linux.

## Instalación

1. **Clona el repositorio de Phomber**:
    ```bash
    git clone https://github.com/Phomber/Phomber.git
    ```

2. **Navega al directorio de Phomber**:
    ```bash
    cd Phomber
    ```

3. **Instala las dependencias necesarias**:
    ```bash
    pip install -r requirements.txt
    ```

## Uso Básico

1. **Ejecuta Phomber con el número de teléfono objetivo**:
    ```bash
    python phomber.py -n <numero_telefono>
    ```

   Reemplaza `<numero_telefono>` con el número de teléfono que deseas investigar.

2. **Opciones disponibles**:

    - `-n <numero_telefono>`: Número de teléfono objetivo.
    - `-h`: Muestra la ayuda y opciones disponibles.

## Ejemplo

Para enumerar información sobre el número de teléfono `+1234567890`, usa el siguiente comando:

```bash
python phomber.py -n +1234567890
```


