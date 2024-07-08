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
***
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

#### a. Warum benötigt man AD-Wandler?

AD-Wandler (Analog-Digital-Wandler) werden benötigt, um analoge Signale, wie sie beispielsweise von Mikrofonen oder Temperatursensoren erzeugt werden, in digitale Signale umzuwandeln. Dies ist wichtig, weil digitale Signale von Computern und digitalen Systemen verarbeitet, gespeichert und übertragen werden können. Analoge Signale können variieren und sind anfällig für Störungen und Verzerrungen, während digitale Signale stabiler und einfacher zu handhaben sind.

#### b. Warum geht eine A/D-Wandlung immer mit einem Datenverlust einher?

Eine A/D-Wandlung geht immer mit einem Datenverlust einher, weil der Prozess der Digitalisierung eine kontinuierliche analoge Welle in eine diskrete Anzahl von Datenpunkten umwandelt. Dabei wird das kontinuierliche Signal in zeitliche Intervalle unterteilt (Sampling) und jedem dieser Intervalle ein bestimmter Wert zugewiesen (Quantisierung). Da es eine unendliche Anzahl von möglichen Werten im analogen Signal gibt, aber nur eine endliche Anzahl von Werten nach der Digitalisierung, gehen dabei zwangsläufig Informationen verloren.

#### c. Gibt eine höhere oder eine tiefere Samplingrate eine präzisere Abbildung des Originals? Begründen Sie!

Eine höhere Samplingrate gibt eine präzisere Abbildung des Originals. Dies liegt daran, dass bei einer höheren Samplingrate mehr Datenpunkte des analogen Signals erfasst werden. Nach dem Nyquist-Shannon-Abtasttheorem muss die Samplingrate mindestens doppelt so hoch sein wie die höchste Frequenz des zu digitalisierenden Signals, um eine verlustfreie Rekonstruktion zu ermöglichen. Wenn die Samplingrate höher ist, werden mehr Details des analogen Signals erfasst, wodurch die digitale Repräsentation genauer wird und das Signal bei der Wiedergabe näher am Original bleibt.
***
### Bilder Komprimieren

1. Um ein gewisses Verständnis für die Luminanz-Chrominanz-Beschreibung von Farben zu erhalten, lösen sie die folgenden Aufgaben. Benutzen sie dazu dieses Online-Tool: https://colorizer.org/
    - RGB 255/255/255 entspricht Weiss und ergibt in YCbCr: Y = 1, Cb = 0, Cr = 0
    - RGB 0/0/0 entspricht Schwarz und ergibt in YCbCr: Y = 0, Cb = 0, Cr = 0
    - Y:0, Cb:0.5, Cr:0 entspricht der Farbe: Blau
    - Y:0, Cb:-0.5, Cr:0 entspricht der Farbe: Gelb
    - Y:0, Cb:0, Cr:0.5 entspricht der Farbe: Rot
    - Y:0, Cb:0, Cr:-0.5 entspricht der Farbe: Cyan
    - Y:0.3, Cb:0.5, Cr:-0.17 entspricht der Farbe: Hellblau

2. Ein RGB-Farbbild benutzt nur die Farbe Weiss als Hintergrund und ein Hellblau mit folgenden Werten: R=33, G=121, B=239 (8 Bit pro Farbkanal). Das Bild soll in ein Graustufenbild umgewandelt werden. Berechnen sie den für das Hellblau entsprechende Grauwert. (8 Bit pro Farbkanal)

    Der Grauwert kann mit der Formel berechnet werden:
    \[
    \text{Gray} = 0.299 \times R + 0.587 \times G + 0.114 \times B
    \]

    Für Hellblau (R=33, G=121, B=239):
    \[
    \text{Gray} = 0.299 \times 33 + 0.587 \times 121 + 0.114 \times 239 \approx 110.34
    \]

3. Berechnen sie, wieviel Speicher eingespart wird, wenn ein Bild mit Subsampling 4:1:1 komprimiert wird.

    Bei 4:1:1-Subsampling werden die Chrominanzinformationen (Cb und Cr) nur für jeden vierten Pixel gespeichert. Dies bedeutet eine Reduktion der Chrominanzdaten auf 25%. Der Speicherbedarf für die Chrominanzdaten beträgt somit nur 25% der ursprünglichen Datenmenge, wodurch insgesamt etwa 50% Speicherplatz eingespart werden können, wenn man davon ausgeht, dass die Luminanzdaten unkomprimiert bleiben.

