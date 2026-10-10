# Pactum_Public
Weryfikacja wersji programu Pactum

## Gdzie Pactum czyta wypisy

![Mapa powiatów, z których urzędów Pactum czyta wypisy z rejestru gruntów](mapa/mapa-powiatow.svg)

Na pomarańczowo — powiaty, z których urzędów program wczytał już prawdziwe wypisy
z rejestru gruntów. Mapę można też [przybliżać i klikać](mapa/mapa-powiatow.geojson).

| Województwo | Urząd wydający wypis |
|---|---|
| dolnośląskie | Starosta Bolesławiecki |
| dolnośląskie | Starosta Jaworski |
| dolnośląskie | Starosta Lubiński |
| dolnośląskie | Starosta Polkowicki |
| dolnośląskie | Starosta Powiatu Wrocławskiego |
| dolnośląskie | Starosta Ząbkowicki |
| dolnośląskie | Starosta Złotoryjski |
| dolnośląskie | Prezydent Wrocławia |
| dolnośląskie | Prezydent Miasta Wałbrzycha |
| zachodniopomorskie | Starosta Koszaliński |
| zachodniopomorskie | Starosta Szczecinecki |
| zachodniopomorskie | Prezydent Miasta Szczecin |

Szary powiat nie znaczy, że wypis się nie wczyta. Program rozpoznaje **układ wydruku**,
a nie nazwę urzędu, a wiele starostw drukuje wypisy tym samym oprogramowaniem.
Jeśli wypis się nie wczyta, program pokaże w Uwagach „Nie rozpoznano układu wypisu” —
wtedy wystarczy dać znać autorowi programu, a nowy urząd trafi na tę mapę.

<sub>Stan na wersję 1.4.2 (10.10.2026). Granice powiatów: Państwowy Rejestr Granic,
Główny Urząd Geodezji i Kartografii, w przeliczeniu z
[ppatrzyk/polska-geojson](https://github.com/ppatrzyk/polska-geojson) (MIT).</sub>
