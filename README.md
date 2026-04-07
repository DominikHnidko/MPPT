# Przetwornica i sterowanie z mppt => controller mppt do paneli PV


## Opis projektu
Projekt jest w trakcie realizacji, obecnie na etapie schematu. Pliki zawierają konkretny scheamt controllera MPPT.
Docelowe urządzenie realizować będzie algorytm P&O do ciągłego monitorowania maksimów na krzywej panelu PV.
Rozważane jest wdrożenie innego algorytmu, aby usprawnić proces i odnajdywać nie tylko maksima lokalne, ale i globalne.

Na schemacie w oddzielnym Sheet przedstawiony jest układ pomiaru rezystancji wewnętrznej baterii.

Przy zastosowaniu tranzystorów GaN planowane jest osiągnięciu małych rozmiarów końcowej płytki.

Mikrokontroler ESP32 pozwala na wdrożenie telemetrii i zdalnego monitorowania parametrów ładowania.

Po wykryciu rezystancji wewnętrznej baterii można wnioskować jaki rodzaj ogniwa jest podłączony i zastosować charakterestyczne krzywe ładowania do każdego rodzaju ogniw.

---

![Opis obrazka](image.png)
