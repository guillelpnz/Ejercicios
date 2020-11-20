# Ejercicios del tema Serverless

## Ejercicio 1: Darse de alta en Vercel y Firebase, y descargarse los SDKs para poder trabajar con ellos localmente

### Configuración e instalación de Vercel

#### Configuración

Podemos registrarnos mediante GitHub:

![Acceso a github desde vercel](imagenes/vercel_access_github.png)

Posteriormente pide que importemos algún proyecto(repositorio) de GitHub a Vercel

![Import GitHub repository to Vercel](imagenes/import_git_repository.png)

![Congratulations vercel](imagenes/vercel_access_github.png)

#### Instalación SDK

Descargamos el VercelCLI de la forma en que se nos indica en la página oficial del software:

![install vercel cli](imagenes/instalacion_sdk_vercel.png)

### Instalación de Firebase

Ejecutamos el siguiente comando:

![Comando ejecución Firebase](imagenes/sdk_firebase.png)

En la consola ejecutamos firebase login, y conectamos una cuenta de Google
para poder usar el servicio:

![Exito login firebase](imagenes/logged_google.png)

## Ejercicio 2: Tomar alguna de las funciones de prueba de Vercel, y hacer despliegues de prueba con el mismo

Lo que hice fue crearme un repo para esta api de prueba, llamado
[tema-serverless-iv](https://github.com/guillelpnz/tema-serverless-iv)

Posteriormente, seguí las instrucciones para la creación de un fichero de
prueba que encontré: [Ejemplo Go](https://vercel.com/docs/serverless-functions/supported-languages#go)

Así, creé la carpeta /api dentro de mi proyecto de prueba, y dentro copié el
fichero date.go del anterior link.

Para ver el funcionamiento basta con visitar [esta página](https://tema-serverless-iv.vercel.app/api/date)

Y como vemos hace algo tan simple como imprimir la fecha actual.
