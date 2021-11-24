# **Rozwiązania - wytyczne**

**Wytyczne ogólne**

1. Zgłoszeniu do oceny podlega rozwiązanie jednego, wybranego zadania spośród zadań 2-4.
2. Niezależnie od wyboru zadania rozwiązanie zgłoszone do oceny powinno znaleźć się w pojedynczym pliku stanowiącym archiwum ZIP.
3. Nazwa archiwum ZIP powinna być zgodna z formatem:
    - w przypadku studentów pracujących w zespole: `xx_yy_zadN.zip`, gdzie:
        1. `xx` - inicjały pierwszego członka zespołu (osoby, której nazwisko występuje wcześniej w porządku alfabetycznym);
        2. `yy` - inicjały drugiego członka zespołu (osoby, której nazwisko występuje później w porządku alfabetycznym);
        3. `N` - numer zadania;
    - w przypadku studenta pracującego samodzielnie: `xx_zadN.zip`, gdzie:
        1. `xx` - inicjały studenta;
        2. `N` - numer zadania.

    Inicjały powinny zostać wpisane małymi literami, a ewentualne polskie znaki diakrytyczne w nich występujące powinny zostać zastąpione ich łacińskimi odpowiednikami.

4. Zgłoszenie rozwiązania do oceny wymaga potwierdzenia jego przesłania (poprzez kliknięcie odpowiedniego przycisku na formularzu podczas wgrywania rozwiązania). Brak takiego potwierdzenia powoduje, że wgrane rozwiązanie pozostaje oznaczone jako tzw. wersja robocza, co będzie traktowane jako niezgłoszenie rozwiązania - rozwiązanie takie nie będzie podlegało sprawdzeniu (i w efekcie może to doprowadzić do utraty terminu).
5. Zgłoszenie rozwiązania, które nie będzie spełniało wszystkich wytycznych, będzie oznaczało konieczność wykonania ponownego zgłoszenia poprawionej wersji, co będzie się wiązać z obniżeniem oceny o 0,5 (za każdym razem, gdy zgłoszone rozwiązanie nie będzie spełniać wszystkich wytycznych).
6. W przypadku zespołów dwuosobowych obowiązek zgłoszenia rozwiązania dotyczy każdego z członków zespołu. Za datę zgłoszenia rozwiązania przyjmuje się w tej sytuacji datę zgłoszenia przez tego członka zespołu, który uczynił to później.

**Wytyczne szczegółowe - zadanie 4**

1. Archiwum ZIP powinno zawierać wyłącznie pojedynczy plik w formacie notatnika Jupyter stanowiący rozwiązanie zadania.
2. Plik w formacie notatnika Jupyter powinien znajdować się na najwyższym poziomie w archiwum. W szczególności na najwyższym poziomie w archiwum **nie** powinien znaleźć się katalog o nazwie `xx_zadN` lub `xx_yy_zadN` (gdzie `xx` i `yy` oznaczają inicjały studenta, a `N` - numer zadania).
3. Plik w formacie notatnika Jupyter powinien nazywać się `analysis.ipynb`.
4. Należy zadbać o to, by w pliku `analysis.ipynb` znalazły się wszystkie wykresy tworzone w ramach analizy (tylko zamieszczone wykresy będą podlegać ocenie!). Dodatkowo zaleca się, żeby przed ostatecznym zapisaniem notatnika zrestartować jądro i uruchomić od nowa kod we wszystkich komórkach po kolei (_Kernel > Restart & Run All_), tak aby numery przy następujących po sobie komórkach występowały w rosnącym porządku.