# Text Analysis Programa Candidatos Presidenciales 2021

El siguiente `jupyter notebook` contiene el análisis de palabras más frecuentes de los candidatos a las *Presidenciales 2021 en Chile: Gabriel Boric, Sebastián Sichel, Jose Antonio Kast, Yasna Provoste*. ^[Falta aún: Eduardo Artés, Marco Enrique Ominami, Franco Parisi]


# Procedimiento

- Para simplificar el trabajo de pasar el `.pdf` a texto plano se utilizó el sitio web [PDFToText](https://pdftotext.com/es/), en el cuál se convirtio el documento del programa en formato `.pdf` a un `.txt`. 
- Posteriormente se limpió el texto, y se _tokenizó_ cada linea del `.txt` , quitándose además caracteres especiales y _stopwords_[2].
- Finalmente se utilizó la librería `wordcloud` para realizar una nube con las palabras más frecuentes.

El detalle del procesamiento se encuentra detallado en el `jupyter notebook`.

# Resultados

##[Antiguo] Palabras más frecuentes programa de gobierno Daniel Jadue
<img src="https://pbs.twimg.com/media/E4WzDQaWYAA4Xsd?format=png&name=900x900" alt="Palabras más frecuentes"/>

## Palabras más frecuentes programa de gobierno de Gabriel Boric[3]
<img src='https://imgur.com/fUfsiGd' alt='Palabras más frecuentes'/>

## Palabras más frecuentes programa de gobierno de Sebastián Sichel[4]
<img src='https://imgur.com/FqYpqQ4' alt='Palabras más frecuentes'/>

## Palabras más frecuentes programa de gobierno de Jose Antonio Kast[5]
<img src='https://imgur.com/3rWQRRK' alt='Palabras más frecuentes'/>

## Palabras más frecuentes programa de gobierno de Yasna Provoste[6]
<img src='https://imgur.com/3rWQRRK' alt='Palabras más frecuentes'/>

# Pasos a seguir

Esto es en primera instancia un acercamiento al análisis del programa de los candidatos presidenciales en base a palabras más frecuentes. Se espera incluír más análisis léxicos prontamente.

# Referencias

[1] https://www.danieljaduepresidente.cl/wp-content/uploads/2021/06/Programa-DJ.pdf 

[2] https://raw.githubusercontent.com/Alir3z4/stop-words/master/spanish.txt

[3] https://www.boricpresidente.cl/wp-content/uploads/2021/05/manifiesto_gabriel_boric.pdf

[4] https://www.servel.cl/wp-content/uploads/2021/06/3_PROGRAMA_SEBASTIAN_SICHEL.pdf

[5] https://www.servel.cl/wp-content/uploads/2017/09/Programa_Jose_Antonio_Kast_Rist.pdf

[6] https://www.pdc.cl/wp-content/uploads/2021/08/Programa-Yasna-Provoste-Campillay.pdf
