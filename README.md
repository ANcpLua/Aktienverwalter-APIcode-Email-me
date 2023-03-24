# StockHandler-UE1-BIF-DUA-2-SS2023-ALGOS-DE

Alexander Nachtmann und Stephanie Rauscher
ÜBUNG 1 - HASHTABELLE aka Aktienverwaltungsprogramm

After downloading the .zip extract the files, press the .exe and it should work. If it does not follow the steps below.

Environment PyCharm 2022.3.3
Manual:
1. Download zip by pressing on the green [<> Code] after it finished download drag its content into PycharmProjects
2. Open Pyhcharm select StockHandler-UE1-BIF-DUA-2-SS2023-ALGOS-DE-main under Projects
3. Press STRG+ALT+S a window will open where you type interpreter into the top left box
4. Click on Add Interpreter and select Add Local Interpreter
5. Under Virtualevn Environment select Base interpreter Python310 and click on ok, 38+ should work also
6. Click on the "+" -- above Package,below Python Interpreter-- and type colorama into the input box, click on it and install package located bottom left
7. Close the Available Package window and click on Apply and ok inside the settings window. After that you should be setup and ready 
8. Press Shift+F10 to start (recommend to change the hotkey 1.press STRG+ALT+S 2.type run b into the searchbox  3.right click run and select add keyboard shortcut)

Das Programm wird über folgende Menüpunkte gesteuert:
1. ADD: Eine Aktie mit Namen, WKN und Kürzel wird hinzugefügt.
2. DEL: Aktie wird gelöscht.
3. IMPORT: Kurswerte für eine Aktie werden aus einer csv Datei importiert
4. SEARCH: Eine Aktie wird in der Hashtabelle gesucht (Eingabe von Namen oder Kürzel) und der aktuellste Kurseintrag (Date,Open,High,Low,Close,Volume,Adj Close) wird ausgegeben.
5. PLOT: Die Schlusskurse der letzten 30 Tage einer Aktie werden als ASCII Grafik ausgegeben, Format ist frei wählbar.
6. SAVE <filename>: Programm speichert die Hashtabelle in eine Datei ab
7. LOAD <filename>: Programm lädt die Hashtabelle aus einer Datei
8. QUIT: Programm wird beendet


Any questions you can contact me on Discord Alex22#8812
