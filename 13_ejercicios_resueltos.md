
# Ejercicios Resueltos (Matemática Financiera - Colombia)

## 1. Introducción

En esta sección se presentan ejercicios resueltos paso a paso para reforzar los conceptos vistos en:

- Valor del dinero en el tiempo
- Interés simple y compuesto
- Conversión de tasas
- Anualidades
- Amortización
- Descuento financiero
- Inflación y tasa real

> Recomendación: antes de resolver, identifica siempre **VP, VF, i, n** y la **frecuencia** de la tasa.

---

## Ejercicio 1: Interés simple (corto plazo)

**Enunciado:**  
Una persona presta $3.500.000 COP a interés simple del 2% mensual durante 6 meses.  
Calcular el interés y el valor futuro.

**Datos:**
- VP = 3.500.000
- i = 0.02 mensual
- n = 6 meses

**Interés:**
I = VP × i × n  
I = 3.500.000 × 0.02 × 6  
I = 420.000

**Valor futuro:**
VF = VP + I  
VF = 3.500.000 + 420.000  
VF = 3.920.000 COP

---

## Ejercicio 2: Interés compuesto (anual)

**Enunciado:**  
Se invierten $5.000.000 COP al 14% EA durante 3 años.  
Calcular el valor futuro.

**Datos:**
- VP = 5.000.000
- i = 0.14 anual
- n = 3

**Cálculo:**
VF = VP (1 + i)^n  
VF = 5.000.000 (1.14)^3  
VF = 5.000.000 (1.481544)  
VF ≈ 7.407.720 COP

---

## Ejercicio 3: Conversión de tasa (EA a mensual)

**Enunciado:**  
Convertir una tasa del 24% EA a tasa efectiva mensual.

**Datos:**
- i_EA = 0.24
- m = 12

**Cálculo:**
i_m = (1 + i_EA)^(1/12) − 1  
i_m = (1.24)^(1/12) − 1  
i_m ≈ 0.0181 = 1.81% mensual

---

## Ejercicio 4: Valor presente (descuento racional)

**Enunciado:**  
¿Cuánto vale hoy recibir $12.000.000 COP dentro de 2 años si la tasa es 16% EA?

**Datos:**
- VF = 12.000.000
- i = 0.16
- n = 2

**Cálculo:**
VP = VF / (1 + i)^n  
VP = 12.000.000 / (1.16)^2  
VP = 12.000.000 / 1.3456  
VP ≈ 8.915.000 COP

---

## Ejercicio 5: Valor futuro de una anualidad (vencida)

**Enunciado:**  
Una persona ahorra $400.000 COP al final de cada mes durante 18 meses en una cuenta que paga 1.2% mensual.  
Calcular el valor futuro.

**Datos:**
- C = 400.000
- i = 0.012 mensual
- n = 18

**Cálculo:**
VF = C × [ ((1 + i)^n − 1) / i ]  
VF = 400.000 × [ ((1.012)^18 − 1) / 0.012 ]

(1.012)^18 ≈ 1.2408  
VF = 400.000 × [ (1.2408 − 1) / 0.012 ]  
VF = 400.000 × (0.2408 / 0.012)  
VF = 400.000 × 20.0667  
VF ≈ 8.026.680 COP

---

## Ejercicio 6: Valor presente de una anualidad (cuota de un crédito)

**Enunciado:**  
Un crédito requiere pagar cuotas mensuales de $950.000 COP durante 24 meses.  
La tasa es 1.5% mensual.  
Calcular el valor presente del crédito (monto financiado aproximado).

**Datos:**
- C = 950.000
- i = 0.015
- n = 24

**Cálculo:**
VP = C × [ (1 − (1 + i)^(-n)) / i ]  
VP = 950.000 × [ (1 − (1.015)^(-24)) / 0.015 ]

(1.015)^24 ≈ 1.4293  
(1.015)^(-24) ≈ 1 / 1.4293 ≈ 0.6997

VP = 950.000 × [ (1 − 0.6997) / 0.015 ]  
VP = 950.000 × (0.3003 / 0.015)  
VP = 950.000 × 20.02  
VP ≈ 19.019.000 COP

---

## Ejercicio 7: Tasa real (inflación Colombia)

**Enunciado:**  
Una inversión ofrece 13% EA y la inflación anual es 8% (aprox.).  
Calcular la tasa real aproximada y la tasa real con Fisher.

### A) Aproximación:
i_real ≈ i_nominal − inflación  
i_real ≈ 13% − 8% = 5%

### B) Fisher:
i_real = [(1 + i_nominal)/(1 + inflación)] − 1  
i_real = (1.13/1.08) − 1  
i_real ≈ 1.0463 − 1  
i_real ≈ 4.63%

---

## Ejercicio 8: Equivalencia financiera (reemplazo de pagos)

**Enunciado:**  
Una empresa debe pagar $4.000.000 hoy y $4.500.000 en 1 año.  
Quiere reemplazarlo por un solo pago en 1 año.  
Tasa: 12% EA.

**Paso 1:** Llevar el pago de hoy a 1 año:

VF1 = 4.000.000 (1.12)  
VF1 = 4.480.000

**Paso 2:** Sumar el pago futuro:

Pago equivalente en 1 año = 4.480.000 + 4.500.000  
Pago equivalente en 1 año = 8.980.000 COP

---

## Conclusión

Estos ejercicios muestran cómo aplicar la matemática financiera para:

- Evaluar créditos e inversiones
- Convertir tasas correctamente
- Calcular valores presentes y futuros
- Entender el efecto real de la inflación
- Comparar alternativas financieras con equivalencia
