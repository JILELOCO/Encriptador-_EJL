# Encriptador-_EJL
Encriptador_de_curso_de_Alura

-----
------
Espero me comprendan y si hay algo mal me puedan apoya ya que es de mi trabajo de aprendiaje de programación del programa ONE en colaboración con Alura.
------
------

se utilixo lo siguiente para la encriptación.

let texto_bytes = new TextEncoder().encode(texto)
let encriptado = new Uint8Array(texto_bytes).reduce((data, byte) => data + String.fromCharCode(byte), '')
document.getElementById("escritura_resultado").innerHTML = btoa(encriptado)

------
------

Las tecnologias utilizadas fueron las siguientes:
<img src="https://img.icons8.com/color/344/html-5--v1.png" alt="html" width="50"/>
<img src="https://img.icons8.com/color/344/css3.png" alt="css" width="50"/>
<img src="https://img.icons8.com/color/344/javascript--v1.png" alt="JavaScript" width="50"/>