4. Der folgende Youtube-Film beschäftigt sich mit RGB und YCrCb: https://www.youtube.com/watch?v=3dET-EoIMM8 Schauen sie den an und beantworten sie anschliessend diese Fragen:
   - **a. Kann man durch die Bildumwandlung vom RGB- in den YCbCr-Farbraum Speicherplatz einsparen?**
  - Ja, durch die Umwandlung und anschließende Subsampling der Chrominanzkanäle (Cb und Cr) kann Speicherplatz eingespart werden.
  
- **b. Kann ein Beamer ein Bild im YCbCr-Farbraum darstellen?**
  - Nein, ein Beamer muss das YCbCr-Signal wieder in RGB umwandeln, um es korrekt darstellen zu können.

- **c. Wie rechnet man ein Farbbild in ein Graustufenbild um?**
  - Ein Farbbild wird in ein Graustufenbild umgewandelt, indem man die Helligkeitsinformation (Luminanz) extrahiert, typischerweise mit der Formel: \[ \text{Grauwert} = 0.299 \times R + 0.587 \times G + 0.114 \times B \]

- **d. Warum hat bei der Umwandlung eines Farbbildes in ein Graustufenbild der Grünanteil am meisten Gewicht?**
  - Der Grünanteil hat am meisten Gewicht, weil das menschliche Auge am empfindlichsten auf Grüntöne reagiert. Dies entspricht den physiologischen Eigenschaften des menschlichen Sehvermögens.


5. Fragen zu Chroma-Subsampling (YouTube-Video)

- **a. Warum verschlechtert sich die Bildschärfe von 4:1:1-Subsampling gegenüber 4:4:4-Subsampling nicht?**
  - Die Bildschärfe bleibt weitgehend erhalten, weil die Luminanzinformationen (Y) in voller Auflösung gespeichert werden, und das menschliche Auge weniger empfindlich auf Farbdetails (Chrominanz) reagiert.

- **b. Ein quadratisches 24-Bit-RGB-Bild mit einer Kantenlänge von 1000 Pixel soll mit 4:1:1 unterabgetastet werden. Wieviel Speicherplatz wird damit eingespart?**

  Ein 24-Bit-RGB-Bild hat 3 Kanäle (R, G, B) mit je 8 Bit pro Kanal:

  \[ \text{Speicherplatz} = 1000 \times 1000 \times 3 \times 8 \text{ Bit} = 24 \text{ MBit} \]

  Bei 4:1:1 Subsampling:

  - Y: 1000 x 1000 (volle Auflösung)
  - Cb: 250 x 1000 (horizontale Unterabtastung um Faktor 4)
  - Cr: 250 x 1000 (horizontale Unterabtastung um Faktor 4)

  \[ \text{Speicherplatz nach Subsampling} = 1000 \times 1000 \times 8 \text{ Bit (Y)} + 250 \times 1000 \times 8 \text{ Bit (Cb)} + 250 \times 1000 \times 8 \text{ Bit (Cr)} = 16 \text{ MBit} \]

  Die Speicherersparnis:

  \[ \text{Ersparnis} = \frac{24 \text{ MBit} - 16 \text{ MBit}}{24 \text{ MBit}} \approx 33.33\% \]

***
### Kryptographie
#### SYMMETRISCHE VERSCHLÜSSELUNGSVERFAHREN

2.
   GHU DQJULII HUIROJW CXU WHHCHLW GLH ZXHUIHO VLQG JHIDOOHQ LFK 
   NDP VDK XQG VLHJWH WHLOH XQG KHUUVFKH
   
   DER ANGRIFF FUEHLTE DUR VEEFEIV DIE UUEIFELE SIND GEFAELLEN ICH KAM SAH UND SIEGTE TEILE UND HERRSCHE

3.
   Das Wort "BEEF" wird mit dem Schlüsselwort "AFFE" verschlüsselt zu "BJJI".
   Der Geheimtext "WRKXQT" wird mit dem Schlüsselwort "SECRET" entschlüsselt zu "DMHILA".

4.
   "DER VERSCHLUESSELUNGSCODE IST GEBROCHEN"

   WFR SBRUDHLALUCSUEAHFPDPXHGZGO TGF ZAFUEOSR

5. Ergebnis: 1001111110011110

#### ASYMMETRISCHE VERSCHLÜSSELUNGSVERFAHREN
2.
   - Bei der Entschlüsselung als "Hasler Harry" sollte es nicht möglich sein, die Nachricht zu entschlüsseln, da der private Schlüssel nicht mit dem verwendeten öffentlichen Schlüssel zur Verschlüsselung übereinstimmt.
   - Bei der Entschlüsselung als "Muster Felix" sollte die Nachricht erfolgreich entschlüsselt werden können, da der private Schlüssel mit dem verwendeten öffentlichen Schlüssel übereinstimmt.

