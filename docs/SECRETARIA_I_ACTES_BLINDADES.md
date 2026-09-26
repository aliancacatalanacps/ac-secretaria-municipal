# 📜 PROTOCOL DE SECRETARIA POLÍTICA I ACTES BLINDADES
**Aliança Catalana (AC) — Castell-Platja d'Aro i S'Agaró (CPS)**  
*Normativa interna de funcionament de reunions, actes i registre oficial d'acords.*

---

## 1. Objectiu del Protocol

En un projecte polític seriós i en creixement com el d'Aliança Catalana, la cohesió interna i la claredat dels acords són pilars fonamentals. Per evitar malentesos, desacords sobre *"qui va dir què"* o modificacions posteriors d'acords presos, s'estableix el procediment de **Secretaria amb Actes Blindades i Immutables**.

---

## 2. El Cicle de la Reunió de Secretaria

```
1. Ordre del dia previ (24h abans)
        │
        ▼
2. Gravació d'àudio durant la sessió (Micròfon / Arxiu extern)
        │
        ▼
3. Transcripció automàtica i generació d'Esborrany
        │
        ▼
4. Fase de revisió i esmenes (Editable)
        │
        ▼
5. Aprovació, Segellat Criptogràfic i Blindatge Permanent (IMMUTABLE)
```

---

## 3. Fase 1: Gestió de l'Ordre del Dia
- El Secretari o persona delegada confecciona l'ordre del dia seguint la regla 50/25/25.
- Cada punt conté:
  - Títol clar del tema.
  - Eix estratègic (*Programa*, *Executiva/Xarxes*, *Ple/Dia a dia*).
  - Persona responsable.
  - Temps estimat en minuts per evitar allargaments innecessaris.
- Els punts es poden afegir, modificar, reordenar o eliminar abans de la reunió.

---

## 4. Fase 2: Enregistrament i Transcripció d'Àudio
- **Opció A (Directe)**: En iniciar la reunió, es prem el botó de gravació a l'aplicació web mitjançant la Web Audio API del dispositiu.
- **Opció B (Pujada)**: Si la sessió s'ha enregistrat amb una gravadora externa o telèfon mòbil, es puja el fitxer (`.mp3`, `.m4a`, `.wav`, `.ogg`).
- **Motor de Transcripció en Català**:
  - L'aplicació analitza la conversa i en genera un esborrany estructurat en quatre blocs:
    1. *Assistència i càrrecs presents*.
    2. *Resum de les intervencions del debat*.
    3. *Propostes i mesures d'AC votades i aprovades*.
    4. *Taula d'acords executius, encàrrecs concrets, responsables i terminis*.

---

## 5. Fase 3: Edició de l'Esborrany
- Un cop generada la transcripció, l'acta roman en estat **"Esborrany en Fase d'Edició"**.
- El Secretari o l'equip poden:
  - Corregir dades o noms mal interpretats per la transcripció.
  - Afegir matisos o xifres exactes de pressupost.
  - Detallar els terminis de les tasques pendents.
  - Desar l'esborrany de manera provisional.

---

## 6. Fase 4: Blindatge Permanent i Immutabilitat (Acció Irreversible)
- Quan l'acta ha estat revisada i validada per l'Executiva, el Secretari acciona el botó **"TANCAR I BLINDAR ACTA"**.
- S'activa un modal solemne d'advertència de confirmació.
- En confirmar el blindatge:
  1. L'estat canvia definitivament a **"ACTA OFICIAL TANCADA I BLINDADA"**.
  2. Tots els camps de text, inputs i taules queden **estrictament bloquejats en mode només lectura** (`readonly`/`disabled`).
  3. Es genera un **Segell de Seguretat Criptogràfic / Hash d'Integritat Únic** (Exemple: `AC-CAT-2026-09-26-9B4E1F8C`) que certifica l'estat original del document.
  4. S'incorpora la signatura electrònica i la marca de temps exacta de bloqueig.
  5. L'acta es persisteix en el magatzem de dades oficials per a consultes futures o auditoria interna.
  6. Es permet la impressió o descàrrega en format PDF oficial amb marca d'aigua de segellat.
