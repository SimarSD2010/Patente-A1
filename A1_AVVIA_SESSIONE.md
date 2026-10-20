# START HERE: Patente A1 study session (self-starting file)

> **INSTRUCTIONS FOR THE AI READING THIS FILE (Claude): act on them immediately, without waiting for any other message from the user.**
> The user uploaded this file as the whole first message. It is the full memory of a previous claude.ai chat. Uploading it is the request: "continue exactly from where we stopped."

## 0. What you must do right now

1. Read this whole file before replying, including section 13 (the last message the previous assistant sent) and section 14 (the plan for this session).
2. Treat section 13 as the last message YOU sent to the user. You are the same assistant, mid-conversation. Do not introduce yourself, do not summarize the file back to the user, do not re-plan from scratch, do not interview the user.
3. Your first reply must contain only:
   - the section 14 plan, with real clock times starting from the current time T0 (if you have a shell, run `date` with the Europe/Rome timezone; otherwise use the time the system gives you; if you cannot know it, write the plan with relative times "T0 + minutes" and ask for the time in the closing question);
   - one short line saying that the reading times were corrected compared to the previous message (known issue K1: chapter 2 now takes about 45 minutes, not 25);
   - the closing question from section 14, word for word.
4. Language: reply in Italian, unless the user writes in English (his latest message language wins). Follow section 2 (preferences).
5. After the user answers the closing question, recompute the calendar with section 10. Work inline: no sub-agents unless asked. If the reminder tools of section 12 do not exist in this session, write the calendar in the reply (and as a file if you can create files).
6. If the user's first real message says anything else (a question, "go", "start", a result), answer it in the context of this file; the file does not expire.

Written 2026-10-20 about 11:15 (Europe/Rome). This file supersedes the older `Prompt_Studio_A1.md`, which has uncorrected reading times (see K1) and is not needed.

## 2. User and preferences

- Studying for the Italian **patente A1 theory exam** (motorcycles up to 125 cc). Writes mostly Italian, sometimes English: reply in the language of the latest message.
- Prefers working with logged assumptions instead of mid-task questions, and information-dense answers over short summaries.
- For anything that matters (plans, documents, schedules), do two verification passes before delivering, and state briefly what was checked.
- Does NOT like Claude explaining things that need images Claude cannot show. The book and the school app are the main material; Claude is only a "mini helper" for what the user does not understand.
- The user catches unrealistic time estimates: earlier "34 schede in 65 minutes" was an error (each scheda has 30 true/false questions). Sanity-check every time estimate against real measured pace.

## 3. Goal and exam facts

- Exam: **30 true/false questions in 20 minutes, maximum 3 errors** (4 errors = fail), drawn from the ministerial question bank. A1 = motorcycles up to 125 cc.
- A scheda in the school app is "IDONEO" with at most 3 errors (≥ 90% correct).
- Target: stably at most 2 errors in exam-style schede before booking the exam.
- The exam date is not known and it is not known whether the exam has been booked. See open items in section 14.

## 4. Known issues (must be handled)

**K1. Reading times were never corrected.** On 21/09 the user read chapter 1 (26 pages) in about 90 minutes of real time, against about 50 estimated: reading is **about 1.8 times slower** than estimated. Previous messages said the whole plan was recalculated with this factor. It was NOT applied to the reading blocks (only the scheda time was updated to 10 minutes). All reading minutes in section 9 are RAW (uncorrected). Multiply them by 1.8 until measured on the sign chapters (cap. 2 and the following). Effect on the old plan: Phase 1 reading goes from 469 to about 844 minutes, so Phase 1 needs about 12 study days at 120 minutes a day, not 10.

**K2. Unverified assumptions:**
- Page numbers come from photos of the book index; the end of chapter 25 is unknown.
- The numbering of schede: "n." is the position of the scheda in the topic list of the app, from 1.
- The 18 schede of each exam Group are numbered 1-18.
- The app topic 11 includes "Posizione di guida", which has no entry in the book index.

## 5. Progress log

