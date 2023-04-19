Softwaretechnologie: Java 2

# Übung 3

In dieser Übung werden Sie einen Merge-Konflikt beheben. Dazu müssen wir einen Merge-Konflikt provozieren. Die dieswöchige Übung kommt also in zwei Teilen, die Sie **zu zwei unterschiedlichen Zeiten** bearbeiten müssen.
Dazu machen Sie Ihre Änderungen diesmal nicht auf einem eigenen Branch, sondern im `main`-Branch.

## Teil 1

Bitte erledigen Sie Teil 1 **vor Sonntag, 23.04., 21 Uhr**.

### a) Repository klonen und Eclipse-Projekt anlegen

Klonen Sie dieses Repository direkt in Eclipse und importieren Sie das Projekt.

### b) Code bearbeiten

In der Klasse `idh.java.Main` befindet sich eine `main`-Methode, die nichts anderes ausgibt als den String "Ich packe in meinen Koffer ein Netzteil für mein Telefon".

Fügen Sie der Liste der zu packenden Gegenstände einen weiteren (noch nicht genannten) hinzu, so dass der Satz z.B. lautet: "Ich packe in meinen Koffer ein Netzteil für mein Telefon und ein Telefon."

### c) Commit
Committen Sie alle Ihre Änderungen am Quellcode im `main`-Branch, **ohne sie direkt zu pushen**. (Wenn Sie den Push doch versuchen, sollten Sie eine Fehlermeldung bekommen, da ich das pushen erst am Sonntagabend freischalten werde).



## Teil 2

Bitte erledigen Sie Teil 2 **nach Sonntag, 23.04., 21 Uhr** (und vor der nächsten Sitzung am Mittwoch, 26.04.).

### d) Push
Pushen Sie (über das Kontextmenü) ihre Änderungen im `main`-Branch zum Server. Dies sollte einen Merge-Konflikt auslösen. 

### e) Beheben Sie den Merge-Konflikt

Achten Sie dabei darauf, dass Sie eine Version herstellen, in der Ihr Beitrag, und auch der Beitrag aller anderen, erhalten ist -- löschen Sie also nichts.

### f) Commit

Committen Sie ihren Merge, und pushen Sie nochmal. Es besteht die Möglichkeit, dass jetzt ein weiterer Merge-Konflikt auftritt (nämlich wenn in der Zwischenzeit jemand anders gepusht hat). Gehen Sie dann zurück zu e).