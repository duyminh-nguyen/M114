# M114

## Titel für Aufgaben:

### Daten_Codieren

1. **Ergänzung der Tabelle:**
   - Studieren Sie die vollständig ausgefüllte Tabelle und beachten Sie insbesondere die Spalten mit den Binärwerten. Was fällt Ihnen auf?

DEC | HEX | BIN 23 | BIN 22 | BIN 21 | BIN20
--- | --- | ------ | ------ | ------ | ------
0   | 0   | 0      | 0      | 0      | 0
1   | 1   | 0      | 0      | 0      | 1
2   | 2   | 0      | 0      | 1      | 0
3   | 3   | 0      | 0      | 1      | 1
4   | 4   | 0      | 1      | 0      | 0
5   | 5   | 0      | 1      | 0      | 1
6   | 6   | 0      | 1      | 1      | 0
7   | 7   | 0      | 1      | 1      | 1
8   | 8   | 1      | 0      | 0      | 0
9   | 9   | 1      | 0      | 0      | 1
10  | A   | 1      | 0      | 1      | 0
11  | B   | 1      | 0      | 1      | 1
12  | C   | 1      | 1      | 0      | 0
13  | D   | 1      | 1      | 0      | 1
14  | E   | 1      | 1      | 1      | 0
15  | F   | 1      | 1      | 1      | 1

2. **Umrechnung von Dezimal zu Binär:**
   - Dezimalzahl: 911
   - Binärzahl: 1110001111

3. **Umrechnung von Binär zu Dezimal:**
   - Binärzahl: 10110110
   - Dezimalzahl: 182

4. **Umrechnung von Binär zu Hexadezimal:**
   - Binärzahl: 1110001010100101
   - Hexadezimalzahl: E2A5

5. **Addition von binären Zahlen:**
   - 11011001
   - + 01110101
   - ----------
   - 100101110 (Übertrag wird ignoriert)

6. **Bedeutung der binären Werte:**
   - a. Möglicherweise eine IP-Adresse oder eine andere Form von digitaler Adresse.
   - b. Kann eine Folge von Daten oder Steuerbefehlen darstellen.

7. **Linux-Bash-Zeile:**
   - Die Zeile könnte die Berechtigungen für die Datei "CreateWeeklyReport" auf 751 setzen, wobei 7 die Berechtigungen für den Eigentümer, 5 die Berechtigungen für die Gruppe und 1 die Berechtigungen für andere Benutzer darstellt.

8. **Codebreite für Kabinenzählung:**
   - Die Codebreite hängt von der Anzahl der Gondeln ab, die maximal gleich der nächstgrößeren Potenz von 2 sein sollte. Für 107 Gondeln würde eine Codebreite von 7 Bit ausreichen.

9. **Speicherkapazität mit 12-Bit-Adress-/16-Bit-Datenbus:**
   - Die Speicherkapazität beträgt \( 2^{12} \) Adressen * 16 Bit = 65536 Bytes oder 64 kiB.

10. **Übertragungsraten mit serieller Leitung:**
    - a. Mit 1 MHz Taktsignal können pro Sekunde 1 Million Bytes übertragen werden.
    - b. Bei 8 Bit-parallel Verbindung wären es 8 Millionen Bytes pro Sekunde.

11. **Vorzeichenbehaftete Binärzahlen:**
    - a. Für unsigned integer: Kleinster Wert: 0, Größter Wert: 255.
    - b. Für signed integer: Kleinster Wert: -128, Größter Wert: 127.
    - c. \( +83 \) als signed integer: 01010011
    - d. \( -83 \) als signed integer mit Zweierkomplement: 10101101
    - e. Die Addition von \( 01010011 + 10101101 \) ergibt 0.
    - f. Die Dezimalzahl 0 als signed integer: 00000000
    - g. Die Dezimalzahl +150 kann nicht in einen vorzeichenbehafteten Binärwert umgewandelt werden, da dieser über den maximal

12. **Fliesskommazahlen (Floating Point Numbers):**
   - Fliesskommazahlen sind eine Möglichkeit, Zahlen mit Dezimalstellen in Computern darzustellen.
   - Eine Fliesskommazahl wird üblicherweise als Mantisse und Exponent dargestellt, z.B. \(1.234 \times 10^5\).
   - Die Mantisse repräsentiert die signifikanten Stellen der Zahl, während der Exponent die Größenordnung angibt.
   - Eine mögliche Darstellung in Binärformat wäre nach dem IEEE 754 Standard, der eine Vorzeichenbit, einen Exponenten und eine Mantisse verwendet.

### Komprimieren

1. **Huffman-Algorithmus:**
   - In anderen IT-Bereichen kommen Baumstrukturen beispielsweise in Datenbanken (B-Bäume, AVL-Bäume) und Dateisystemen (Verzeichnisbäume) vor.
   - Ein binärer Baum unterscheidet sich von einem nicht binären Baum dadurch, dass jeder Knoten höchstens zwei Kinder hat.

2. **Huffman-Algorithmus:**
   - Diese Aufgabe erfordert die Erstellung eines Huffman-Codes für ein selbst gewähltes Wort und den Austausch der Codes mit einem Partner zur Überprüfung der Dekomprimierungsfähigkeit.

3. **RLC:**
   - Bei einem Farbbild könnten benachbarte Pixel mit identischer Farbe zusammengefasst werden, ähnlich wie bei einem Schwarz/Weiß-Bild, jedoch unter Berücksichtigung der Farbkanäle (z.B. RGB).
   - Die Bitbreite für die Codierung hängt von der Anzahl der Farben im Bild ab und sollte ausreichend sein, um alle möglichen Farbwerte darzustellen. Bei einem einfarbigen Bild würde eine Bitbreite von 1 ausreichen.

4. **RLC:**
   - Die Grafik sollte als wiederholendes Muster von Schwarz und Weiß aussehen, beginnend mit Weiß in der linken oberen Ecke. Die genaue Darstellung hängt von der Reihenfolge und Anzahl der wiederholten Farben im Code ab.

8. **Weitere Verfahren für verlustlose Kompression:**
   - Weitere Verfahren sind z.B. das Lempel-Ziv-Welch (LZW) Verfahren, Burrows-Wheeler-Transformation (BWT), Run-Length-Encoding (RLC) und das ZIP-Kompressionsverfahren.
   - Daten, die verlustlos komprimiert werden sollen, sind solche, bei denen keine Information verloren gehen darf, z.B. Textdokumente, Programmcode, oder Bilddaten im RAW-Format.

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
