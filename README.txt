**********************************************************************************************
*Android App zur Bachelorarbeit:    Automatisierung der Kartographierung von Stra�enschildern*
*Autor:                             Philipp Unger                                            *
*Datum:                             11.03.2013                                               *
*Hochschule:                        Universit�t Passau                                       *
**********************************************************************************************

GPStreetCam ist eine Android Applikation zum gleichzeitigen Aufzeichnen eines Videos und eines GPS-Tracks.

Die App ben�tigt mindestens die Android-Version 2.3 (Gingerbread).

Die Videoaufzeichnung erfolgt �ber den android.media.MediaRecorder die GPS-Aufzeichnung
�ber den android.hardware.SensorListener.

Das aufgezeichnete Video wird dabei im .mp4 Format und die GPS-Informationen als .gpx Datei
im Medienspeicher des Smartphones abgespeichert.

Die genaue Funktion und Vorgehensweise der Applikation kann den Kommentaren im Quellcode
entnommen werden.