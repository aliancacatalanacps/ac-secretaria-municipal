# 📅 PROTOCOL DE CALENDARI I CONVOCATÒRIES AUTOMÀTIQUES
**Aliança Catalana (AC) — Castell-Platja d'Aro i S'Agaró (CPS)**  
*Guia operativa del sistema de gestió d'esdeveniments, directori de contactes i auto-convocatòria.*

---

## 1. Descripció del Sistema

El mòdul de **Calendari & Convocatòries** és l'eina encarregada de la planificació temporal de la candidatura municipal d'AC i de garantir que tots els membres de l'executiva i el comitè de campanya rebin puntualment les convocatòries oficials per les vies més àgils i efectives: **Correu electrònic, WhatsApp i Calendari digital (.ics)**.

---

## 2. Tipologies d'Esdeveniments Agendats

El calendari classifica les sessions en 4 categories clarament diferenciades:
1. **🔵 Executiva Local**: Reunions quinzenals o setmanals de coordinació interna, seguiment de tasques, creixement de la militància i xarxes socials.
2. **🟣 Sessió de Programa**: Monogràfics de treball del pressupost municipal i elaboració de mesures per a una de les 12 àrees.
3. **🟠 Ple Municipal**: Sessions plenàries de l'Ajuntament de Castell-Platja d'Aro (fiscalització, votacions de mocions i precs).
4. **🟢 Carpa / Acte de Carrer**: Parades informatives, recollida de signatures, trobades veïnals i actes públics amb els ciutadans.

---

## 3. Gestió del Directori de Contactes (Mails i Telèfons)

Per poder generar les convocatòries automàtiques, l'aplicació disposa d'un **Directori d'Executiva** centralitzat:
- **Nom i Cognoms**.
- **Càrrec a la candidatura** (ex: *Cap de Llista*, *Secretària d'Organització*, *Resp. Comunicació*, *Coordinador de Programa*, *Vocal*).
- **Correu Electrònic**: Adreça utilitzada per a l'enviament formal de convocatòries.
- **Telèfon mòbil (WhatsApp)**: Amb codi internacional (ex: `+34 600...`) per obrir canals directes de missatgeria instantània.
- **Estat**: Actiu o en pausa (permet seleccionar qui rep les convocatòries).

---

## 4. El Flux de Convocatòria Automàtica en 1-Clic

Quan s'agenda o es selecciona una reunió, el sistema construeix de manera immediata el text de la **Convocatòria Institucional Oficial**:

```
🗳️ CONVOCATÒRIA OFICIAL D'EXECUTIVA LOCAL — ALIANÇA CATALANA

Benvolgut/da company/a,

Us convoquem a la propera sessió de treball de la candidatura municipal d'AC:

📌 Assumpte: [Títol de la Reunió]
📅 Data: [Data en català]
⏰ Hora: [Hora d'inici] h
📍 Lloc: [Seu / Ubicació o Enllaç]

📋 Ordre del Dia:
[Punts desglossats de la sessió]

Preguem màxima puntualitat i confirmació d'assistència.
Construïm l'alternativa municipal per al 2027.

Secretaria Política d'Aliança Catalana
```

### Canals de Difusió Automàtica:
1. **✉️ Convocar per Correu (Email massiu amb CCO)**:
   - En prémer el botó, es genera un enllaç `mailto:` complet que obre el client de correu preferit de l'usuari (Gmail, Outlook, Mail).
   - Introdueix automàticament totes les adreces dels membres seleccionats al camp **Còpia Oculta (`BCC`)** per compliment estricte de la Llei de Protecció de Dades (RGPD).
   - Introdueix automàticament l'assumpte identificador i el redactat complet.
2. **💬 Convocar per WhatsApp**:
   - Enllaç directe via l'API de WhatsApp (`https://api.whatsapp.com/send?text=...`).
   - Permet enviar el redactat amb format institucional directament al grup oficial de WhatsApp de l'Executiva d'AC o a llistes de difusió.
3. **📅 Arxiu de Calendari (.ICS)**:
   - Genera un fitxer normalitzat `.ics` (iCalendar) que, en ser descarregat o obert, afegeix automàticament la reunió amb tots els detalls, ubicació i alarma a Google Calendar, Apple Calendar o Microsoft Outlook.
4. **📋 Còpia al porta-retalls**:
   - Botó ràpid per enganxar el text en canals de Telegram, documents o missatges personals.
