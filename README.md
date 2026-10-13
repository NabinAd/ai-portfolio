# KI-Portfolio – Local LLM Projects

Dieses Repository enthält zwei Python-Projekte, mit denen ich den praktischen Einsatz lokaler Large Language Models (LLMs) untersuche.

Beide Projekte verwenden Ollama, sodass die Modelle lokal ausgeführt werden können und keine Cloud-API für die Inferenz erforderlich ist.

## Projekte

| Projekt | Worum geht es | Technik |
|---|---|---|
| [RAG-Assistent](rag-assistent) | Eigene PDFs hochladen, Dokumentinhalte durchsuchen und Fragen dazu beantworten lassen | Streamlit, LangChain, Chroma, Ollama |
| [Ticket-Agent](ticket-agent/) | Support-Tickets klassifizieren, Antwortentwürfe erstellen und Eskalationen vorschlagen | CrewAI, Ollama |

## Voraussetzungen (für beide Projekte)

- Python 3.12
- [Ollama](https://ollama.com) installiert und gestartet
- Modelle laden:
  ```
  ollama pull llama3.2
  ollama pull nomic-embed-text   # nur für den RAG-Assistenten
  ```
## Projekt starten

Jedes Projekt hat eine eigene requirements.txt und sollte in einer separaten virtuellen Python-Umgebung ausgeführt werden.

Die vollständigen Installations- und Ausführungsanweisungen findest du in den jeweiligen Projekt-READMEs:

[Installation des RAG-Assistent](rag-assistent)

[Installation des Ticket-Agenten](ticket-agent)

## Technischer Hinterground
### RAG-Assistent
Verwendet Retrieval-Augmented Generation (RAG), um relevante Textabschnitte aus hochgeladenen PDF-Dokumenten abzurufen und sie als Kontext für die Antwortgenerierung zu verwenden.

### Ticket-Agent
Verwendet drei aufeinanderfolgende Agenten für die Klassifikation eines Tickets, die Erstellung eines Antwortentwurfs und eine Entscheidung über die mögliche Eskalation.

## Grenzen

Beide Projekte sind Lern- und Portfolio-Prototypen, keine produktionsfertigen Unternehmenssysteme.

Die Antwortqualität hängt unter anderem vom verwendeten Modell und den verfügbaren Informationen ab. Die Ausgabe eines LLM ist nicht automatisch korrekt. Der Ticket-Agent ist derzeit nicht an ein echtes Ticketsystem angebunden.

## Über mich

Ich studiere Wirtschaftsinformatik an der Technischen Hochschule Mittelhessen (THM) und interessiere mich für Künstliche Intelligenz, LLM-Anwendungen und Softwareentwicklung.

Ich suche ein Praktikum beziehungsweise eine Möglichkeit, ein Praktikum mit meiner Bachelorarbeit im Bereich KI und Digitalisierung zu verbinden.

## Kontakt

- LinkedIn: www.linkedin.com/in/nabin-adhikariadhikari
- E-Mail: nabinadhikariadhikari@gmail.com

