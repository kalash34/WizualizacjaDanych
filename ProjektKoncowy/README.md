Projekt Koncowy Wizualizacja Danych

Segmentacja obrazow MRI  podstawie DATASET z kaggle.com

Pobieramy Dane z pliku .csv o pacjentach, pliki ze zdjeciami z maszyny wirtualnej z kaggle.com.
Pliki sa podzielone na folder zdjec bez oraz z maska.

Zdjecia MRI zapisane sa w formacie .tiff ( Tag Image File Format, is a computer file used to store raster graphics and image information.)

Maska na czesci pikseli wyroznia obszar obecnosci guza.

Najpierw Obrazki Poddajemy Segemntacji w celu nalozenia masek na zdjecia i pokazania zdjec z obszarami ze zmianami pokazujacymi guza mozgu.

Nastepnie tworzymy Train Set oraz Test Set i trenujemy model deep learningowy.

Sprawdzamy Model U-NET do prognozowania diagnozy guza mozgu.

Model U-NET overview:

https://pyimagesearch.com/2022/02/21/u-net-image-segmentation-in-keras/


Do modelu U-NET piszemy funkcje utraty Tversky'ego. ( Wstawiamy do wzoru ).
Zastosowalem ja bo stosuje sie ja powszechnie w Segmentacji Obrazow Medycznych.

https://paperswithcode.com/paper/tversky-loss-function-for-image-segmentation

https://medium.com/@junma11/loss-functions-for-medical-image-segmentation-a-taxonomy-cefa5292eec0

https://www.arxiv-vanity.com/papers/1803.11078/#:~:text=To%20define%20the%20Tversky%20loss,i%20be%20a%20non%2Dlesion.



