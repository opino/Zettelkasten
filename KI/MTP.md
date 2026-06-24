# MTP Multi Token Prediction

## wie funktioniert die Vorhersage?

Ein wenig rechenintensives Draft Modell sagt 3 Tokens voraus, welche vom Target überprüft und einen weiteren Token vorhersagt.
Damit hat das Target Modell 4 Token in einem Durchlauf erzeugt. Die erzeugten 4 Token werden als Kontext im Drafter Modell benutzt um die 
nächsten Token zu erzeugen.
