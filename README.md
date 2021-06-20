# TextAnalysisProgramaCandidatos2021

El siguiente `jupyter notebook` contiene el análisis de palabras más frecuentes del **Programa de Gobierno de Daniel Jadue.[1]**

# Procedimiento

- Para simplificar el trabajo de pasar el `.pdf` a texto plano se utilizó el sitio web [PDFToText](https://pdftotext.com/es/), en el cuál se convirtio el documento del programa en formato `.pdf` a un `.txt`. 
- Luego, manualmente se quitó un caracter especial dentro del `.txt` que en primera instancia complicó el trabajo al utilizar `python`. Simplemente se buscó y reemplazo por nada. De esta forma, el `.txt` quedó completamente limpio para empezar a procesarlo con `python`.
- Posteriormente se limpió el texto, y se _tokenizó_ cada linea del `.txt` , quitándose además caracteres especiales y _stopwords_[2].
- Finalmente se utilizó la librería `wordcloud` para realizar una nube con las palabras más frecuentes.

El detalle del procesamiento se encuentra detallado en el `jupyter notebook`.

# Pasos a seguir

Esto es en primera instancia un acercamiento al análisis del programa, se espera aplicar más técnicas de _text analysis_ e incluir el programa de los demás candidatos presidenciales.

# Referencias

[1] https://www.danieljaduepresidente.cl/wp-content/uploads/2021/06/Programa-DJ.pdf 

[2] https://raw.githubusercontent.com/Alir3z4/stop-words/master/spanish.txt
