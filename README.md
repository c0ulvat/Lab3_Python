# AZTU Dərs Yoxlama Skripti

Bu Python skripti AZTU-nun tələbə portalına daxil olaraq, seçilmiş Python kursunun dərs qeydiyyat məlumatlarını çıxarmağa imkan verir. Script avtomatik olaraq daxil olma prosesini həyata keçirir, menyulardan keçərək python kursuna çatır və təqdim olunan tarixlər üzrə dərs iştirak məlumatlarını ("i/e" - iştirak edib, "q/b" - iştirak etməyib) çıxarır.

## Tələblər

*   Python 3
*   Aşağıdakı Python kitabxanaları:
    *   `selenium` (`pip install selenium`)
    *   `beautifulsoup4` (`pip install beautifulsoup4`)

## İstifadə

1.  Virtual mühit yaratın (tövsiyə olunur):

    ```bash
    python -m venv aztu_yoxlama
    ```

2.  Virtual mühiti aktivləşdirin:

    *   Linux/MacOS:

        ```bash
        source aztu_yoxlama/bin/activate
        ```

    *   Windows:

        ```bash
        aztu_yoxlama\Scripts\activate
        ```

3.  Lazımlı kitabxanaları quraşdırın:

    ```bash
    pip install selenium beautifulsoup4
    ```

4.  Skripti işə salın:

    ```bash
    python aztu_ders_yoxlama.py
    ```

   Skript sizdən istifadəçi adınızı və şifrənizi daxil etməyi tələb edəcək. Daxil etdikdən sonra, əgər daxıl olma müvəffəqiyyətli olarsa, script seçilmiş Python kursunun mövcud dərs iştirak məlumatlarını tarix və status (“iştirak edib” və ya “iştirak etməyib”) şəklində göstərəcəkdir.

## Qeydlər

*   Script avtomatik olaraq AZTU tələbə portalına daxil olma prosesini həyata keçirir, ancaq təhlükəsizlik məqsədləri ilə istifadəçi adınızı və şifrənizi öz məsuliyyətinizdə saxlamaq tövsiyə olunur.
*   Script internet bağlantınızın sürətinə və AZTU tələbə portalının cavab müddətinə görə fərqli işləyə bilər. Gərək duyulduqda, gözləmə müddətlərini (.sleep()) tənzimləyə bilərsiniz.
*   AZTU tələbə portalının quruluşu dəyişdikdə script işləməməsi ehtimalı var. Bu cür hallarda kodun yenilənməsi lazım ola bilər.

## Müəllif Hüquqları

Bu skript açıq mənbəlidir və MIT Lisensiyası ilə yayımlanır. Sərbəst istifadə edə, dəyişə və ya paylaya bilərsiniz.
