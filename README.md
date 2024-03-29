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
- Ich berechne einfach pumbNormal und verwende es anstelle von "normliaze", nachdem ich die Intensität des Parameters verwendet habe, um die Konzentration und die Häufigkeit anzuzeigen, um den Replikanten anzuzeigen, nachdem ich diese Parameter zur Material-Benutzeroberfläche hinzugefügt habe, damit der Benutzer diese beiden Parameter steuern kann.
- Der checkPumb-Parameter dient zum Aktivieren/Deaktivieren der Pubm-Funktion für das Objekt.

### Assigment 2 Extras
<!-- Describe any extra features that you implemented. Make sure to cite your sources. -->

<!--------------------------------------------------------------------------->
## Assignment 3

### Assignment 3a
- Das neue Panel "Oval Camera AnimationPane" dient zur Steuerung der Kameraanimation "Start, Stop, Add-Keyfram und Remove-Keyfram".
– Die Funktion updateCameraForOval in der Datei meshrenderer.html berechnet den Kamerapfad abhängig von der Ovalfunktion mithilfe von ovalPath und verwendet dann updateCameraForOval in der Renderfunktion, um die Kamerapositionsparameter jederzeit zu aktualisieren.
- Verbinden Sie die Controller der Schnittstellentasten mit der Funktion updateCameraForOval in der Renderfunktion.

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