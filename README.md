# API-Directions-Google-
Aplicación desarrollada en Python que emplea la API de Google Maps para ofrecer direcciones y rutas óptimas. Este proyecto es ideal para quienes estén interesados en aplicaciones de mapeo y geolocalización.

## Tabla de Contenidos
- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Imágenes](#imágenes)

## Características
- Obtención de direcciones y rutas óptimas utilizando la API de Google Maps.
- Visualización de rutas en un mapa interactivo.
- Soporte para múltiples destinos.
- Diferentes modos de transporte: automóvil, bicicleta, a pie.

## Requisitos
- Python 3.9 o superior
- Cuenta de Google Cloud con una API Key de Google Maps
- Docker (opcional, para despliegue en contenedores)
- Kubernetes y Minikube (opcional, para despliegue en clúster)

## Instalación
1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu-usuario/API-Directions-Google.git
    cd API-Directions-Google
    ```

2. Crea un entorno virtual y activa el entorno:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
    ```

3. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

4. Configura tu API Key de Google Maps:
    - Renombra el archivo `.env.example` a `.env` y agrega tu API Key:
    ```env
    GOOGLE_MAPS_API_KEY=tu-api-key
    ```

5. Ejecuta la aplicación:
    ```bash
    python app.py
    ```

## Uso
1. Abre tu navegador y ve a `http://localhost:5000`.
2. Ingresa las direcciones de origen y destino.
3. Selecciona el modo de transporte.
4. Haz clic en "Obtener ruta" para ver la ruta óptima en el mapa.

## Imágenes

### Captura de pantalla de la interfaz
![Interfaz de usuario](https://ibb.co/KzR2sj7)
![Interfaz de usuario](https://ibb.co/JdjkkSN)

