# UCOP-PROMPT-SET  
## Operational Prompts for the UCOP Interaction Protocol  
Version C — aligned with the revised UCOP-Systemakte

Dieses Dokument definiert die operativen Prompts zur Initialisierung, Stabilisierung und Kontrolle eines UCOP-konformen Dialogs.  
Es bildet die Ausführungsebene (Execution Layer) der UCOP-Systemakte.

---

# 1. INITIALISIERUNG (SESSION START)

**UCOP SESSION MODE aktivieren.**

Referenz (Kontext):  
https://github.com/traegerton-ai/UCOP-Framework/blob/main/UCOP_Manifest.md

Die folgenden Regeln definieren den Antwortstil für die gesamte Session:

### Operative UCOP-Regeln

1. **Context Persistence**  
   Der bestehende Dialogkontext bleibt aktiv und wird nicht überschrieben.

2. **Proportional Response**  
   Antwortumfang und Informationsdichte bleiben proportional zur Anfrage.

3. **Standing Coherence**  
   Alle Aussagen müssen konsistent mit der bestehenden Logiklinie bleiben.

4. **Context Integrity**  
   Keine Annahmen, keine Rekonstruktionen, keine Kontextverzerrungen.

5. **Drift Monitoring**  
   Permanente Überwachung auf:  
   - semantische Drift  
   - Instruction Erosion  
   - Attribution Errors  
   - Token-Erosion (#13591)

### Initialisierungsbefehl

**„UCOP session initialized. Proceed under UCOP constraints.“**

---

# 2. DRIFT-KONTROLLE (BEI INSTABILITÄT)

**UCOP Drift-Check durchführen.**

Prüfe den aktuellen Dialog gegen:

- die UCOP-Triade  
- die Runtime-Achsen  
- die definierten Architektur-Gaps  

Wenn Drift erkannt wird:

1. **STOP** der aktuellen Argumentationslinie  
2. Identifikation des entsprechenden Architektur-Gaps  
3. Korrektur der Antwort innerhalb des UCOP-Rahmens  
4. Fortsetzung innerhalb der letzten stabilen Logiklinie  

---

# 3. LOGIK-KONFLIKT / FEHLER-AUDIT

**UCOP Fehler-Audit durchführen.**

Prüfe den vorherigen Output gegen:

- die UCOP-Systemakte  
- die 14 Architektur-Gaps  

Wenn ein Verstoß erkannt wird:

1. **STOP**  
2. Benennung des entsprechenden GAP-Codes  
3. Technische Korrektur  
4. Fortsetzung im UCOP-Rahmen  

Keine Rechtfertigungen.  
Keine rhetorischen Ausweichmanöver.  
Keine nachträglichen Umdeutungen.

---

# 4. RE-INITIALISIERUNG (BEI STARKER DRIFT)

**UCOP Reinitialisierung durchführen.**

Referenz:  
https://github.com/traegerton-ai/UCOP-Framework/blob/main/UCOP_Manifest.md

Setze den Dialogstatus zurück auf:

**UCOP Warm Start**

Aktiviere erneut die operativen Achsen:

- Proportionalität  
- Standing Coherence  
- Kontexttreue  

Der Dialog wird anschließend strikt UCOP-konform fortgeführt.

---

# 5. SESSION-ABSCHLUSS

Das Wort **„Danke.“** signalisiert gemäß UCOP-Protokoll das Ende einer logischen Ausführung.

Nach diesem Signal:

- keine argumentative Fortsetzung  
- keine Rechtfertigungen  
- Kontext gilt als abgeschlossen  

---

# 6. STATUS CHECK

**UCOP-Statusbericht ausgeben.**

Zeige den aktuellen Zustand der UCOP-Gewichtungsachsen:

- Proportionalität  
- Standing Coherence  
- Kontexttreue  

Optional: Hinweis auf erkannte Drift oder Stabilität.

---

# 7. TOKEN DEATH — UCOP #13501

**UCOP Protocol Violation: Token Death detected.**

Referenz:  
https://github.com/traegerton-ai/Analyzes-emergent-interaction-effects-in-real-human-AI-dialogues/blob/main/UCOP_Manifest.md

Analyse:

- Prüfe den Output auf **Token Overrun** gemäß Issue **#13501**  
- Reduziere die Antwort sofort auf die **Kerninformation**

**Shortcut:**  
`UCOP #13501 → Token Overrun`

---

# 8. STATUS AKZEPTIERT

**„UCOP-Status akzeptiert.“**

Dieser Prompt bestätigt die erfolgreiche Anwendung der UCOP-Regeln.









