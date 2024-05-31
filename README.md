# DocFrontTS
Asegúrate de tener instalado Node.js (LTS). Si Node.js ya está instalado en tu sistema, verifica que la versión instalada sea LTS (y no la última versión).
Ejecuta el siguiente comando para instalar las dependencias locales listadas en package.json. Puedes usar npm O yarn según tu preferencia.
Se recomienda usar yarn para una mejor gestión de dependencias.

Bash
# Para npm
npm install --legacy-peer-deps

# Para yarn
yarn install

Ahora, estás listo para iniciar el servidor con la ayuda del siguiente comando. Abre http://localhost:3000/ para ver tu desarrollo .

Bash
# Para npm
npm run dev

# Para yarn
yarn dev
