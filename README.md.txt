# ProofChainMarket

ProofChainMarket es una plataforma para compartir y gestionar ideas y proyectos en un entorno colaborativo. Este repositorio contiene el código fuente del cliente y servidor de la aplicación.

## Instalación

Sigue estos pasos para instalar y ejecutar el proyecto localmente:

1. Clona el repositorio:
   git clone https://github.com/tu-usuario/ProofChainMarket.git
   cd ProofChainMarket

2. Instala las dependencias:
   npm install

3. Configura las variables de entorno necesarias en los archivos de configuración.

4. Inicia el servidor de desarrollo:
   npm run dev

5. Abre la aplicación en tu navegador en http://localhost:3000.

## Estructura del Código

El proyecto está organizado de la siguiente manera:

ProofChainMarket/
├── client/                # Código del cliente (frontend)
│   ├── src/
│   │   ├── components/    # Componentes reutilizables de React
│   │   ├── pages/         # Páginas principales de la aplicación
│   │   ├── hooks/         # Hooks personalizados
│   │   ├── styles/        # Archivos de estilos
│   │   └── utils/         # Utilidades y funciones auxiliares
│   └── index.html         # Archivo HTML principal
├── server/                # Código del servidor (backend)
│   ├── auth.ts            # Lógica de autenticación
│   ├── db.ts              # Configuración de la base de datos
│   ├── routes.ts          # Definición de rutas del servidor
│   └── storage.ts         # Gestión de almacenamiento
├── scripts/               # Scripts auxiliares
├── .config/               # Archivos de configuración
└── package.json           # Dependencias y scripts del proyecto

## Sponsors

El proyecto ProofChainMarket incluye soporte para diferentes sponsors. A continuación, se muestra cómo se utilizan en el código:

### Sponsors en el Código

#### Camp
{formData.hackathonTrack === 'camp' && (
  <div className="bg-blue-50 p-4 rounded-md">
    <h3 className="font-semibold text-blue-700 mb-2">Requisitos de Camp:</h3>
    <ul className="list-disc list-inside text-blue-700 text-sm">
      <li>Debe demostrar aplicaciones creativas de la visión de IP y AI de Camp</li>
      <li>Debe estar desplegado en BaseCAMP chain</li>
      <li>Debe enfocarse en la experiencia de usuario y potencial de adopción</li>
      <li>Debe alinearse con la misión de Camp de soberanía del creador y AI transparente</li>
    </ul>
  </div>
)}

#### Mantle
{formData.hackathonTrack === 'mantle' && (
  <div className="bg-green-50 p-4 rounded-md">
    <h3 className="font-semibold text-green-700 mb-2">Requisitos de Mantle:</h3>
    <ul className="list-disc list-inside text-green-700 text-sm">
      <li>Debe ser una aplicación DeFi (pagos, finanzas, stablecoins, etc.)</li>
      <li>OBLIGATORIO: Despliegue e integración en Mantle Sepolia Testnet o Mantle Mainnet</li>
    </ul>
  </div>
)}

#### EigenLayer
{formData.hackathonTrack === 'eigenlayer' && (
  <div className="bg-purple-50 p-4 rounded-md">
    <h3 className="font-semibold text-purple-700 mb-2">Requisitos de EigenLayer:</h3>
    <ul className="list-disc list-inside text-purple-700 text-sm">
      <li>Debe enfocarse en utilidad en el mundo real</li>
      <li>El código del proyecto debe ser de código abierto</li>
      <li>Debe incluir cómo se integra EigenLayer en la presentación</li>
    </ul>
  </div>
)}

## Contribuciones

Si deseas contribuir al proyecto, por favor abre un issue o envía un pull request. ¡Toda ayuda es bienvenida!

## Licencia

Este proyecto está bajo la licencia MIT.