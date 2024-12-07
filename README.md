# **Esempio ULTRA semplice di PySimpleGUI**
## **Usage:**
0) Creare/attivare un ambiente virtuale Python
1) Installare i requisiti 
   ```sh
   pip install -r requirements.txt
   # or with mini-conda
   conda install --yes --file requirements.txt
   ```
2) Lanciare il codice Python
   ```sh 
   python main.py
   ```
   - (Eventuale) Modificare il file `main.py` a piacimento
3) Creare l'eseguibile/binario (funziona sia su Windows che su Linux)
   ```sh 
    pyinstaller main.py --onefile
   ``` 
   Questo creerà una cartella `dist` con all'interno un file eseguibile `main` su Linux o `main.exe` su Windows.
4) Il file può essere eseguito senza bisogno di installare Python.

## **Disclaimer**
**PySimpleGUI** è open source fino alla versione 4 (qui usata).
Dalla versione 5 hanno aggiunto una licenza (per quanto gratuita)