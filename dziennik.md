Dziennik projektu — Temat 1: Rdzeń sieci 5G (SBA)



Autor: Roman Akhunjanov  

Numer indeksu: 71691  





1\. Lista komunikatów (sekwencja "Włączanie telefonu w 5G")



Poniżej znajduje się lista komunikatów w kolejności, w jakiej zostały przekazane między karteczkami (zgodnie z diagramem sekwencji):



1\. Telefon → Wieża (gNB) "witaj, jestem tu"

2\. Wieża (gNB) → AMF: "nowy telefon się pojawił"

3\. AMF → Baza danych abonentów "czy znam tego abonenta?"

4\. Baza danych abonentów → AMF: "tak, to Jan" (w diagramie: "tak, to User")

5\. AMF → SMF: "zestaw sesję internetową"

6\. SMF → Internet "łącze gotowe"



2\. Pytania, które się pojawiły



W trakcie ćwiczenia z makietą karteczkową i tworzenia diagramu pojawiły się następujące pytania:



\- Czy komunikacja między telefonem a wieżą (gNB) a AMF odbywa się zawsze w tej samej kolejności?

\- Co się stanie, jeśli baza danych abonentów odpowie "nie znam tego abonenta"?

\- Czy AMF zawsze musi pytać bazę danych, czy może mieć własny cache?

\- Jak dokładnie wygląda różnica między sygnalizacją a ruchem użytkownika (user plane vs control plane)?

\- Czy SMF zawsze komunikuje się bezpośrednio z Internetem, czy przez dodatkowe bramki (UPF)?

\- Co oznacza skrót SBA i jakie ma znaczenie dla architektury 5G?



3\. Propozycja podziału ról w zespole



Wszystkie zadania i role w projekcie wykonał samodzielnie:



Roman Akhunjanov (nr indeksu: 71691)





4\. Wynik dnia



\- Diagram sekwencji "Włączanie telefonu w 5G" (eksport do PNG) — wykonany przez Romana Akhunjanova.

\- Dziennik projektu (`dziennik.md`) — prowadzony przez Romana Akhunjanova

