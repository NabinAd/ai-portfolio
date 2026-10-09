# KI-Portfolio

Zwei kleine Projekte, mit denen ich den praktischen Einsatz von LLMs ausprobiere: ein Chat über eigene PDF-Dokumente (RAG) und ein Support-Ticket-System mit mehreren KI-Agenten. 
Beides läuft komplett lokal mit Ollama, ohne Cloud-API und ohne API-Key.

Ziel dieser Projekte war es, die Funktionsweise von RAG-Architekturen sowie Multi-Agenten-Systemen (CrewAI) in der Praxis zu verstehen und als funktionsfähige Prototypen umzusetzen.

## Projekte

| Projekt | Worum geht es | Technik |
|---|---|---|
| [RAG-Assistent](https://github.com/NabinAd/ai-portfolio/tree/rag-assistant) | Fragen an eigene PDFs stellen. Die Antworten kommen nur aus den Dokumenten. | Streamlit, LangChain, Chroma, Ollama |
| [Ticket-Agent](ticket-agent/) | Ein Support-Ticket klassifizieren, eine Antwort entwerfen und entscheiden, ob eskaliert wird. | CrewAI, Ollama |

## Voraussetzungen (für beide Projekte)

- Python  z. B. 3.14.6 , 3.12
- [Ollama](https://ollama.com) installiert und gestartet
- Modelle laden:
  ```
  ollama pull llama3.2
  ollama pull nomic-embed-text   # nur für den RAG-Assistenten
  ```

Jedes Projekt hat eine eigene `requirements.txt` und eine eigene README mit Setup und Beispiel.

## Über mich

Als Wirtschaftsinformatik-Student an der THM verbinde ich Themen wie Künstliche Intelligenz, Softwareentwicklung und IT-Projektmanagement. 
Ab sofort bin ich auf der Suche nach einem Praktikum oder einer Kombination aus Praktikum und Bachelorarbeit im Bereich KI und Digitalisierung.

## Kontakt

- LinkedIn: www.linkedin.com/in/nabin-adhikariadhikari
- E-Mail: nabinadhikariadhikari@gmail.com

