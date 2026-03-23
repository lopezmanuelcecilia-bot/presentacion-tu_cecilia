# Bitácora de arranque - Ruta de arranque Linux + Git — Cecilia Lopez

**Fecha:** 23/03/2026  
**Duración estimada:** 1 hora 

## Pasos ejecutados

1. pwd → mostré la ruta actual de trabajo en la terminal  
2. cd Desktop → me moví al escritorio, cambié la ubicación de la terminal 
al escritorio para trabajar en una carpeta  
3. git clone → descargué el repositorio desde GitHub, creando una copia 
local del proyecto  
4. cd presentacion-tu_cecilia → entré al proyecto  
5. git checkout -b semana2-arranque → creé una nueva rama, sin modificar 
la rama principal del repositorio  
6. nano README.md → edité el archivo README agregando usuario y color 
favorito  
7. git status → verifiqué los cambios en el repositorio, confirmando que 
los archivos habían sido modificados  
8. git add . → agregué los archivos  
9. git commit → guardé los cambios con un mensaje  
10. git push → subí los cambios al repositorio remoto, las credenciales 
ya estaban guardadas en el sistema por lo que no fue necesario ingresar el 
token nuevamente  
11. git log --oneline → me mostró los cambios realizados en mi rama  
12. nano bitacora.md → añadí las modificaciones finales a mi bitácora  
13. git push origin semana2-arranque → subí todas mis actualizaciones  

## Comandos destacados

| Comando | Qué hizo |
|--------|--------|
| git status | Mostró el estado del repositorio y los cambios realizados |
| git checkout -b semana2-arranque | Creó y cambió a una nueva rama |
| git clone | Descargó el repositorio desde GitHub |

## Problemas encontrados

- Problema: al momento de hacer git push esperaba que el sistema 
solicitara autenticación mediante usuario y contraseña o token, lo cual no 
ocurrió  
- Cómo lo resolví: investigué que las credenciales ya estaban almacenadas 
en el sistema mediante el llavero de macOS, por lo que no fue necesario 
ingresar el token nuevamente  
- Nota: tengo reservado el token en caso de que sea necesario próximamente  
- Aprendizaje: me permitió entender cómo Git gestiona la autenticación de 
manera segura en sistemas ya configurados previamente  

## Resultado de git log --oneline

74ea41f docs: agrega README y bitacora  
b4154c9 Añadiendo contenido en README  
577b02d Añadiendo README  

## Higiene digital aplicada

- Se generó un Personal Access Token en GitHub para mejorar la seguridad 
en la autenticación, aunque no fue necesario utilizarlo en este caso 
debido a que las credenciales ya estaban almacenadas en el sistema









