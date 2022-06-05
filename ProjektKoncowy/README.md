Projekt Koncowy Wizualizacja Danych

Segmentacja obrazow MRI  podstawie DATASET z kaggle.com

Pobieramy Dane z pliku .csv o pacjentach, pliki ze zdjeciami z maszyny wirtualnej z kaggle.com.
Pliki sa podzielone na folder zdjec bez oraz z maska.

Zdjecia MRI zapisane sa w formacie .tiff ( Tag Image File Format, is a computer file used to store raster graphics and image information.)

Maska na czesci pikseli wyroznia obszar obecnosci guza.

Najpierw Obrazki Poddajemy Segemntacji w celu nalozenia masek na zdjecia i pokazania zdjec z obszarami ze zmianami pokazujacymi guza mozgu.

Nastepnie tworzymy Train Set oraz Test Set i trenujemy model deep learningowy.

Sprawdzamy Model U-NET oraz Model Tversky do prognozowania diagnozy guza mozgu.

Model U-NET overview:

https://pyimagesearch.com/2022/02/21/u-net-image-segmentation-in-keras/



