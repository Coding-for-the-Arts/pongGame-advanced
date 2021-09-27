# pongGame - Advanced 
Aufgabe ist es, das Game `Pong` zu programmieren. Dabei wollen wir mit zufälliger Bewegung und User Input der Mouse ein simples Spiel programmieren. Diese Grundbausteine werden uns später helfen ein eigenes Mouse-Game zu entwickeln. 

## Pong Game
![](/img/pong.png)

Pong wurde 1972 von Atari veröffentlich und das erste kommerziell erfolgreiche Spiel. Heute gilt Pong als das Spiel, mit dem die Videospielindustrie ihren Anfang nahm.

Das Spielprinzip von Pong ist simpel: Ein Punkt („Ball“) bewegt sich auf dem Bildschirm hin und her. Jeder der beiden Spieler steuert einen senkrechten Strich („Schläger“), den er mit einem Balken (Paddle) nach oben und unten verschieben kann. Lässt man den „Ball“ am „Schläger“ vorbei, erhält der Gegner einen Punkt. [Original Atari PONG (1972)](https://www.youtube.com/watch?v=fiShX2pTz9A)

Wir werden zuerst ein einfaches Pong programmieren bei dem wir gegen den Computer spielen. 

## Setup 
Clone dein Repo: Du hast nun ein Git-Repository lokal auf deinem Computer. Versuche mit den Git-Kommandos zu arbeiten und deinen Code regelmässig zu committen und zu pushen. 
- `commit`: Speichert die Änderungen des local repository (Erstellt Snapshots des momentanen Zustandes)
- `push`: Mehrere commits auf das remote repository "pushen" (hochladen).

Hier kommen noch mehr Infos...

#### Lokales Repo
![](/img/code.png)
Nachdem du den Ordner geclonet hast, solltest du 4 Dateien und 1 Ordner in deinem Repo finden. In `pong.js`schreiben wir die Spiellogik bzw. den Code:
1. `index.html` -> Hier wird das Spiel angezeigt 
2. `pong.js` -> Hier schreiben wir den Code
3. `style.css` -> Hier sind die Styles für das html-file definiert
4. `README.md`-> Das Readme, welches du gerade liest

#### Pong Game anzeigen 
Um zu sehen was du programmmiert hast, öffnest du die index.html Datei in deinem Browser. 
Dies könnte dann so aussehen: 
![](/img/index.jpg)

## Additional
Falls du möchstest kannst dein Pong Game beliebig erweitern oder verändern, du bist nicht an den Stil der 70er Jahre gebunden.
* Versuche deinen eigenen Stil dem Pong Game hinzuzufügen (Bsp. verschwommene Bewegungen, der Ball zeichnet eine Spur, bunte Farben, etc.)
* Lass den Ball immer schneller und das Spiel somit immer schwieriger werden.
* Programmiere einen Gegenspieler. Der Einfachheit halber ist dieser Gegenspieler "dumm" und wird ebenfalls von dir bedient. 