7. 
   - Beim ersten Überprüfen der Signatur am unveränderten Dokument sollte die Signatur gültig sein und die Integrität und Authentizität des Dokuments bestätigen.
   - Nach der vorgenommenen Änderung am Dokument wird die Signatur nicht mehr gültig sein. Die Überprüfung wird fehlschlagen, da die ursprüngliche Signatur für das ursprüngliche unveränderte Dokument erstellt wurde und nun nicht mehr mit dem veränderten Inhalt übereinstimmt.

#### DIE SCHLÜSSELVERWALTUNG

1. Ein Public-Key kann durch Überprüfung der Signatur eines Zertifikats verifiziert werden, das den Public-Key zusammen mit Identitätsinformationen enthält.
2. Die Public Key Infrastruktur (PKI) umfasst die Richtlinien, Prozesse, Rollen und Technologien zur Verwaltung von digitalen Zertifikaten und Public Keys.
3. - Certification-Authority (CA): Eine CA ist eine vertrauenswürdige Organisation, die digitale Zertifikate ausstellt und verwaltet, um die Identität und den öffentlichen Schlüssel von Benutzern oder Systemen zu verifizieren.
   - Trust-Center (TC): Ein Trust-Center ist eine Organisation, die die Schlüsselverwaltung und Sicherheitsdienste bereitstellt, oft im Rahmen einer PKI, um Vertrauen und Sicherheit in digitale Kommunikation zu gewährleisten.

#### SICHERES INTERNET UND ZERTIFIKATE
1. DigiCert EV RSA CA G2 und Issued On	Thursday, November 16, 2023 at 1:00:00 AM und Expires On	Friday, December 13, 2024 at 12:59:59 AM

2. Common Name (CN)	R3
   Organization (O)	Let's Encrypt
   Organizational Unit (OU)	<Not Part Of Certificate>
   Issued On	Sunday, June 2, 2024 at 7:31:20 PM
   Expires On	Saturday, August 31, 2024 at 7:31:19 PM

3. Webseite ist Not Secure, deshalb keine gültige Zertifikatsinformationen

4. Um sicherzustellen, dass ich die echte Software-Version erhalte, überprüfe ich die offizielle Website des Herstellers und die digitale Signatur der heruntergeladenen Datei.

5. Ja, es ist möglich, eine virtuelle Linux-Maschine mit VirtualBox und Ubuntu zu erstellen und dann eine Remoteverbindung von Ihrem Windows-PC über SSH einzurichten. 

6. HTTP (HyperText Transfer Protocol) überträgt Daten unverschlüsselt über das Netzwerk und verwendet standardmäßig Port 80, während HTTPS (HyperText Transfer Protocol Secure) Daten mit SSL/TLS-Verschlüsselung schützt, um Sicherheit und Integrität der Übertragung zu gewährleisten und Port 443 verwendet. Bei HTTPS können mit Wireshark durch den Server Name Indication (SNI)-Header die besuchten Webseiten trotz Verschlüsselung identifiziert werden.

7. Beide sind HTTPS, benützen aber andere Zertifikate von andere Organizationen

8. CAcert bietet kostenlos SSL/TLS-Zertifikate an, die durch eine Community verifiziert werden, jedoch mit begrenzter Unterstützung in gängigen Webbrowsern. Let's Encrypt bietet ebenfalls kostenlose Zertifikate an, die automatisiert und weit verbreitet akzeptiert werden.

   - Let's Encrypt ist eine von der Internet Security Research Group (ISRG) unterstützte Zertifizierungsstelle, die ebenfalls kostenlose SSL/TLS-Zertifikate anbietet.
   - Die Zertifikate von Let's Encrypt sind automatisiert und werden durch den ACME-Protokollstandard bereitgestellt, was die Einrichtung und Erneuerung vereinfacht.
   - Let's Encrypt-Zertifikate sind in den meisten modernen Webbrowsern und Betriebssystemen vorinstalliert und genießen ein hohes Maß an Vertrauen.

   - CAcert ist eine Community-basierte Zertifizierungsstelle, die kostenlos SSL/TLS-Zertifikate anbietet.
   - Die Zertifikate werden von einer Community von Freiwilligen ausgestellt, die Verifikation erfolgt durch das Web of Trust (WoT)-System.
   - Die Vertrauensstellung der CAcert-Zertifikate in gängigen Webbrowsern ist jedoch begrenzt, da sie nicht in allen Browsern vorinstalliert sind und von vielen als weniger vertrauenswürdig angesehen werden.

