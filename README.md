# sudoku-solver

In diesem Jupyter Notebook soll zuerste auf einem Bild ein Sudoku erkennt werden. Zusätzlich werden die Zahlen ausgelesen.
Ein CNN Modell klassifiziert, ob die Zahlen handgeschrieben sind, denn dann wurde das Sudoku bereits versucht zu lösen und diese Zahlen könnten falsch sein.
Alle nicht handgeschriebenen Zahlen werden in ein CP Modell importiert und die Lösung wird berechnet, welche dann wieder in das Bild projiziert wird.
