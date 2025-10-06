# 🔌 Tasca 2 – Selecció d’un SAI per a una empresa client

## 🧾 Descripció del cas
L’empresa **TecnoGestió S.L.**, dedicada a la gestió documental i a l’assessorament informàtic, té un petit despatx amb **4 ordinadors de sobretaula**, una **impressora-fotocopiadora multifunció** (similar a les que té l’escola) i un **router d’accés a Internet**.  

Davant les constants incidències amb el subministrament elèctric a la zona, la direcció ha decidit adquirir un **SAI (Sistema d’Alimentació Ininterrompuda)** per garantir la continuïtat del servei i protegir els equips.  

S’han posat en contacte amb l’empresa on esteu fent l’estada i el vostre responsable us ha encarregat que en feu **l’estudi i la tria del SAI**.

---

## 🖥️ Inventari d’equips

| Equip                          | Quantitat | Potència (W) | Potència total (W) |
|--------------------------------|------------|---------------|--------------------|
| Ordinadors de sobretaula       | 4          | 200           | 800                |
| Monitors LED 24’’              | 4          | 30            | 120                |
| Router                         | 1          | 15            | 15                 |
| **Total consumat**             | —          | —             | **935 W**          |

> ⚠️ **Nota:** No es connecta la impressora multifunció al SAI, ja que té consums puntuals molt elevats i **no és un equip crític** per al funcionament del despatx.

---

## ⚡ Càlcul de potència

- **Consum total:** 935 W  
- **+20% de reserva:** 1.122 W  
- **Factor de potència (FP):** 0,9  
- **Potència aparent necessària:**  
  \[
  1.122\text{ W} ÷ 0,9 = 1.247\text{ VA}
  \]  
- Es recomana un **SAI de 2000–2200 VA** per tenir marge suficient.

---

## ⏱️ Autonomia necessària

L’autonomia mínima requerida és de **10 minuts**, per permetre desar els treballs i apagar correctament els equips en cas de tall elèctric.

| Equip connectat                          | Potència estimada | Autonomia mínima requerida |
|------------------------------------------|--------------------|----------------------------|
| 4 ordinadors + 4 monitors + router       | 1.122 W (amb reserva 20%) | 10 minuts                 |

---

## 🔍 Models analitzats

| Model                       | Potència (VA / W) | Autonomia aproximada | Observacions |
|------------------------------|--------------------|-----------------------|---------------|
| **CyberPower CP1500EPFCLCD** | 1500 VA / 900 W   | 2–5 min a 1.100 W     | Insuficient per la nostra càrrega. |
| **APC Smart-UPS SMT2200**    | 2200 VA / 1980 W  | >10 min a 1.100 W     | Adequat, bona gestió, fiabilitat i marge de creixement. |
| **Eaton 5P 2200**            | 1950–2200 VA / 1920 W | 8–15 min a 1.100 W  | Bona eficiència, ampliable amb mòduls externs. |

---

## ✅ Solució final

Es **recomana el model [APC Smart-UPS SMT2200 (2200 VA)](https://www.apc.com/)** perquè:  
- Cobreix la potència total amb la reserva de seguretat.  
- Garanteix **més de 10 minuts d’autonomia** amb la càrrega actual.  
- Ofereix **gestió professional via software** i **possibilitat d’ampliació futura**.  
- Té **alta fiabilitat** i un **bon equilibri entre potència, autonomia i preu**.

---

## 📚 Material de suport
- **Apunts:** RA1AA3 – *El SAI (Sistema d’Alimentació Ininterrompuda)*

---

> 💡 **Conclusió:**  
> El model **APC Smart-UPS SMT2200** és la millor opció per a TecnoGestió S.L., ja que garanteix protecció, autonomia i escalabilitat, assegurant la continuïtat del servei davant qualsevol interrupció elèctrica.


![Foto relacionada](img/imatge01.png)

[Tornar a enunciat](README.md)