9. Für einen Webshop, wo Kreditkartenzahlungen verarbeitet werden, ist ein Extended Validation (EV) Zertifikat der richtige Typ. Es bietet die höchste Sicherheit und Vertrauensstufe, da es strengere Validierungsprozesse durchläuft und in Browsern eine grüne Adressleiste mit dem Unternehmensnamen anzeigt, was die Vertrauenswürdigkeit für Kunden erhöht.

10. OpenPGP konzentriert sich auf die Sicherung von Kommunikation und Dateien durch Verschlüsselung und Signierung, während X.509 die Authentifizierung und Vertrauensstellung über digitale Zertifikate in einer Vielzahl von Anwendungen und Systemen ermöglicht.

11. Beim Aufruf einer sicheren Webseite über HTTPS sendet der Webbrowser eine Anfrage an den Server, der daraufhin sein SSL/TLS-Zertifikat zur Authentifizierung zurücksendet. Dieses Zertifikat wird vom Browser überprüft, um die Identität des Servers zu bestätigen, bevor eine sichere Verschlüsselung der Daten mittels TLS-Protokoll ermöglicht wird.

12. S/MIME steht für "Secure/Multipurpose Internet Mail Extensions" und ist ein Sicherheitsstandard für die Verschlüsselung und digitale Signierung von E-Mails, um deren Vertraulichkeit, Integrität und Authentizität sicherzustellen.

13. Das Problem beim Archivieren verschlüsselter geschäftlicher E-Mails liegt darin, dass die Nachrichten entschlüsselt werden müssen, um sie zu archivieren, was Datenschutz- und Sicherheitsbedenken aufwerfen kann. Eine Lösung könnte darin bestehen, eine sichere Schlüsselverwaltung und transparente Entschlüsselungstechnologien zu implementieren, um den gesetzlichen Anforderungen zu entsprechen, ohne die Sicherheit zu gefährden.

#### PGP und OpenPGP

20. Fremden Public-Key verifizieren: Die Authentizität eines Public Keys kann durch ein digitales Zertifikat einer vertrauenswürdigen Zertifizierungsstelle (CA) überprüft werden. Diese bestätigt, dass der Schlüssel tatsächlich zu der Person gehört, von der Sie dies annehmen.

21. Frage zum OpenPGP-Schlüssel: Ein OpenPGP-Schlüssel besteht aus einem Public Key und einem Private Key. Erkennbar ist er oft an einer Datei mit der Endung ".asc" oder ".gpg". Der Schlüssel enthält auch Informationen wie den Schlüsselinhaber und das Ablaufdatum.

22. X.509-Schlüsselpaar: Ein X.509-Schlüsselpaar wird für S/MIME (Secure/Multipurpose Internet Mail Extensions) verwendet, um E-Mails zu signieren und zu verschlüsseln. Im Gegensatz zu OpenPGP basiert X.509 auf einer hierarchischen Struktur mit Zertifikaten von CAs. OpenPGP nutzt ein Web of Trust. S/MIME ist standardisierter und wird häufig in Unternehmensumgebungen genutzt.

***
### Aufgabe für 08.07.24

Blockchain-Verfahren: Eine Blockchain ist eine dezentrale, digitale Datenbank, die Informationen in Blöcken speichert, die durch kryptografische Verfahren miteinander verkettet sind. Jeder Block enthält Transaktionsdaten und einen Verweis auf den vorherigen Block, was Manipulationen nahezu unmöglich macht.

Warum Blockchain? Blockchain bietet Sicherheit, Transparenz und Dezentralisierung. Dadurch wird Vertrauen in digitale Transaktionen geschaffen, ohne dass eine zentrale Autorität benötigt wird.

Zusammenhang Blockchain zu Bitcoin, Ethereum, Smart Contracts: Bitcoin war die erste Anwendung der Blockchain-Technologie und dient als digitales Währungssystem. Ethereum erweiterte die Blockchain um programmierbare Verträge, sogenannte Smart Contracts, die automatisch ausgeführt werden, wenn vordefinierte Bedingungen erfüllt sind.

Weitere Einsatzmöglichkeiten: Neben Kryptowährungen kann Blockchain in Lieferkettenmanagement, Gesundheitswesen, Wahlsystemen, digitaler Identitätsverifikation und im Immobiliensektor eingesetzt werden.











