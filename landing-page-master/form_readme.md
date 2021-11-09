## Formulario google forms para landing page
### Pasos.
 a. 
 1. crear formulario en blanco en docs.google.com/forms/u/0/ 
 2. Marcar tipo de respuesta corta, y requerido.
 3. Click en icono engranaje(settings) y en  pestaña(general) seleccionar "recoger dirección de correo", en pestaña (presentación) escribo  mensaje  de confirmación que recibirá el usuario cuando haya introducido sus datos. 4. opcional personalizar página de google con imágen para cabezera y color para el body.
   
 b. Una vez creado el formulario 
 1. inpeccionar su código . 
 2. busco la parte de input donde llenó el nombre y busco name="entry.3642644326(número de 9 cifras aprox."  copiarlo y pegarlo en "NAME_INPUT": "entry.XXXXXXXXX" del config.json 
 3. luego a la parte de form action= "la url del formulario" copiarlo y pegarlo en el "FORM_RESPONSE_URL": del config.json 
 
 fuente:https://youtu.be/UNWnb73etac?t=431  



 ## Sibirla gratis a Netlify