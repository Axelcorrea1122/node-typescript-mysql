npm i typescript --save-dev
npm i @types/<nombre paquete> --save-dev  //para obtener el intellisense de los paquete en ts y se guarda como una dependencia de desarrollo
npm i copyfiles --save-dev //paquete para copiar archivos estaticos porque tsc no hace un build de esos archivos
//entonces se debe especificar el script "html": "copyfiles --up 1 src/public/*.html dist"
#--up <nivelesAOmitir> <pathDondeSeEncuentranArch> <destinoDelCopiado> #en este caso agarra todos los arch .html y copia solo la carpeta public/*.html en dist
//luego hacer otro script "build": "tsc && npm run build"
#para combinar los dos comando y ejecutarlos como npm run build en terminal 
npm install mysql
npm install mysqljs/mysql
npm install @types/mysql --save-dev


para mas info de typescript visitar https://www.typescriptlang.org/docs/