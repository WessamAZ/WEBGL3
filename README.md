# Computer Graphics, Winter Semester 2023

- **Name:** Your name, e.g., Maxi Musterfrau
- **E-Mail:** Your e-mail, e.g., maxi@musterfrau.de
- **Matriculation no.:** Your matriculation number: 123456789

<!--------------------------------------------------------------------------->
## Assignment 1

### Assigment 1a
1- Bestimmen Sie die Lichtposition und -richtung innerhalb des Vertex-Shaders "VS" und übergeben Sie sie über v_lightDirection, v_normal paarameters an "FS".
2- In "FS", abhängig von v_normal und v_lightDirection, berechne ich die diffuse Farbe und die spiegelnde Farbe, also berechne ich damit die "endgültige Farbe" der Ausgangsfarbe, um zu zeigen, wie sich das Licht abhängig von der Lichtrichtung und -position auf das Objekt auswirkt. 

### Assigment 1b
- Die zur Materialseite hinzugefügten Lichtpositionsparameter „Ich habe versucht, eine neue Seite für diese Parameter hinzuzufügen, aber es hat nicht funktioniert, also habe ich sie zu den vorhandenen Parametern (Umgebung, Diffus und Spiegelung) innerhalb der Materialseite in der Benutzeroberfläche hinzugefügt.“ .
- In vs habe ich die vorhandenen Werte durch diese Lichtparameter ersetzt.

### Assigment 1 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 2

### Assignment 2a
- Ich extrahiere die Parameter ambientColor, specularColor und diffuseColor in der fs-Funktion mithilfe der Funktionalität „texture“, um das Objekt mit dem geschriebenen Bild abzudecken, also texturiere ich das Bild über dem Objekt und verwende dann diese Parameter, um die endgültige Farbe zu extrahieren.

### Assignment 2b
- twMatrix ist eine Transformationsmatrix, die den Normalenvektor vom Texturraum (Tangentenraum) in den Weltraum oder einen anderen relevanten Raum transformiert. Die resultierende gestörte Normale (Normal) wird dann in Beleuchtungsberechnungen verwendet, um das Erscheinungsbild von Oberflächenunebenheiten oder Details zu erzeugen, also berechne ich twMatrix in vs.

- Dann transformiere ich in fs mithilfe der Transformationsmatrix (twMatrix) die RGB-Werte einer Textur, die ich vom BumpMap-Texture-Sampler erhalten habe. Das Ergebnis wird in der Variablen twTexture gespeichert.


### Assignment 2c
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assigment 2 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 3

### Assignment 3a
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 3b
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 3 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 4

### Assignment 4a
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 4b
<!-- Briefly describe your solution. If you did not solve the assignment, simply enter "Not solved." -->

### Assignment 4 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->