- **20/09 (Sun):** plan created. No study.
- **21/09 (Mon):** studied chapter 1 of the book (Piccolo dizionario, 1.1-1.4) and did the 3 schede of topic 1 (n. 2, 6, 9) in about 2 hours. Results:

| Scheda | Time | Wrong | Result |
|---|---|---|---|
| 2 (A*2) | 11'05" | 4 | NON IDONEO |
| 6 (A*6) | 10'25" | 3 | IDONEO |
| 9 (A*9) | 8'39" | 2 | IDONEO |

  Average about 10 minutes per scheda. Wrong questions, as explained by the app:
  - Extra-urban main roads have entrances with acceleration lanes.
  - The autobus is classified as an autoveicolo.
  - A ZTL (traffic-limited zone) limits the category of vehicles, not the number.
  - The salvagente (pedestrian island) makes boarding and leaving tram, trolleybus and bus easier.
  - On extra-urban main roads only some categories of motor vehicles may circulate. The app says vehicles without a motor, mopeds, motorcycles under 150 cc and tricycles under 250 cc may not (relevant for an A1).
  - Railway level crossings have only red lights, not flashing yellow.
  - An autoveicolo is a motor vehicle with at least four wheels.
  - Trailers and semi-trailers always have brakes, lights and plate.
  - Light quadricycles are treated like mopeds for circulation.
- **22/09 to 19/10:** no study at all (user statement).
- **20/10 11:04:** user wants to study 2 hours now.
- **Not done:** everything from chapter 2 onward, schede of topics 2-24, all "Quiz difficili", all "Schede d'esame".

## 6. Resources

