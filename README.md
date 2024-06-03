# M114

## Titel für Aufgaben:

### Daten_Codieren

### Komprimieren

### Bilder

1. Bestimmen Sie die Farben für die folgenden RGB-Farbcodes (in DEZ und HEX). Nutzen Sie den RGB-Farbenmixer. Benutzen Sie dazu die beiden Online-Tools: 
   - [w3schools.com/colors/colors_hexadecimal.asp](https://www.w3schools.com/colors/colors_hexadecimal.asp)
   - [w3schools.com/colors/colors_rgb.asp](https://www.w3schools.com/colors/colors_rgb.asp)
   
   - **RGB(255, 255, 255)** entspricht Farbe: Weiß
   - **RGB(0, 0, 0)** entspricht Farbe: Schwarz
   - **RGB(252, 178, 91)** entspricht Farbe: Dunkles Gold
   - **#FF0000** entspricht Farbe: Rot
   - **#00FF00** entspricht Farbe: Grün
   - **#0000FF** entspricht Farbe: Blau
   - **#FFFF00** entspricht Farbe: Gelb
   - **#00FFFF** entspricht Farbe: Cyan
   - **#FF00FF** entspricht Farbe: Magenta
   - **#000000** entspricht Farbe: Schwarz
   - **#FFFFFF** entspricht Farbe: Weiß
   - **#00BC00** entspricht Farbe: Mittleres Grün

2. Bestimmen Sie die Farben für die folgenden prozentualen CMYK-Angaben. Nutzen Sie den CMYK-Farbenmixer bzw. das folgende Online-Tool: 
   - [w3schools.com/colors/colors_cmyk.asp](https://www.w3schools.com/colors/colors_cmyk.asp)
   
   - **C:0%, M:100%, Y:100%, K:0%** entspricht Farbe: Rot
   - **C:100%, M:0%, Y:100%, K:0%** entspricht Farbe: Grün
   - **C:100%, M:100%, Y:0%, K:0%** entspricht Farbe: Blau
   - **C:0%, M:0%, Y:100%, K:0%** entspricht Farbe: Gelb
   - **C:100%, M:0%, Y:0%, K:0%** entspricht Farbe: Cyan
   - **C:0%, M:100%, Y:0%, K:0%** entspricht Farbe: Magenta
   - **C:100%, M:100%, Y:100%, K:0%** entspricht Farbe: Schwarz (bei vollem Toner)
   - **C:0%, M:0%, Y:0%, K:100%** entspricht Farbe: Schwarz (einfacher)
   - **C:0%, M:0%, Y:0%, K:0%** entspricht Farbe: Weiß
   - **C:0%, M:46%, Y:38%, K:22%** entspricht Farbe: Braun

3. Berechnen Sie den theoretischen Speicherbedarf in Bit und in Byte eines unkomprimierten RGB-Bildes mit der Größe 640 x 480 und 8 Bit Auflösung pro Farbkanal.
   - Auflösung: 640 x 480 Pixel
   - Farbkanäle: 3 (RGB)
   - Bits pro Farbkanal: 8
   - Speicherbedarf = 640 * 480 * 3 * 8 Bits = 7,372,800 Bits = 921,600 Bytes

4. Sie müssen die Webseite der Firma Muster-GmbH gestalten. Als Hintergrundbild (background-image) soll eine gekachelte Textur verwendet werden. (background-repeat: repeat). Auf diesen Hintergrund wird das Firmenlogo gelegt. 
   - **Bildformate für Hintergrund:** PNG oder JPEG
     - **Begründung:** PNG bietet eine verlustfreie Kompression und Transparenzunterstützung, ideal für Texturen und Logos. JPEG kann verwendet werden, wenn eine kleinere Dateigröße bevorzugt wird, aber es sollte bei der Bildqualität vorsichtig verwendet werden, da es verlustbehaftet komprimiert.

5. Sie haben ein 30-Zoll-Display (Diagonale) im Format 16:10 und 100ppi erworben. Was ist die Pixelauflösung horizontal und vertikal?
   - Diagonale: 30 Zoll
   - Seitenverhältnis: 16:10
   - PPI (Pixel per Inch): 100
   - Auflösung berechnen:
     - Diagonale in Pixeln = 30 Zoll * 100 PPI = 3000 Pixel
     - Verhältnis 16:10 bedeutet:
       - Höhe² + Breite² = 3000²
       - (10x)² + (16x)² = 3000²
       - 100x² + 256x² = 9000000
       - 356x² = 9000000
       - x² = 25281.46
       - x ≈ 159
       - Höhe = 10x ≈ 1590 Pixel
       - Breite = 16x ≈ 2544 Pixel
     - **Auflösung:** 2544 x 1590 Pixel

6. Sie drucken ein quadratisches Foto mit einer Kantenlänge von 2000 Pixeln mit 600dpi. Wie groß in cm wird dieses?
   - Auflösung: 600 dpi
   - Bildgröße in Pixel: 2000 x 2000
   - Größe in Zoll: 2000 / 600 = 3.33 Zoll
   - Größe in cm: 3.33 Zoll * 2.54 cm/Zoll ≈ 8.46 cm

7. Berechnen Sie den Speicherbedarf für ein unkomprimiertes Einzelbild im HD1080p50-Format bei einer True-Color-Farbauflösung.
   - Auflösung: 1920 x 1080 Pixel
   - Farbkanäle: 3 (RGB)
   - Bits pro Farbkanal: 8
   - Speicherbedarf = 1920 * 1080 * 3 * 8 Bits = 49,766,400 Bits = 6,220,800 Bytes = 6.22 MB

8. Welchen Speicherbedarf hat das Video aus der vorangegangenen Aufgabe bei einer Spieldauer von 3 Minuten?
   - Bildrate: 50 fps
   - Spieldauer: 3 Minuten = 3 * 60 Sekunden = 180 Sekunden
   - Speicherbedarf pro Sekunde = 6.22 MB * 50 = 311 MB
   - Gesamtspeicherbedarf = 311 MB * 180 Sekunden = 55,980 MB = 55.98 GB

9. Ihre Digitalkamera bietet für die Speicherung ihrer Bilder die beiden Formate RAW und JPG an. Wo liegen die Unterschiede und was sind die Verwendungszwecke?
   - **RAW:**
     - **Unterschied:** Unkomprimiertes Format, speichert alle Daten direkt von der Kamera ohne Verluste.
     - **Verwendungszweck:** Maximale Flexibilität bei der Nachbearbeitung, da keine Daten verloren gehen, geeignet für professionelle Fotografie.
   
   - **JPG:**
     - **Unterschied:** Komprimiertes Format, reduziert Dateigröße durch Datenkompression mit Qualitätsverlust.
     - **Verwendungszweck:** Schnelles Teilen und Anzeigen von Bildern, weit verbreitet in Webanwendungen und für den persönlichen Gebrauch.

10. Sie möchten ihr neulich erstelltes Gameplay-Video auf Youtube veröffentlichen. Was sind die technischen Vorgaben dazu? (Format, Bildrate, Farbauflösung, Video-, Audiocodec etc.). Gibt es allenfalls rechtliche Einschränkungen?
    - **Format:** Vorzugsweise MP4.
    - **Bildrate:** Typischerweise 24, 25 oder 30 fps.
    - **Farbauflösung:** Empfohlen ist mindestens 8 Bit pro Farbkanal.
    - **Video-/Audiocodec:** H.264 für Video, AAC für Audio.
    - **Rechtliche Einschränkungen:** Ja, z.B. Urheberrechte für Musik oder fremdes Material im Video.

11. Was ist der Unterschied zwischen dem Interlaced Mode und dem Progressive Mode?
    - **Interlaced:** Bild wird in zwei Halbbildern dargestellt, abwechselnd in geraden und ungeraden Zeilen. Älteres Verfahren, kann bei Bewegungen zu Flimmern führen.
    - **Progressive:** Vollständiges Bild wird gleichzeitig dargestellt, bietet eine bessere Bildqualität und ist für moderne Anwendungen üblicher.

12. Was versteht man unter Artefakten und welche kennen sie?
    - **Artefakte:** Unerwünschte Anomalien oder Störungen in digitalen Medien, die durch Komprimierung, Übertragung oder andere Verarbeitungsschritte entstehen können.
    - **Beispiele:** Blockbildung, Verzerrungen, Farbverfälschungen.

13. Berechnen Sie die Datenrate in GigaBit per Second oder kurz Gbps für die Übertragung eines unkomprimierten digitalen Videosignals HD1080i50 ohne Unterabtastung und 8 Bit Auflösung pro Farbkanal.
    - **Datenrate:** \( 1920 \times 1080 \times 50 \times 8 = 829,440,000 \) Bits pro Sekunde oder ca. 829.44 Mbps.

14. Nach wie vielen Minuten unkomprimierten HD1080i50 Video wäre eine DVD-5 (Single-Layer DVD mit 4.7GB) voll?
    - **Speicherbedarf pro Sekunde:** \( 1920 \times 1080 \times 50 \times 8 = 49,766,400 \) Bits
    - **Speicherbedarf für 1 Minute:** \( 49,766,400 \times 60 = 2,985,984,000 \) Bits
    - **Speicherbedarf für 4.7GB:** \( 4.7 \times 8 \times 1024 \times 1024 \times 1024 = 40,212,428,800 \) Bits
    - **Minutenanzahl:** \( \frac{40,212,428,800}{2,985,984,000} \approx 13.47 \) Minuten.

15. Was ist der Unterschied zwischen einem Codec und einem Mediencontainer?
    - **Codec:** Komprimierungs- und Dekomprimierungsalgorithmen zur Codierung und Decodierung von Audio- und Videodaten.
    - **Mediencontainer:** Enthält mehrere Mediendateien, Metadaten und den Codec zur Wiedergabe der Medien.
