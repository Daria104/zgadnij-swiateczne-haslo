❄️ Zgadnij Świąteczne Hasło (Power BI)

Świąteczna gra w Power BI polegająca na odgadywaniu ukrytych słów i haseł związanych z Bożym Narodzeniem literka po literce. Gracze wybierają kolejne litery na ekranowej klawiaturze, aby odsłonić hasło, a całość utrzymana jest w zimowej oprawie wizualnej.

✨ Funkcjonalności i oprawa wizualna

Plansza z hasłem (HTML / DAX): Dynamicznie generowane kafelki. Nieodkryte litery ozdobione są wektorowym motywem płatka śniegu, a słowa układają się i centrują automatycznie.
Ekranowa klawiatura (A–Ż): Interaktywny wybór liter z podświetlaniem trafionych i nietrafionych znaków.
System rund i podpowiedzi: Możliwość przełączania się między kolejnymi rundami (1–12), podgląd aktualnej kategorii hasła oraz szybki przełącznik trybu (Ukryte litery / Odkryj całe hasło).
Zimowa atmosfera: Animowane tło z wolno opadającym śniegiem przygotowane w czystym SVG z przezroczystym tłem.
Niestandardowe komponenty UI: Nagłówek gry, kapsuła kategorii oraz przycisk startowy zbudowane w oparciu o kod HTML osadzony w miarach DAX.

<img width="1160" height="646" alt="image" src="https://github.com/user-attachments/assets/d05525d0-614f-452c-8aea-b650e534a221" />
<img width="1157" height="645" alt="image" src="https://github.com/user-attachments/assets/202ba159-fcdc-4d3d-886e-a88a89f7a529" />



🚀 Jak uruchomić projekt?

Pobierz plik .pbix z folderu pbix/ i otwórz go w programie Power BI Desktop.
Upewnij się, że w raporcie załadowana jest wizualizacja niestandardowa HTML Content (z AppSource), która odpowiada za renderowanie planszy, nagłówka oraz przycisku startowego.
Aby dodać własne hasła, edytuj tabelę źródłową bezpośrednio w Power Query i kliknij Odśwież w Power BI Desktop.
Przejdź w tryb pełnoekranowy (lub opublikuj raport w usłudze Power BI) i rozpocznij zabawę!

🛠️ Wykorzystane technologie

Microsoft Power BI Desktop (model danych, fragmentatory, zakładki i nawigacja)
DAX (logika odkrywania liter oraz dynamiczne generowanie kodu HTML)
HTML5 & CSS3 (stylowanie kafelków, gradienty, poświaty i układ planszy)
SVG (wektorowe płatki śniegu oraz wielowarstwowa animacja opadającego śniegu)
