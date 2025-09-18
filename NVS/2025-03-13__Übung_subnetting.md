Verwende Tools: https://chatgpt.com

# Übung Subnetting

## Übung 1

Bilde aus dem Netz 192.168.0.0 /24 4 Subnetze. Netze mit Mindestzahl an nutzbaren Host aber nicht darunter wählen: Netz a mit 20, Netz b mit 15, Netz c mit 30, und das Netz d mit den Rest Anteil der Netzwerkadressen.

**Antwort**

Netz A: 192.168.0.0/27
Netz B: 192.168.0.32/27
Netz C: 192.168.0.64/27
Netz D: 192.168.0.128/25

## Übung 2

Teile das Netz 193.170.20.0 /24 in 8 gleich große Netze! Erstelle eine Tabelle mit folgenden Angaben:
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.

**Antwort**

                Netzwerkadresse                 nutzbare Hosts                      Broadcastadresse                Subnetzmaske
Netz 1          193.170.20.0            193.170.20.1 - 193.170.20.30                193.170.20.31                   255.255.255.224
Netz 2          193.170.20.32           193.170.20.33 - 193.170.20.62               193.170.20.63                   255.255.255.224
Netz 3          193.170.20.64           193.170.20.65 - 193.170.20.94               193.170.20.95                   255.255.255.224
Netz 4          193.170.20.96           193.170.20.97 - 193.170.20.126              193.170.20.127                  255.255.255.224
Netz 5          193.170.20.128          193.170.20.129 - 193.170.20.158             193.170.20.159                  255.255.255.224
Netz 6          193.170.20.160          193.170.20.161 - 193.170.20.190             193.170.20.191                  255.255.255.224
Netz 7          193.170.20.192          193.170.20.193 - 193.170.20.222             193.170.20.223                  255.255.255.224
Netz 8          193.170.20.224          193.170.20.225 - 193.170.20.254             193.170.20.255                  255.255.255.224

## Übung 3

172.28.40.0 /26 Teile wie folgt auf: 2 Netze!
Erstelle eine Tabelle mit folgenden Angaben:
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.

**Antwort**

                Netzwerkadresse                 nutzbare Hosts                      Broadcastadresse                Subnetzmaske
Netz 1          172.28.40.0            172.28.40.1 - 172.28.40.30                   172.28.40.31                   255.255.255.224
Netz 2          172.28.40.32           172.28.40.33 - 172.28.40.62	                172.28.40.63                   255.255.255.224

## Übung 4

Wie lautet die Subnetzmaske bei der Netzadresse: 17.0.0.0 mit 10 verwendbaren Subnetzen, sowie mit mindestens 12 Hosts je Subnetz?
Antwort in Sätzen, wie sie zu dieser Lösung kommen; und erstelle eine Tabelle:

**Antwort**

Wir verwenden /28, weil /28 hat 14 nutzbare Adressen pro Netz.

             Netzwerkadresse               nutzbare Hosts                          Broadcastadresse
Netz 1       17.0.0.0                      17.0.0.1 - 17.0.0.14                    17.0.0.15
Netz 2       17.0.0.16                     17.0.0.17 - 17.0.0.30                   17.0.0.31
Netz 3       17.0.0.32                     17.0.0.33 - 17.0.0.46                   17.0.0.47
Netz 4       17.0.0.48                     17.0.0.49 - 17.0.0.62                   17.0.0.63
Netz 5       17.0.0.64                     17.0.0.65 - 17.0.0.78                   17.0.0.79
Netz 6       17.0.0.80                     17.0.0.81 - 17.0.0.94                   17.0.0.95
Netz 7       17.0.0.96                     17.0.0.97 - 17.0.0.110                  17.0.0.111
Netz 8       17.0.0.112                    17.0.0.113 - 17.0.0.126                 17.0.0.127
Netz 9       17.0.0.128                    17.0.0.129 - 17.0.0.142                 17.0.0.143
Netz 10      17.0.0.144                    17.0.0.145 - 17.0.0.158                 17.0.0.159

## Übung 5

Bestimmen Sie die Subnetmaske mit folgenden Angaben:

Netzadresse: 210.52.190.0
Subnetze: Anzahl 5
Mindestanzahl von Hosts je Subnetz: 10

**Antwort**

255.255.255.240

## Übung 6

Teile  ein /30 Netz auf!    Wozu werden diese /30 Netze am häufigsten verwendet?
Antwort:

**Antwort**

Ein /30 wird oft für Punkt-zu-Punkt-Verbindungen verwendet, bei denen nur zwei Geräte miteinander kommunizieren, wie z.B.: bei Verbindungen zwischen zwei Routern.

## Übung 7

Nennen Sie den jeweiligen Netz- und Hostanteil der Klassen A, B und C

**Antwort**
        Netzanteil          Hostanteil
A       8 Bit               24 Bit
B       16 Bit              16 Bit
C       24 Bit              8 Bit