# Algorithmique-et-pseudo-code
DEDUT
 
 VARIABLE
 (réel A (argents), réel b (nombre de bonbon), réel P (prix du bonbon) , réel I (variable temporaire)

 Algorithme
 Si  A < 0 retourner  " Pas de bonbon! "
 Si  P < 0 retourner  " Erreur de prix !"
 Sinon
 I <- A diviser par P
 si I < 1 retourner " Pas de bonbon! "
 sinon 
 b=1
  Pour I <- I-1 et tant que I > 1 , faire b <- b+1
  Fin Pour
 Retourner  " On peux acheter " b " bonbons. " 
