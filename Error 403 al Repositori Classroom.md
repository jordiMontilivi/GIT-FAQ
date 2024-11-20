# Error al fer `pull` o `push` al repositori del classroom

Documentant una solució per a problemes d'accés al repositori GitHub d'un classroom, especialment quan s'utilitza un compte d'institut o es fa servir un Token d'Accés Personal (PAT). Aquí tens el contingut formatat correctament en Markdown:  

Quan intentes fer un `pull` o `push` al repositori del classroom, és possible que apareguin els següents errors després de seleccionar usuari o introduir un PAT en la finestra emergent (potser també en altres casos):

## Errors típics
1. **Error 403: Write access not granted**
remote: Write access to repository not granted. fatal: unable to access 'https://github.com/@username/repo.git/': The requested URL returned error: 403


2. **Error 403: Repository not found**
remote: Repository not found. fatal: unable to access 'https://github.com/@username/repo.git/': The requested URL returned error: 403


## Solució
Segueix aquests passos per solucionar el problema:

1. **Selecciona _Add a new account_**
- Quan aparegui la finestra emergent, selecciona l'opció `Add a new account`.  
![image6](https://github.com/user-attachments/assets/fb20ee00-feb2-404e-bf33-57b02619802f)

2. **Selecciona _Sign in with a code_**
- Tria l'opció `Sign in with a code`.    
![image1](https://github.com/user-attachments/assets/7d89a083-f606-4410-a9d9-57af096aebc1)

3. **Copia el codi de 8 dígits**
- Copia el codi de 8 dígits que es mostrarà i clica el link proporcionat.  
![image3](https://github.com/user-attachments/assets/7c386d55-c970-4df4-afff-16fb4cbcd153)

4. **Obre la pestanya al navegador**
- Quan s'obri el navegador:
  - Clica **Continue** al compte associat al correu de l'institut.
  - Si no apareix automàticament, clica **Use different account** i inicia sessió amb el compte correcte.  
![image4](https://github.com/user-attachments/assets/38cbc044-165e-46fb-89a1-28070fdba428)

5. **Enganxa el codi i continua**
- Enganxa el codi copiat prèviament i fes clic a **Continue**.  
![image7](https://github.com/user-attachments/assets/de04bf14-29f7-42ed-b7d7-347b88e4f9cb)

6. **Autoritza GitHub**
- Fes clic a **Authorize git-ecosystem**.  
![image8](https://github.com/user-attachments/assets/136a076c-aa4f-42dd-a6e5-b2c1b6650fc1)

7. **Confirma amb la teva contrasenya**
- Introdueix la teva contrasenya de GitHub i clica **Confirm**.  
![image5](https://github.com/user-attachments/assets/45264ac6-a487-41a0-b4e3-a1c20a287755)

## Resultat esperat
Si tot s'ha configurat correctament, hauries de veure un missatge similar al següent:  
![image9](https://github.com/user-attachments/assets/debe0ba9-5e2e-496c-9ada-386db93baa86)  

[Acció completada] Pull (o Push) realitzat correctament
Juntament amb el pull (o push) realitzat correctament a la consola de Git  
![image2](https://github.com/user-attachments/assets/a77feafd-86bd-456b-a634-59a76f281e20)  

Ara ja pots continuar treballant amb el repositori del classroom sense errors! 🎉

