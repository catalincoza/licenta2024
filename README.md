# Proiect Licenta 2024 - Analiza Defrisare cu Machine Learning

Doar fisierele principale din proiect sunt prezente pentru vizualizare, intrucat seturile de date sunt imense si nu ar avea sens sa fie adaugate in repo.
Toate output-urile din notebook-uri au fost salvate.
Continutul fisierelor:
- get-data.ipynb - Preluarea pe benzi (B04, B03, B02 - True Color) a fragmentelor din fisierele preluate de pe Copernicus Browser (Sentinel-2A) a muntilor Carpati
- label-data.ipynb - Procesarea fragmentelor obtinute si sortarea lor pe label-uri: deforestation si not_deforestation
- model_training.ipynb - Crearea si antrenarea unui model ResNet50 pe setul de date "Planet: Understanding the Amazon from Space" preluat de pe Kaggle, cat si testarea lui pe fragmentele sortate anterior. De asemenea contine statisticile si rezultatele antrenarii si testarii acestui model
- resnet50.pkl - Modelul antrenat, in format 'pickle'
