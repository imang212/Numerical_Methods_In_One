# Numerické metody v R
Tenhle report obssahuje vsechny Numericke metody a jejich popis v R, co jsme probírali na předmětu NUM a zadání z NUM.

#### 1. Řešení soustav lineárních rovnic
- Gaussova metoda
<img width="573" height="332" alt="image" src="https://github.com/user-attachments/assets/5ce509b3-a11d-47ae-bc4a-9540f25ec9c7" />

- metoda LU dekompozice
<img width="563" height="280" alt="image" src="https://github.com/user-attachments/assets/852867d3-185e-48c2-90e4-abe85b975c76" />

- Jacobiova metoda
<img width="599" height="125" alt="image" src="https://github.com/user-attachments/assets/a15920ae-deb1-49cb-a76c-abdaa3330826" />

- Gauss-seidelova metoda
<img width="546" height="151" alt="image" src="https://github.com/user-attachments/assets/2071d04f-b71f-47dd-b5f4-7008b18c82e3" />


#### 2. Interpolace (přesné proložení bodů)
- Lineární interpolace po částech
- Lagrangeova interpolace (polynomem)
- Newtonova interpolace (polynomem) 
- Vandermondova interpolace (výpočet koeficientů polynomu)
- Hornerovo schéma (vyhodnocení polynomu)
- Hermitova interpolace (polynom s derivacemi)

#### 3. Aproximace (hledání přibližné funkce pro danou závislost, nemusí procházet body)
- metoda nejmenších čtverců (nalezení koeficientů aproximovaného polynomu)
- Hornerovo schéma (vyhodnocení polynomu)

#### 4. Numerické derivace
- Dopředná/zpětná diference (I. diference)
- centrální diference (I. a II. diference)
- Richardsonova extrapolace

#### 5. Numerická integrace
- Obdelníkové pravidlo (Trapezoid rule) - nízká
- Midpoint rule  - střední
- Lichoběžníkové pravidlo - sřední
- Simpson's rule - vysoká
- Simpson's 3/8 rule - vysoká
- Booleovo pravidlo - velmi vysoká
- Monte carlo metoda - střední
- Gaussova kvadratura (výpočet hodnoty integrálu) - velnmi vysoká
- Rombergova metoda
- Horner (integrace polynomu)

#### 6. Numerické řešení obyčejných diferenciálních rovnic
- Eulerova metoda - nízká
- Runge kutta metody - vysoká

#### 7. Řešení nelineárních rovnic (hledání kořene funkce)
- Newtonova metoda tečen (nutná I. derivace)
- Steffensonova metoda (derivace se nahrazuje přibližným odhadem, nepotřebuje derivaci)
- Halleyova metoda (Rozšíření Newtonovy metody - používá I. a II. derivaci)
- Chebyshevova metoda (potřebuje I. a II. derivaci)
- Metoda Bisekce (půlení intervalu, bez derivace)
- Regula-falsi metoda (vylepšení bisekce)
- Newton-Hornerova metoda (výpočet polynomu, používá hodnotu a derivaci polynomu)
- Metoda prostých iterací (nejjednodušší přístup)
- Monte carlo metoda (bez derivace pr ohrubý odhad)
