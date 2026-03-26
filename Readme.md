Sistem Inteligent pentru Analiza Fază VAR în Fotbal

Descriere generală
Acest proiect dezvoltă un sistem inteligent capabil să analizeze faze controversate din fotbal (faulturi, offside, henț etc.) folosind tehnici de procesare video și învățare automată. Scopul este de a sprijini procesul decizional VAR prin identificarea automată a unor evenimente relevante.

 Sursa datelor
Setul de date utilizat provine de pe Kaggle:

Link: https://www.kaggle.com/datasets/sauravjoshi23/fifa-video-assistant-referees-var  

Acest dataset conține clipuri video etichetate cu diverse evenimente din fotbal (faulturi, goluri, pase, tackling etc.), utile pentru antrenarea unui model de clasificare video.

Obiectivul proiectului

Obiectivul principal este:

Să clasific automat fazele dintr-un meci de fotbal pentru a identifica evenimente relevante pentru analiza VAR, precum:
- Faulturi
- Henț
- Offside (prin analiză pozițională)
- Contact fizic suspect
- Situații de potențial cartonaș

Modelul va primi ca input un clip video scurt și va returna tipul de eveniment detectat.

 Tehnologii utilizate
Proiectul folosește următoarele tehnologii:

Limbaj de programare
- Python 

Biblioteci principale
- **pandas** – manipularea datelor
- **numpy** – operații numerice
- **opencv-python** – procesare video
- **matplotlib / seaborn** – vizualizări
- **scikit-learn** – modele clasice ML
- **tensorflow / keras** – rețele neuronale pentru clasificare video
- **pytorch** (opțional) – alternative pentru modele 3D CNN sau Transformers
- **moviepy** – extragerea cadrelor din videoclipuri


Funcționalități planificate
- Detectarea automată a evenimentelor din videoclipuri
- Clasificarea fazelor relevante pentru VAR
- Vizualizarea cadrelor cheie
- Generarea unui raport automat pentru fiecare clip analizat
