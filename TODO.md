# TODO
- [ ] Mozliwosc wgrywania modelu i artifact clusters
- [ ] Zbierać warstwy tylko z określonych predykcji np. 1 -> przyspieszenie pracy
- [X] zamienić agglomerative clustering na inną metodę klasteryzacji
- [X] zmienić biblioteki z agglomerative na szybsze np. [fastcluster](https://github.com/dmuellner/fastcluster)
- [X] spróbować z agglomerative clustering z cuML
- [ ] eksperymenty z siecią neuronową
- [ ] zaimplementować notebook z możliwością wyświetlenia większej ilością filtrów 

# UWAGI i WNIOSKI
- modele wgrywane z dysku po zapisaniu dają bardzo słabe wyniki
- o4 i o4-mini-high znacznie lepiej radzi sobie gdy ontologie wkleic jako tekst, niz jako załącznik
- lepiej radzi sobie z przedstawienie artefaktów jeśli jest ich kilka, a nie tylko jeden
- warstwy aktywacji za bardzo się na siebie nakładają, być może potrzeba więcej klastrów
- przy rozbiciu na 10 klastrów - wyniki dużo lepsze - np. klaster drugi zbiera 2

x_train[predictions,:,:]
predictions = predictions[predictions==8]

Tabela:
- wiersze -> obraz
- kolumny -> cechy (mogą być binarnie)


Klasy C1, C2 i poziomy ogólności od szczegółu do ogółu