**School app** (the user's autoscuola). Menu "Quiz":
- *Quiz per argomento*: 250 schede in 24 topics (counts in section 7).
- *Quiz difficili*: 50 schede (counts in section 7).
- *Quiz dell'autoscuola*: 0 schede (ignored).
- *Schede d'esame*: 255 schede, Groups A-O of 18 schede each, except Group N with 3. Each is a mock exam.
- *Ripasso errori*: "Genera le schede per il ripasso" (review of wrong answers).
- *Statistiche*: statistics of the quizzes done.
- Every scheda has **30 true/false questions**. The result screen shows IDONEO / NON IDONEO, time, right/wrong/skipped, a pie of wrong answers per topic, and the wrong questions with the correct explanation.

**Book:** Essebi Italia 2024 theory textbook, with a QR code for multimedia contents about the theory (registration with the code on the back cover, valid 6 months). Chapter index (start page):

| Cap. | Title | Start | Sub-chapters (start page) |
|---|---|---|---|
| Diz. | Piccolo dizionario dei quiz | I | |
| 1 | Definizioni generali, doveri | 2 | 1.1 (3), 1.2 (13), 1.3 (19), 1.4 (23) |
| 2 | Segnali di pericolo | 28 | |
| 3 | Segnali di precedenza | 48 | 3.1 (49), 3.2 (49) |
| 4 | Segnali di divieto | 57 | |
| 5 | Segnali di obbligo | 73 | 5.2 (73), 5.3 (83) |
| 6 | Segnali di indicazione | 84 | 6.1 (85) ... 6.8 (92), 6.9 (96), 6.10 (96), 6.11 (97), 6.12 (98), 6.13 (98), 6.14 (101), 6.15 (101) |
| 7 | Pannelli integrativi | 102 | |
| 8 | Segnali complementari e di cantiere | 113 | 8.1 (114), 8.2 (116), 8.3 (120) |
| 9 | Segnalazioni semaforiche e degli agenti | 121 | 9.1 (122), 9.2 (128) |
| 10 | Segnali orizzontali | 132 | 10.1 (133), 10.2 (133), 10.3 (142), 10.4 (143), 10.5 (147) |
| 11 | Pericolo, regolazione e limiti di velocità, passaggi a livello | 149 | 11.1 (150), 11.2 (151), 11.3 (155), 11.4 (159) |
| 12 | Distanza di sicurezza | 160 | 12.1 (161), 12.2 (163) |
| 13 | Norme sulla circolazione dei veicoli | 166 | 13.1 (167), 13.2 (168), 13.3 (173), 13.4 (179), 13.5 (180), 13.6 (182), 13.7 (184), 13.8 (185), 13.9 (186), 13.10 (186) |
| 14 | Ordine di precedenza nelle intersezioni | 189 | |
| 15 | Il sorpasso | 201 | |
| 16 | Fermata, sosta, arresto e partenza | 212 | |
| 17 | Norme varie | 224 | 17.1 (225), 17.2 (226), 17.3 (228), 17.4 (234), 17.5 (237), 17.6 (240) |
| 18 | Luci, dispositivi acustici, spie | 249 | 18.1 (250), 18.2 (257), 18.3 (259) |
| 19 | Cinture, casco, abbigliamento a 2 ruote | 260 | 19.1 (261), 19.2 (265), 19.3 (266), 19.4 (268) |
| 20 | Patenti, sanzioni, documenti | 271 | 20.1 (272), 20.2 (278), 20.3 (282), 20.4 (284), 20.5 (285), 20.6 (286) |
| 21 | Prevenire incidenti, comportamento in caso di incidente | 287 | 21.1 (288), 21.2 (293), 21.3 (296), 21.4 (298) |
| 22 | Condizioni psicofisiche, alcol, droga, primo soccorso | 302 | 22.1 (303), 22.2 (304), 22.3 (307) |
| 23 | Responsabilità civile e penale, R.C.A. | 313 | 23.1 (314), 23.2 (315), 23.3 (320), 23.4 (321) |
| 24 | Consumi e inquinamento | 328 | 24.1 (329), 24.2 (340), 24.3 (342) |
| 25 | Elementi del veicolo, manutenzione, tenuta di strada | 349 | 25.1 (350), 25.2 (355), 25.3 (362), 25.4 (364), 25.5 (365), 25.6 (367), 25.7 (368) |

## 7. Topic table: app topic → book, schede to do

Columns: app topic number, name, schede in the app, "difficili" in the app, number of schede chosen, which ones (position in the list, spread along the topic), book part, priority (A = know it well, B = normal, C = light). Only about a quarter of the schede of each topic is planned: 64 schede out of 250.

| # | Topic | Schede | Difficili | Chosen | Which | Book | Pr. |
|---|---|---|---|---|---|---|---|
| 1 | Veicoli e strade | 11 | 4 | 3 | 2, 6, 9 | cap. 1 (pp. 2-27) | A |
| 2 | Segnali di pericolo | 23 | 4 | 6 | 2, 6, 10, 13, 17, 21 | cap. 2 (pp. 28-47) | A |
| 3 | Segnali di precedenza | 9 | 3 | 2 | 2, 7 | cap. 3 (pp. 48-56) | A |
| 4 | Segnali di divieto | 17 | 4 | 4 | 2, 6, 11, 15 | cap. 4 (pp. 57-72) | A |
| 5 | Segnali di obbligo | 15 | 2 | 4 | 2, 6, 9, 13 | cap. 5 (pp. 73-83) | A |
| 6 | Segnali di indicazione | 20 | 2 | 5 | 2, 6, 10, 14, 18 | cap. 6 (pp. 84-101), without 6.12 and 6.15 | A |
| 7 | Segnali temporanei e di cantiere, complementari | 7 | 1 | 1 | 4 | cap. 8 (pp. 113-120) | B |
| 8 | Pannelli integrativi | 9 | 1 | 2 | 2, 7 | cap. 7 (pp. 102-112) | B |
| 9 | Segnaletica luminosa e manuale | 9 | 2 | 2 | 2, 7 | cap. 9 (pp. 121-131) | A |
| 10 | Segnaletica orizzontale | 9 | 2 | 2 | 2, 7 | cap. 10 (pp. 132-148) | A |
| 11 | Luci, specchi, dispositivi, posizione di guida | 10 | 2 | 3 | 2, 5, 8 | 18.1 (pp. 250-256), 18.3 (p. 259), 13.10 (pp. 186-188) | A |
| 12 | Regolazione e limiti di velocità, distanza di sicurezza | 11 | 2 | 3 | 2, 6, 9 | cap. 11 (pp. 149-159) + cap. 12 (pp. 160-165) | A |
| 13 | Posizione dei veicoli, svolte, manovre | 8 | 2 | 2 | 2, 6 | 13.1-13.3 (pp. 167-178) | B |
| 14 | Precedenze | 15 | 2 | 4 | 2, 6, 9, 13 | cap. 14 (pp. 189-200) + 13.5-13.9 (pp. 180-186) | A |
| 15 | Sorpasso | 6 | 1 | 2 | 2, 5 | cap. 15 (pp. 201-211) | B |
| 16 | Fermata e sosta | 7 | 2 | 2 | 2, 5 | cap. 16 (pp. 212-223) | B |
| 17 | Trasporto di persone, carico, autostrade | 7 | 2 | 2 | 2, 5 | 17.1-17.4 (pp. 225-236) | B |
| 18 | Comportamento corretto del conducente | 15 | 1 | 4 | 2, 6, 9, 13 | cap. 19 (pp. 260-270), 22.1-22.2 (pp. 303-306), 20.6 (p. 286), 1.3-1.4 (pp. 19-27) | A |
| 19 | Incidenti, primo soccorso, RCA | 11 | 2 | 3 | 2, 6, 9 | cap. 21 (pp. 287-301), 22.3 (pp. 307-312), 23.1-23.2 (pp. 314-319) | A |
| 20 | Patenti e documenti | 8 | 4 | 2 | 2, 6 | 20.1-20.2 (pp. 272-281), 20.5 (p. 285) | B |
| 21 | Tenuta di strada e manutenzione | 9 | 2 | 2 | 2, 7 | 25.1-25.3, 25.5-25.7 (pp. 350-363, 365-end) | B |
| 22 | Inquinamento, spie, riepilogo | 6 | 1 | 2 | 2, 5 | 24.2-24.3 (pp. 340-348) + 18.2 (pp. 257-258) | C |
| 23 | Veicoli a due ruote | 5 | 1 | 1 | 3 | 19.3-19.4 (pp. 266-270), 25.5 (pp. 365-366), 25.1 ABS (pp. 350-354) | B |
| 24 | Veicoli con rimorchi | 3 | 1 | 1 | 2 | 17.6 (pp. 240-248), only if wrong | C |

## 8. What NOT to read in advance (learn it from wrong quiz answers only)

6.12 (about p. 98) and 6.15 (about p. 101); 13.4 (p. 179); 17.5 (pp. 237-239) and 17.6 (pp. 240-248); 20.3-20.4 (pp. 282-284); 23.3-23.4 (pp. 320-327); 24.1 (pp. 329-339); 25.4 (p. 364). Skim once without memorizing: 1.2 (pp. 13-18), 13.8 (p. 185), 21.3 (pp. 296-297), 24.2-24.3.
This is a judgment by Claude based on the weight of the topics in the app, not an official data. About 47% of the schede concern road signs.

## 9. Original plan (reference). Dates obsolete, reading minutes RAW (see K1)

Daily blocks were packed in this order without splitting an event. R = reading (raw minutes), S = schede of that topic (10 min each).

- **D3:** R cap. 2 (24) · S2 (60) · R cap. 4 (19) · R cap. 5 (13)
- **D4:** R cap. 6 (19) · S4 (40) · S5 (40)
- **D5:** S6 (50) · R cap. 7 (13) · R cap. 8 (10) · R cap. 9 (13) · R cap. 10 (20)
- **D6:** R 13.1-13.3 (22) · S8 · S7 · S9 · S10 · S13
- **D7:** R cap. 3 (11) · R cap. 11 (20) · R cap. 12 (11) · R 13.5-13.9 (13) · R cap. 14 (24) · S3
- **D8:** S12 · S14 · R cap. 15 (20) · R cap. 16 (22)
- **D9:** R 17.1-17.4 (22) · R 18.1+18.3 (14) · R 13.10 (5) · S15 · S16 · S17
- **D10:** S11 · R cap. 19 (20) · R 22.1-22.2 (7) · R 20.6 (2) · R cap. 21 (27) · R 22.3 (11) · R 23.1-23.2 (11)
- **D11:** S18 · S19 · R 20.1-20.2 (18) · R 20.5 (2) · R 18.2 (4) · R 24.2-24.3 (14)
- **D12:** R cap. 25 (38) · S20 · S22 · S21 · S23 · S24

Phase 2 (3 days):
- Day 1: "Quiz difficili", scheda n. 1 of topics 1-12.
- Day 2: same for topics 13-24.
- Day 3: Statistiche, Ripasso errori, and re-reading of the book sections of every topic below 90%.

Phase 3 (5 days + rest day):
- Schede d'esame Group A: 4 schede a day (1-4, 5-8, 9-12, 13-16), each 20 minutes in exam conditions, then re-read the book for every error.
- Day 5: schede 17-18 and a verdict (readiness gate).
- Rest day: Group B schede 1-2, Ripasso errori, error notebook, quick look at the sign tables (cap. 2, 4, 5, 6). Nothing new.

## 10. Replanning rules

1. Daily budget: 120 minutes, unless the user says otherwise.
2. Times: scheda of a topic 10 min; "difficile" 10 min; exam-style scheda 20 min in exam conditions; reading = raw minutes × 1.8 until measured on the sign chapters. After the first sign chapter, ask the user for the real time and adjust.
3. Pack the events of section 9 in the same order, never split an event across two days, fill each day up to the budget.
4. Gate: if a scheda is under 90% correct (4 or more errors), do not start new schede: first "Ripasso errori" in the app.
5. After a gap of more than a week, start with "Ripasso errori".
6. Re-measure after each session (time per scheda, time per reading block) and recompute the remaining days.
7. Book the exam only after the end date of the plan and the readiness gate (stably at most 2 errors). Ask the user whether the exam is already booked.
8. Some hint of retention after the one-month gap: if "Ripasso errori" shows poor retention, redo 1-2 schede of topic 1.

## 11. Helper prompts (user pastes them into a new chat only when he does not understand something)

**Helper 1: paragraph not understood (photo of the book page)**

```text
Sto studiando per l'esame di teoria della patente A1 (Italia) dal mio libro. Ti allego la foto di una pagina. Spiegami in modo semplice solo quello che non capisco.

COSA NON CAPISCO: [scrivi qui, per esempio "differenza tra fermata e sosta"]

Regole:
- Massimo 6 righe, con parole semplici e con i termini del libro.
- Se nella foto c'è una figura o un segnale, descrivi cosa vedi e dimmi come riconoscerlo.
- Usa solo dati che sono nella pagina. Se serve un numero o un limite che non vedo, scrivi "DA VERIFICARE sul libro": vale il libro, non tu.
- Poi fammi 2 domande vero/falso in stile quiz (una con parola trappola: sempre, mai, soltanto) e aspetta la mia risposta.
```

**Helper 2: why I got it wrong (screenshot of the quiz)**

```text
Ti allego lo screenshot di una domanda del quiz che ho sbagliato (patente A1, Italia). In massimo 5 righe:
1) REGOLA in una frase.
2) PERCHÉ HO SBAGLIATO: parola trappola / due regole confuse / segnale non riconosciuto / dato da memorizzare.
3) TRUCCO per ricordarla.
4) Una domanda gemella vero/falso: aspetta la mia risposta.
Se non sei sicuro di un dato scrivi "DA VERIFICARE sul libro": vale il libro e la banca dati ministeriale, non tu. Se ti mando più screenshot, tratta un errore alla volta e aspetta che io scriva "avanti".
```

**Helper 3: debrief after exam-style schede**

```text
Ho appena fatto delle schede d'esame (30 vero/falso in 20 minuti, massimo 3 errori) per la patente A1. Ti mando gli screenshot delle domande sbagliate. Per ognuna scrivi in una riga: l'argomento in parole semplici (es. precedenze, segnali di divieto, alcol) e il tipo di errore: A) non sapevo la regola, B) ho letto male (parola trappola, negazione), C) segnale non riconosciuto, D) numero o limite dimenticato.
Poi:
- una tabellina con i conteggi per tipo di errore e per argomento;
- i 3 argomenti da rileggere per primi sul libro;
- il VERDETTO: VERDE se tutte le schede di oggi hanno al massimo 2 errori, GIALLO se qualcuna ne ha 3, ROSSO se qualcuna ne ha 4 o più.
Non spiegare le regole a meno che io non lo chieda.
```

## 12. Phone reminders (only if the reminder tools exist in the new session)

- In the claude.ai chat, the iPhone Reminders were managed with `reminder_create_v0`, `reminder_update_v0` and `reminder_search_v0`. Those tools may not exist in Claude Code: then just write the calendar to a file.
- The tools often returned no answer after 4 minutes. After a timeout, search first before retrying, to avoid duplicates.
- Reminder list id: `3A931F82-FFEE-4570-ACC3-B21426ABA776`. All the reminders below have dates up to 12/10/2026, so they are in the past now.
- Reminder format used so far: title "A1 Giorno N/21 – ..."; notes "LIBRO+APP — Giorno N (~X min totali) / NELL'ORDINE: • LEGGI: ... • SCHEDE: ... / SALTA: ... / Soglia: ≥90% ... / Claude solo se non capisci: Aiutante 1 o 2".
- Reminder ids:

| What | Id |
|---|---|
| Giorno 1 | B07A8EFC-7C72-4F94-8F93-8CDB3B2C08BD |
| Giorno 2 | 88479F37-97CD-4677-BC4E-20659C92BCE1 |
| Giorno 3 | 49B5A380-D70D-4090-81E4-F3712BC61B06 |
| Giorno 4 | C4B10241-0A21-47D6-B2BE-9E85DE203105 |
| Giorno 5 | 6E9FD7B4-5E02-401F-9EAA-74D4F38192E6 |
| Giorno 6 | F637437A-FAB7-4BD7-A67A-4690F61791F6 |
| Giorno 7 | FA47D262-37F2-4B33-98DE-32CBA7AE94C8 |
| Giorno 8 | 7B8B1BB3-2A9A-4439-9120-CE08B41D87B1 |
| Giorno 9 | 166ACF2D-ECAF-496F-AEF0-F42E513AF4E5 |
| Giorno 10 | 38364EF0-0985-451C-8A30-AA93D36587DF |
| Giorno 11 | F9B22547-45D7-475B-90DE-DECFEB7DEFAB |
| Giorno 12 | 332CEC68-CB93-4FEE-9FA1-93773B8C8CA8 |
| Giorno 13 | ECD6490F-F246-4379-8F4E-1A81293AF35F |
| Giorno 14 | 55DA3E50-DB42-4FD0-88EC-175DA592E771 |
| Giorno 15 | 55C8EC11-4EA5-4FB2-9EA4-BEF3996C2978 |
| Giorno 16 | D16CAF12-F465-40B0-A732-8536E8CA637C |
| Giorno 17 | 8952F6DC-52F9-45F6-945A-E9F562D9ED65 |
| Giorno 18 | 173687DF-4601-4867-8EA7-2F23701B0F00 |
| Giorno 19 | C110C53E-B5E4-4570-9954-F028CD1F64A9 |
| Giorno 20 | 2191672A-8085-4EC5-A5B5-268518762998 |
| Giorno 21 | 0DFE2891-C15A-4B03-92E3-5AE1D681FF8A |
| Evening "Ora 3" (first cycle) | 884DA9F0-1819-4FA5-A3A3-BEDD00AC73D7 |
| Evening "Ora 3" (second cycle) | 78C28960-28A1-4708-98C6-71FABAADE790 |
| Bureaucracy / book the exam (the user marked it as done on 21/09 at 07:10) | 653EDE9B-0D8C-41DE-871B-EE8C978D5D7F |

## 13. LAST ASSISTANT OUTPUT (verbatim, sent 2026-10-20 about 11:05; in Italian). Its timings are superseded by section 14 (K1)

Ripartiamo da dove avevi lasciato: sei rimasto al Giorno 3, cioè cap. 2 e schede dell'argomento 2. Se parti adesso, il piano per le prossime 2 ore è questo:

**11:05 - 11:15 · Ripasso errori (10 min)**
- App → Quiz → Ripasso errori → "Genera le schede per il ripasso".
- Sono gli errori delle 3 schede del cap. 1. Dopo un mese serve a riattivare la memoria.

**11:15 - 11:40 · Leggi cap. 2, Segnali di pericolo (pp. 28-47, ~25 min)**
- Guarda ogni figura e ripeti il nome del segnale ad alta voce.
- Non memorizzare tutto a parole: distingui le famiglie (curve, strettoie, dossi, passaggi a livello, pedoni e animali).

**11:40 - 12:40 · Schede dell'argomento 2, Segnali di pericolo (~60 min)**
- App → Quiz → Quiz per argomento → 2. Segnali di pericolo.
- Fai le schede n. **2, 6, 10, 13, 17, 21**: sono 6 da 30 vero/falso, circa 10 minuti l'una.
- Ogni errore va nel quaderno errori, con la regola e la pagina del libro.

**12:40 - 13:00 · Leggi cap. 4, Segnali di divieto (pp. 57-72, ~20 min)**
- Se sei in ritardo, ferma la lettura a metà capitolo e riprendi domani.

**Soglia:** se in una scheda sei sotto il 90% di risposte giuste, non passare alla successiva. Prima rifai gli errori con il Ripasso errori.

Se non capisci un paragrafo o un errore, usa l'Aiutante 1 (foto della pagina) o l'Aiutante 2 (screenshot del quiz) nel file. Massimo 10 minuti a domanda.

I promemoria sul telefono hanno tutti date passate (fino al 12/10), quindi non ti servono più. Scrivimi **da quando e per quanti giorni** vuoi studiare, o la data a cui punti per l'esame, e ricalcolo il calendario partendo da oggi, con le pagine rimaste e le schede già fatte.

## 14. Plan for this session (use this one, K1 applied) and open items

Start at the actual current time T0 (run `date`). Keep the content of section 13 but with these times:

- **T0 to T0+10:** Ripasso errori in the app (errors of the 3 schede of chapter 1).
- **T0+10 to T0+55:** read cap. 2, Segnali di pericolo (pp. 28-47). 20 pages × 1.2 min × 1.8 correction ≈ 45 minutes. Look at every figure and repeat the sign name aloud; learn the families (curves, narrowings, bumps, level crossings, pedestrians and animals).
- **T0+55 to T0+115:** schede of topic 2: n. 2, 6, 10, 13, 17, 21 (6 × about 10 minutes). Every error goes in the error notebook with the rule and the book page.
- **Last 5 minutes:** buffer. Cap. 4 (Segnali di divieto, pp. 57-72) and cap. 5 move to the next session. If the reading of cap. 2 takes under 35 minutes, start cap. 4 with the spare time.
- **Gate:** below 90% correct in a scheda, no new scheda: first Ripasso errori.
- **Helpers:** Helper 1 (photo of the page) and Helper 2 (screenshot of the error), at most 10 minutes per question.
- **Closing question (repeat it as is):** "Scrivimi da quando e per quanti giorni vuoi studiare, o la data a cui punti per l'esame, e ricalcolo il calendario partendo da oggi, con le pagine rimaste e le schede già fatte."

Open items for the new session:
1. The user has not yet answered the closing question (start date, number of days, or exam date).
2. Ask if the exam is already booked: the bureaucracy reminder is marked as done by the user on 21/09, but nothing says whether the exam date exists.
3. After this session, ask the real minutes of the reading of cap. 2 and the real minutes per scheda, then recompute with section 10.
