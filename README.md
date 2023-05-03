# Deflation-with-GIvens-Rotations
Main function is P2Z35_SPR_rotivens

Przybliżanie tylu wartości własnych λ1, λ2,..., λs macierzy A, gdzie |λ1| > |λ2| > ... > |λs| na ile pozwalają podane parametry. Deflacja za pomocą złożenia n-1 obrotów Givensa. Metoda jest iteracyjna, dlatego przyjmuje parametry dotyczące żądanej dokładności, oraz maksymalnej liczby iteracji.
Wejście:
   A       - macierz kwadratowa, której wartości własne są szukane
   prec    - dokładność z jaką mają być wyznaczane wartości własne
   m       - maksymalna ilośc iteracji dla wyznaczania pojedynczej
             wartości włanej
 Wyjście:
   vec     - wektor wyznaczonych wartości własnych
