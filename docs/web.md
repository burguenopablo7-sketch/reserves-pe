# 🎬 Reserva Cinema 🍿
![Logo](img/logo.png)

Aquesta web permet reservar la teva butaca de cinema en segons des del mòbil: *tria la sessió*, **paga online** i entra amb el teu ***codi QR***. Sense cues, ~~sense taquilla~~, sense riscos.

> El cinema obre de dilluns a diumenge, tots els dies de l'any. La primera sessió comença a les 16:00 h i l'última funció acaba a les 01:00 h.

### Per a l'espectador
Pensat per a qui vol veure una pel·lícula sense fer cua a la taquilla i sense arriscar-se a trobar les entrades esgotades.

#### Reserva en 4 passos
Pel·lícula, sessió, butaca i pagament. Tot es pot fer parlant amb el xat.

##### Pagament i QR
La reserva només queda confirmada després del pagament online. Llavors rebràs el codi QR per entrar directe a la sala.

## Passos

- Tria la **pel·lícula** i la sessió
- Selecciona la butaca al mapa de la sala
- Paga online: la reserva **només es confirma** després del pagament
- Cancel·la o canvia la sessió des de l'app fins a 30 minuts abans

1. L'usuari parla amb el xat
2. El sistema bloqueja la butaca en temps real mentre es fa la compra
3. Si algú altre l'ha triat abans, el xat suggereix seients lliures
4. Arriba el codi QR i s'entra a la sala sense passar per taquilla

## Ocupació de la sala

![Ocupació per sala](img/foto_ejemplo.png)

Ocupació de les sales en una tarda d'exemple. La Sala 3 és la que s'omple abans.

### Mapa de la sala

**Shrek · 18:30 · Sala 3**

📽️ Pantalla 📽️

Fila 1 🟩🟩🟩🟩🟥🟥🟩🟩🟩🟩🟩🟩🟩🟩  
Fila 2 🟩🟥🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩  
Fila 3 🟩🟩🟩🟩🟩🟩🟩🟩🟥🟥🟩🟩🟩🟩  
Fila 4 🟩🟩🟩🟩🟩🟥🟥🟩🟩🟩🟩🟩🟩🟩  
Fila 5 🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟥🟨🟥🟩  
Fila 6 🟩🟩🟥🟩🟩🟩🟩🟥🟩🟩🟩🟩🟩🟩

🟩 Lliure · 🟥 Ocupada · 🟨 La teva butaca (Fila 5, Seient 12)

### La teva entrada

| 🎟️ Entrada | |
| --- | --- |
| Pel·lícula | **Shrek** |
| Data | 18 de setembre |
| Sessió | 18:30 · Sala 3 |
| Butaca | Fila 5, Seient 12 |
| Preu | 8,50 € |
| Accés | Codi QR |

# Xat IA
> 🤖 **Xat:** Hola! 👋 Quina pel·lícula vols veure?
>
> 👤 **Alex:** Shrek
>
> 🤖 **Xat:** Perfecte! 🍿 Sessions: 18:30 (Sala 3), 21:00 (Sala 2), 23:15 (Sala 3). Quina vols?
>
> 👤 **Alex:** La de les 18:30.
>
> 🤖 **Xat:** Quina butaca vols?
>
> 👤 **Alex:** Fila 5, seient 12.
>
> 🤖 **Xat:** ✅ Disponible. El total és de 8,50 €. Per confirmar, fes el pagament online.
>
> 👤 **Alex:** Faig el pagament.
>
> 🤖 **Xat:** 🎉 Reserva confirmada! Aquí tens el teu codi QR.

### Butaca ocupada

> 🤖 **Xat:** Quina butaca vols?
>
> 👤 **Alex:** Fila 5, seient 12.
>
> 🤖 **Xat:** ❌ Aquesta butaca acaba de ser seleccionada per un altre usuari. Et puc oferir: Fila 5 seient 11, Fila 5 seient 13 o Fila 6 seient 12.
>
> 👤 **Alex:** Fila 5, seient 13.
>
> 🤖 **Xat:** ✅ Seleccionada. Per confirmar, fes el pagament online.
>
> 👤 **Alex:** No faig el pagament.
>
> 🤖 **Xat:** Reserva no confirmada. La butaca queda lliure per a un altre usuari.