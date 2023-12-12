# NER-Aufgabe-Transplantation
#Named Entitiy Recognition Texte Transplantationschirurgie

Die Named Entity Recognition (NER) beschreibt die Technik zur Identifizierung und Extraktion von speziellen benannten Entitäten in Texten, wie z.B. Personennamen, Ortsnamen, Organisationen, Produkte und mehr (Carstensen et al., 2010). Im Kontext von medizinischen Texten bieten sich mit der NER viele Möglichkeiten. NER kann dazu beitragen, schnell relevante Informationen aus unstrukturierten medizinischen Daten zu extrahieren. Beispielsweise können medizinische Fachkräfte dabei unterstützt werden, schnelle und fundierte Entscheidungen zu treffen (Götz, 2023).

Es können also benannte Entitäten in medizinischen Texten identifiziert und klassifiziert werden. Daraus ergibt sich die Annotationsaufgabe, Krankheitsnamen und Medikamentennamen in medizinischen Texten mithilfe eines Sprachmodells zu annotieren.

Beispieltext:

“Tuberculosis is a communicable disease of public health concern that inequitably impacts the most vulnerable populations worldwide. Vulnerable populations are those with a high risk for tuberculosis disease and whose disadvantaged or marginalised socioeconomic position limits their access to the health system. We conducted an overview of reviews that aimed to assess the burden (ie, prevalence and incidence) of tuberculosis disease among 12 vulnerable populations globally (Litvinjenko et al., 2023).”

Annotation:

Krankheitsname: Tuberculosis

Krankheitsname: tuberculosis disease (wiederholte Erwähnung)

Datenbasis:

Als Datenbasis werden 8 der meistzitierten Artikel des American Journal of Transplantation herangezogen. Eines der rennomiertesten Magazine für Transplantationschirurgie.

Sprachmodell / Interface:

ChatGPT

Experimentdesign:

Datenauswahl: Auswahl medizinischer Texte aus den genannten Quellen.

Datenvorbereitung: Daten werden mittels Phython zu einer Textdatei zusammengstellt.

Annotation mit Prompts: Mittels zielführender Prompts sollen die Entitäten "Organe" und "Krankheiten" annotiert werden

Annotatorenauswahl für die Überprüfung: Annotatoren mit medizinischem Hintergrund, um die von den LLMs generierten Annotationen zu überprüfen.



