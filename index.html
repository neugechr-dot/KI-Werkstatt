import React, { useState } from 'react';
import { 
  Sparkles, Code, Calendar, PenTool, Search, Languages, ExternalLink, 
  Github, Info, Scale, Wand2, GraduationCap, TrendingUp, Clock, 
  Landmark, Network, Cpu, FileText, BookOpen, Trophy, Layout, 
  ArrowRight, Users, Lightbulb, Microscope, Music, Video, Image as ImageIcon,
  CheckCircle2, Rocket, Brain, Layers, MessageSquare, Headphones, X, Mail,
  ChevronRight, Filter, Globe, MousePointer2, FileSearch, Zap, ListChecks, HelpCircle
} from 'lucide-react';

// --- VOLLSTÄNDIGE DATEN AUS DEM DOKUMENT ---

const GEMS_DATA = [
  { id: 1, title: "Politikzyklus interaktiv", description: "Sokratischer Tutor zur Analyse politischer Konflikte mit umfassender Dokumentation und Bewertung.", link: "https://gemini.google.com/gem/1l0xsAtu7zm0S099P9w_Q7OV-J_DZRuWz?usp=sharing", category: "Politik", icon: <Scale className="w-6 h-6" />, color: "from-blue-500 to-indigo-500" },
  { id: 2, title: "Gem Generator", description: "Promptinghilfe zur Gestaltung von individuellen GEM-Agenten im Bildungssektor (basiert auf Edugems.com).", link: "https://gemini.google.com/gem/1kH_2yF6lW2tWSzOV9Wr-7VZ_98-F960J?usp=sharing", category: "Tools", icon: <Wand2 className="w-6 h-6" />, color: "from-purple-500 to-pink-500" },
  { id: 3, title: "Sokratischer Lerncoach", description: "Allgemeiner Sokratischer Tutor, der streng auf Hilfe zur Ergebnisfindung statt Produktion von Lösungen achtet.", link: "https://gemini.google.com/gem/1GPMWpVcJWotJDIrCT-eDfSJpSPhgnGBy?usp=sharing", category: "Lernen", icon: <GraduationCap className="w-6 h-6" />, color: "from-emerald-500 to-teal-500" },
  { id: 4, title: "Economics Mastermind", description: "Spezielles Tool zur Planung des Unterrichtes im Fach Wirtschaftslehre in Hessen (KCBG für Berufliche Gymnasien).", link: "https://gemini.google.com/gem/1hiBFrtNI8BFddMWcL-LZRTGj_G7_pyMT?usp=sharing", category: "Wirtschaft", icon: <TrendingUp className="w-6 h-6" />, color: "from-amber-500 to-orange-500" },
  { id: 5, title: "Vertretungsstunden Planer", description: "Tool zur schnellen Planung von (fachfremden) Vertretungsstunden unter Einbeziehung der Schüler.", link: "https://gemini.google.com/gem/1GHdiLM6HsIP8vLgGZ3XpUfQxlpDyfEwj?usp=sharing", category: "Schulalltag", icon: <Clock className="w-6 h-6" />, color: "from-rose-500 to-red-500" },
  { id: 6, title: "Politics Mastermind", description: "Spezielles Tool zur Planung des Unterrichtes im Fach Politik und Wirtschaft in Hessen (KCGO).", link: "https://gemini.google.com/gem/11ngV6770tGKIeCDmR9dMnK-sW4qFqUrn?usp=sharing", category: "Politik", icon: <Landmark className="w-6 h-6" />, color: "from-blue-600 to-cyan-600" },
  { id: 7, title: "Nexus politischer Entscheidungen", description: "Simulation politischer Entscheidungen aktueller Problemstellungen anhand simulierter Folgen.", link: "https://gemini.google.com/gem/1EwlDFvFQpZBih23NmdYPPwzBuR2s59wt?usp=sharing", category: "Politik", icon: <Network className="w-6 h-6" />, color: "from-violet-500 to-purple-600" },
  { id: 8, title: "Teach a Robot (Oberstufe)", description: "Das Gem agiert als Roboter mit gelöschtem Speicher. Nutzer müssen das Wissen wiederherstellen.", link: "https://gemini.google.com/gem/1w92C8w42ecoyI5VfugDrmICxCtt7xb7h?usp=sharing", category: "Lernen", icon: <Cpu className="w-6 h-6" />, color: "from-gray-600 to-slate-800" },
  { id: 9, title: "Teach a Robot (Mittelstufe)", description: "Angepasste Version des Robot-Szenarios für die Mittelstufe zur Wissensfestigung.", link: "https://gemini.google.com/gem/1n6ru5NhZ_STGlNvDQUatYzC5h5kztoif?usp=sharing", category: "Lernen", icon: <Cpu className="w-6 h-6" />, color: "from-slate-400 to-slate-600" },
  { id: 10, title: "Document Architect", description: "Tool zur Umwandlung von Dokumenten oder Text in PDF nach festgelegten Designvorgaben.", link: "https://gemini.google.com/gem/1HtRVv-Om6lckykSjlApxKV-Kul-STeQg?usp=sharing", category: "Tools", icon: <FileText className="w-6 h-6" />, color: "from-blue-400 to-indigo-400" },
  { id: 11, title: "Lernberater Abivorbereitung", description: "Coaching zu KCBG Hessen Wirtschaftslehre inkl. Kompetenzbewertung und Persona-Wahl.", link: "https://gemini.google.com/gem/1qHprW7Nc5ZKoG3eTU1zKMk38NG54p3jh?usp=sharing", category: "Lernen", icon: <BookOpen className="w-6 h-6" />, color: "from-emerald-400 to-green-600" },
  { id: 12, title: "10 Fragen Kontest", description: "Generiert 10 Fragen mit steigender Schwierigkeit und teilt Klassen in Wettbewerbs-Gruppen ein.", link: "https://gemini.google.com/gem/1zY8dKq6LmX1bF7clQLI_zjecLdvRtpBQ?usp=sharing", category: "Gamification", icon: <Trophy className="w-6 h-6" />, color: "from-yellow-500 to-orange-400" }
];

const TOOLS_LIST = [
  { id: "material", category: "Unterricht & Material", icon: <FileText className="w-4 h-4" />, items: [
    { name: "NotebookLM", url: "https://notebooklm.google.com", desc: "Lerntool für Dokumente, erstellt Videos, Präsentationen und Podcasts." },
    { name: "MagicSchool.ai", url: "https://www.magicschool.ai", desc: "All-in-One: Unterrichtspläne, differenzierte Texte und IEP-Vorschläge." },
    { name: "Diffit", url: "https://web.diffit.me", desc: "Wandelt jeden Text in Materialpakete für spezifische Leseniveaus um." },
    { name: "Claude.ai", url: "https://claude.ai", desc: "Besonders natürlicher Schreibstil für komplexe pädagogische Texte." },
    { name: "Eduaide.ai", url: "https://www.eduaide.ai", desc: "Über 100 Ressourcen-Typen zur Unterrichtsgestaltung und Gamification." }
  ]},
  { id: "recherche", category: "Recherche & Fakten", icon: <Search className="w-4 h-4" />, items: [
    { name: "Perplexity", url: "https://www.perplexity.ai/", desc: "Echtzeitrecherche mit Quellenangaben. Fokus auf Transparenz und Fakten." },
    { name: "Use.ai", url: "https://use.ai/", desc: "Nutzung aller gängigen LLM Modelle im Wechsel oder Vergleich." },
    { name: "Google Gemini", url: "https://gemini.google.com", desc: "Sprachmodell für Gems, Bilder, Videos, Präsentationen und Coding." },
    { name: "Consensus", url: "https://consensus.app", desc: "Suchmaschine ausschließlich basierend auf wissenschaftlichen Studien." },
    { name: "Scite.ai", url: "https://scite.ai", desc: "Prüfung der Zitierhistorie und Validität wissenschaftlicher Aussagen." }
  ]},
  { id: "medien", category: "Visualisierung & Medien", icon: <ImageIcon className="w-4 h-4" />, items: [
    { name: "Napkin.ai", url: "https://www.napkin.ai/", desc: "Generierung von vielfältig anpassbaren Visualisierungen aus Texten." },
    { name: "Playground", url: "https://playground.com/", desc: "Grafikdesign und Bildgenerierung mit Editierfunktionen." },
    { name: "Mureka.ai", url: "https://www.mureka.ai/", desc: "Generierung von Songs und Liedern nach individuellen Vorgaben." },
    { name: "Gamma.app", url: "https://gamma.app", desc: "Erstellt Präsentationen, Webseiten oder Dokumente aus Textvorgaben." },
    { name: "HeyGen", url: "https://www.heygen.com", desc: "Videogenerator für sprechende Avatare (historische Persönlichkeiten)." },
    { name: "Canva Magic Studio", url: "https://www.canva.com", desc: "KI-Design-Tools für Layouts, Text-zu-Bild und Bildbearbeitung." }
  ]},
  { id: "interaktion", category: "Interaktion & Aktivierung", icon: <Users className="w-4 h-4" />, items: [
    { name: "Mizou", url: "https://mizou.com", desc: "Geschützte KI-Tutoren für Schüler (Hilfe zur Selbsthilfe)." },
    { name: "Curipod", url: "https://curipod.com", desc: "Interaktive Präsentationsplattform mit Sofort-Auswertung." },
    { name: "Conker.ai", url: "https://www.conker.ai", desc: "Blitzschnelles Tool für Quizze (Export in Google Forms)." },
    { name: "DeepL Write", url: "https://www.deepl.com/write", desc: "Verbesserung von Grammatik, Stil und Ausdruck (DE/EN)." },
    { name: "WolframAlpha", url: "https://www.wolframalpha.com", desc: "Rechnende Wissensmaschine mit schrittweisen Lösungswegen." },
    { name: "Screenpal", url: "https://screenpal.com", desc: "KI-Videobearbeitung und automatische Untertitelung." }
  ]},
  { id: "fortgeschrittene", category: "Spezial-Tools", icon: <Zap className="w-4 h-4" />, items: [
    { name: "ElevenLabs", url: "https://elevenlabs.io", desc: "Lebensechte Sprachausgabe (TTS) für Hörverstehen und Inklusion." },
    { name: "Tome", url: "https://tome.app", desc: "Fokus auf narratives Storytelling durch KI-Layouts." },
    { name: "v0.dev", url: "https://v0.dev", desc: "Generiert funktionale Benutzeroberflächen und Web-Code." },
    { name: "Mapdeduce", url: "https://www.mapdeduce.com", desc: "Analysiert Dokumente auf logische Fehler und fasst Kernpunkte zusammen." }
  ]},
  { id: "schueler", category: "Speziell für Schüler", icon: <GraduationCap className="w-4 h-4" />, items: [
    { name: "Khanmigo", url: "https://www.khanacademy.org", desc: "KI-Lerncoach, der Aufgaben erklärt, ohne die Lösung zu verraten." },
    { name: "Quizlet Q-Chat", url: "https://quizlet.com", desc: "Interaktiver Lernchat zur Abfrage von Vokabeln und Konzepten." },
    { name: "Goblin.tools", url: "https://goblin.tools", desc: "Bricht komplexe Aufgaben in machbare Checklisten-Schritte herunter." },
    { name: "StudySmarter", url: "https://www.studysmarter.de", desc: "Erstellt Karteikarten und Zusammenfassungen aus Unterlagen." },
    { name: "LanguageReactor", url: "https://www.languagereactor.com", desc: "Browser-Erweiterung für YouTube/Netflix mit doppelten Untertiteln." }
  ]}
];

const WORKFLOW_GROUPS = [
  { id: "lehrkraefte", title: "Lehrkräfte", icon: <Users className="w-5 h-5" />, items: [
    { title: "Differenzierte Materialerstellung", desc: "Von der Recherche bis zum Inklusionsmaterial für alle Niveaus.", steps: [
      { tool: "Perplexity", action: "Fakten & Quellen recherchieren", detail: "Sichere Fakten und aktuelle Quellen für ein Thema sammeln, um eine verlässliche Informationsbasis zu schaffen." }, 
      { tool: "Diffit", action: "Materialpakete & Niveaus", detail: "Den gefundenen Text hochladen, um automatisch Lesetexte, Fragen und Vokabellisten für verschiedene Klassenstufen zu generieren." }, 
      { tool: "Napkin.ai", action: "Inhalte visualisieren", detail: "Komplexe Zusammenhänge aus dem Text in anschauliche Diagramme oder Mindmaps umwandeln lassen." }, 
      { tool: "DeepL Write", action: "Sprachlicher Feinschliff", detail: "Texte auf grammatikalische Korrektheit prüfen und den pädagogischen Tonfall optimieren." }
    ]},
    { title: "Sokratische Lernumgebungen", desc: "Begleitung von Lernprozessen ohne direkte Lösungsvorgabe.", steps: [
      { tool: "NotebookLM", action: "Materialien strukturieren", detail: "Eigene PDFs oder Skripte hochladen, damit die KI den Kontext deiner spezifischen Unterrichtseinheit versteht." }, 
      { tool: "Mizou", action: "KI-Tutor konfigurieren", detail: "Einen geschützten Chatbot erstellen, der Schüler durch gezielte Fragen zur eigenen Lösung führt." }, 
      { tool: "Conker.ai", action: "Formativen Check erstellen", detail: "Ein kurzes Quiz generieren, um den Lernfortschritt am Ende der Einheit spielerisch zu prüfen." }
    ]},
    { title: "Multimediale Aufbereitung", desc: "Geschichte und Politik durch KI-Medien lebendig gestalten.", steps: [
      { tool: "Google Gemini", action: "Historisches Skript", detail: "Ein Skript oder Interview aus der Sicht einer historischen Person verfassen lassen." }, 
      { tool: "Playground", action: "Bildgenerierung", detail: "Ein authentisches Porträt oder eine Szenerie passend zum Skript generieren." }, 
      { tool: "HeyGen", action: "Avatar-Video", detail: "Das Bild zum Leben erwecken: Der Avatar spricht das verfasste Skript lippensynchron." },
      { tool: "Mureka.ai", action: "Atmo & Musik", detail: "Eine passende musikalische Untermalung generieren, um die Stimmung des Mediums zu verstärken." }
    ]},
    { title: "Wissenschaftspropädeutik", desc: "Methodische Begleitung komplexer wissenschaftlicher Arbeiten.", steps: [
      { tool: "Consensus", action: "Evidenzbasierte Recherche", detail: "Wissenschaftliche Studien zu einer Forschungsfrage finden, die belegbare Antworten liefern." }, 
      { tool: "Mapdeduce", action: "Quellen-Analyse", detail: "Mehrere lange Paper hochladen, um Kernargumente und logische Widersprüche zu identifizieren." }, 
      { tool: "Use.ai", action: "KI-Vergleich", detail: "Thesen von verschiedenen Sprachmodellen (Claude, GPT, Gemini) prüfen lassen, um Perspektivenvielfalt zu erhalten." },
      { tool: "Gamma.app", action: "Ergebnis-Präsentation", detail: "Die Analyseergebnisse automatisch in eine strukturierte, ästhetische Präsentation überführen." }
    ]},
    { title: "Formative Feedbackschleifen", desc: "Individuelle Rückmeldung im Schreibprozess für jeden Schüler.", steps: [
      { tool: "Google Gemini", action: "Kriterienbasiertes Feedback", detail: "Schülertexte gegen einen Erwartungshorizont prüfen lassen und konkrete Tipps geben." }, 
      { tool: "DeepL Write", action: "Stilistische Überarbeitung", detail: "Schüler nutzen das Tool, um ihre Argumente präziser und fachsprachlich korrekter zu formulieren." }, 
      { tool: "Napkin.ai", action: "Struktur-Visualisierung", detail: "Die Argumentationskette des eigenen Textes grafisch darstellen, um Logikfehler zu finden." }
    ]}
  ]},
  { id: "schueler", title: "Schüler", icon: <GraduationCap className="w-5 h-5" />, items: [
    { title: "Lernprojekt-Struktur", steps: [
      { tool: "Goblin.tools", action: "To-Do-Liste erstellen", detail: "Ein komplexes Thema wie 'Referat' eingeben und in winzige, machbare Aufgaben zerlegen lassen." }, 
      { tool: "Perplexity", action: "Quellen recherchieren", detail: "Fakten suchen und direkt die passenden Web-Links für das Literaturverzeichnis sichern." }, 
      { tool: "Napkin.ai", action: "Mindmap generieren", detail: "Die gesammelten Informationen grafisch ordnen, um die Gliederung der Arbeit festzulegen." }
    ]},
    { title: "Vokabeltraining im Kontext", steps: [
      { tool: "LanguageReactor", action: "Kontextuelles Lernen", detail: "Fremdsprachige Videos schauen und unbekannte Wörter direkt im Untertitel speichern." }, 
      { tool: "Quizlet Q-Chat", action: "Dialogisches Üben", detail: "Die neuen Wörter in einem interaktiven Chat anwenden, statt nur auswendig zu lernen." }, 
      { tool: "ElevenLabs", action: "Hörtraining", detail: "Eigene Texte in der Zielsprache vorlesen lassen, um die korrekte Aussprache zu verinnerlichen." }
    ]},
    { title: "Mathe-Problemlösung", steps: [
      { tool: "WolframAlpha", action: "Lösungsweg verstehen", detail: "Eine Aufgabe eingeben, um nicht nur das Ergebnis, sondern jeden einzelnen Rechenschritt zu sehen." }, 
      { tool: "Khanmigo", action: "Verständnisfragen", detail: "Fragen stellen, WARUM ein bestimmter Rechenschritt nötig ist, ohne dass die KI vorsagt." }, 
      { tool: "Conker.ai", action: "Ähnliche Übungen", detail: "Zusätzliche Übungsaufgaben zum gleichen Schwierigkeitsgrad generieren lassen." }
    ]},
    { title: "Präsentations-Design", steps: [
      { tool: "NotebookLM", action: "Inhalts-Gliederung", detail: "Eigene Notizen hochladen und eine logische Struktur für die Folien vorschlagen lassen." }, 
      { tool: "Gamma.app", action: "Folien-Layout", detail: "Die Gliederung eingeben und automatisch ein modernes Design für die gesamte Präsentation erstellen." }, 
      { tool: "Playground", action: "Einzigartige Bilder", detail: "Passende, urheberrechtsfreie Bilder für die Folien generieren, statt Google-Bilder zu nutzen." }
    ]},
    { title: "Kriteriengeleitete Textoptimierung", steps: [
      { tool: "DeepL Write", action: "Grammatik & Stil", detail: "Den eigenen Text auf Fehler prüfen und elegantere Formulierungen wählen." }, 
      { tool: "Google Gemini", action: "Logik-Feedback", detail: "Fragen: 'Welche Gegenargumente fehlen in meinem Text noch?'" }
    ]},
    { title: "Systematische Prüfungsvorbereitung", steps: [
      { tool: "StudySmarter", action: "Lernplan & Karten", detail: "Aus Schulunterlagen automatisch Karteikarten erstellen und Lernzeiten planen." }, 
      { tool: "Quizlet Q-Chat", action: "Wissens-Abfrage", detail: "Sich von der KI prüfen lassen, um Lücken in der Theorie zu finden." }, 
      { tool: "NotebookLM", action: "Wiederholungs-Podcast", detail: "Einen KI-generierten Podcast aus den Lernzetteln hören, um unterwegs zu wiederholen." }
    ]},
    { title: "Analyse komplexer Sachtexte", steps: [
      { tool: "Mapdeduce", action: "Kernargumente finden", detail: "Lange Texte analysieren, um sofort die Hauptthesen und Widersprüche zu sehen." }, 
      { tool: "Perplexity", action: "Faktenrecherche", detail: "Im Text genannte Namen oder Daten auf Richtigkeit prüfen." }, 
      { tool: "Napkin.ai", action: "Grafische Darstellung", detail: "Die Textstruktur in ein Flussdiagramm umwandeln." }
    ]},
    { title: "Visuelle Wissensrepräsentation", steps: [
      { tool: "NotebookLM", action: "Fachbegriffe extrahieren", detail: "Die wichtigsten Konzepte aus einer Unterrichtseinheit auflisten lassen." }, 
      { tool: "Napkin.ai", action: "Hierarchisches Diagramm", detail: "Die Begriffe in eine logische Ordnung (Ober-/Unterbegriffe) bringen." }, 
      { tool: "Google Gemini", action: "Fachliche Prüfung", detail: "Das Diagramm auf Richtigkeit der Verknüpfungen prüfen lassen." }
    ]},
    { title: "Simuliertes Peer-Review", steps: [
      { tool: "Google Gemini", action: "Kritischer Mitschüler", detail: "Die KI bitten: 'Reagiere als kritischer Mitschüler auf meine folgende These...'" }, 
      { tool: "DeepL Write", action: "Textüberarbeitung", detail: "Basierend auf den Rückfragen die Argumente präzisieren." }, 
      { tool: "Claude", action: "Finaler Tonfall", detail: "Den Text auf einen wissenschaftlichen und kohärenten Ton prüfen lassen." }
    ]},
    { title: "Interaktionstraining", steps: [
      { tool: "Claude", action: "Rollenspiel", detail: "Ein simuliertes Gespräch (z.B. Bewerbung) in der Fremdsprache führen." }, 
      { tool: "ElevenLabs", action: "Audio-Ausgabe", detail: "Die KI-Antworten laut anhören, um das Hörverstehen zu trainieren." }, 
      { tool: "DeepL Write", action: "Fehleranalyse", detail: "Die eigenen Beiträge im Nachgang auf Fehler analysieren lassen." }
    ]}
  ]}
];

// --- KOMPONENTEN ---

const Modal = ({ title, isOpen, onClose, children }) => {
  if (!isOpen) return null;
  return (
    <div className="fixed inset-0 z-[100] flex items-center justify-center p-4 bg-slate-900/60 backdrop-blur-sm">
      <div className="bg-white rounded-3xl w-full max-w-2xl max-h-[85vh] overflow-hidden flex flex-col shadow-2xl">
        <div className="flex items-center justify-between p-6 border-b border-slate-100">
          <h3 className="text-xl font-black tracking-tight">{title}</h3>
          <button onClick={onClose} className="p-2 hover:bg-slate-100 rounded-full transition-colors">
            <X className="w-6 h-6" />
          </button>
        </div>
        <div className="p-8 overflow-y-auto text-slate-600 leading-relaxed space-y-4">
          {children}
        </div>
      </div>
    </div>
  );
};

const HorizontalNav = ({ items, activeId, onSelect }) => (
  <div className="flex overflow-x-auto no-scrollbar gap-2 pb-2 -mx-2 px-2 items-center justify-center">
    <div className="flex bg-white/60 backdrop-blur-md p-1.5 rounded-2xl border border-slate-200 shadow-sm min-w-max">
      {items.map(item => (
        <button
          key={item.id}
          onClick={() => onSelect(item.id)}
          className={`flex items-center gap-2 px-5 py-2.5 rounded-xl font-bold transition-all whitespace-nowrap ${
            activeId === item.id 
            ? 'bg-blue-600 text-white shadow-md shadow-blue-200 scale-105' 
            : 'text-slate-500 hover:bg-white hover:text-blue-600'
          }`}
        >
          {item.icon}
          <span>{item.label || item.category || item.title}</span>
        </button>
      ))}
    </div>
  </div>
);

const WorkflowCard = ({ wf, colorClass }) => (
  <div className="bg-white p-8 rounded-[2.5rem] border border-slate-200 shadow-sm relative overflow-hidden h-full flex flex-col group hover:border-blue-400 transition-all duration-300">
    <div className={`absolute top-0 right-0 w-32 h-32 ${colorClass} opacity-5 rounded-bl-full -mr-10 -mt-10 transition-transform group-hover:scale-110`} />
    <h4 className="font-black text-2xl text-slate-900 mb-2 relative z-10">{wf.title}</h4>
    {wf.desc && <p className="text-slate-500 text-sm font-medium italic mb-8 relative z-10 border-l-2 border-slate-100 pl-3">{wf.desc}</p>}
    <div className="space-y-8 relative z-10 flex-grow">
      {wf.steps.map((step, sIdx) => (
        <div key={sIdx} className="relative">
          <div className="flex items-start gap-5">
            <div className={`w-10 h-10 rounded-2xl ${colorClass.replace('bg-', 'bg-opacity-10 ')} flex items-center justify-center shrink-0 border border-current transition-all group-hover:shadow-lg`}>
              <span className="text-sm font-black">{sIdx + 1}</span>
            </div>
            <div className="flex-grow pt-1">
              <div className="flex items-center gap-2 mb-1">
                <span className="text-sm font-black text-slate-900">{step.tool}</span>
                <div className="h-px bg-slate-100 flex-grow" />
              </div>
              <div className="text-xs font-bold text-blue-600 uppercase tracking-widest mb-2">{step.action}</div>
              <p className="text-sm text-slate-500 leading-relaxed font-medium bg-slate-50/50 p-3 rounded-xl border border-slate-100/50">
                {step.detail}
              </p>
            </div>
          </div>
          {sIdx < wf.steps.length - 1 && (
            <div className="absolute left-5 top-10 w-px h-10 bg-slate-100 ml-[-0.5px]" />
          )}
        </div>
      ))}
    </div>
  </div>
);

export default function App() {
  const [activeTab, setActiveTab] = useState('gems');
  const [gemFilter, setGemFilter] = useState('Alle');
  const [activeToolboxCat, setActiveToolboxCat] = useState('material');
  const [activeWorkflowGroup, setActiveWorkflowGroup] = useState('lehrkraefte');
  
  const [showImpressum, setShowImpressum] = useState(false);
  const [showDatenschutz, setShowDatenschutz] = useState(false);

  const gemCategories = ['Alle', ...new Set(GEMS_DATA.map(g => g.category))];
  const filteredGems = gemFilter === 'Alle' ? GEMS_DATA : GEMS_DATA.filter(g => g.category === gemFilter);

  return (
    <div className="min-h-screen bg-[#f8fafc] text-slate-900 font-sans selection:bg-blue-100">
      
      {/* Modals */}
      <Modal title="Impressum" isOpen={showImpressum} onClose={() => setShowImpressum(false)}>
        <p className="font-bold underline uppercase tracking-tight text-blue-600">Angaben gemäß § 5 TMG:</p>
        <p className="text-lg font-black">Christian Neugebauer</p>
        <p className="text-slate-500 font-bold">Berufliche Schulen Bebra</p>
        <p className="font-bold pt-4">Kontakt:</p>
        <p className="flex items-center gap-2 font-medium"><Mail className="w-4 h-4" /> cneugebauer@gmx.net</p>
        <p className="text-xs pt-6 border-t border-slate-100 italic text-slate-400 font-medium">
          Verantwortlich für den Inhalt: Christian Neugebauer. Diese Webseite dient rein pädagogischen Zwecken im Rahmen der Lehrtätigkeit an den Beruflichen Schulen Bebra.
        </p>
      </Modal>

      <Modal title="Datenschutzerklärung" isOpen={showDatenschutz} onClose={() => setShowDatenschutz(false)}>
        <p className="font-medium">Diese Webseite ist eine rein statische Informationsseite. Es werden keine personenbezogenen Daten erhoben.</p>
        <p className="font-bold pt-4">Externe Links:</p>
        <p className="font-medium">Diese Seite enthält Links zu externen Diensten (z.B. Google Gemini). Sobald Sie diese Links anklicken, verlassen Sie diesen Verantwortungsbereich. Es gelten die Datenschutzbestimmungen der jeweiligen Anbieter.</p>
      </Modal>

      {/* Header & Main Nav */}
      <header className="bg-white/80 backdrop-blur-xl border-b border-slate-200 sticky top-0 z-[60] py-4 shadow-sm">
        <div className="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
          <div className="flex items-center gap-3">
            <div className="bg-blue-600 p-2 rounded-xl shadow-lg shadow-blue-200">
              <Sparkles className="w-5 h-5 text-white" />
            </div>
            <div>
              <h1 className="text-lg font-black tracking-tighter uppercase leading-none">KI-WERKSTATT</h1>
              <p className="text-[9px] text-slate-400 font-bold tracking-widest mt-0.5 uppercase">Christian Neugebauer • BSB</p>
            </div>
          </div>
          
          <HorizontalNav 
            items={[
              { id: 'gems', label: 'Eigene Gems', icon: <Layout className="w-4 h-4" /> },
              { id: 'tools', label: 'KI-Toolbox', icon: <Search className="w-4 h-4" /> },
              { id: 'workflows', label: 'Workflows', icon: <Rocket className="w-4 h-4" /> }
            ]}
            activeId={activeTab}
            onSelect={setActiveTab}
          />
        </div>
      </header>

      <main className="max-w-7xl mx-auto px-6 py-12">
        
        {/* TAB: GEMS */}
        {activeTab === 'gems' && (
          <div className="animate-in slide-in-from-bottom-2 duration-400">
            <div className="mb-10">
              <div className="flex items-center gap-3 mb-6 justify-center md:justify-start">
                <div className="w-8 h-1 bg-blue-600 rounded-full" />
                <h2 className="text-3xl font-black tracking-tight uppercase">Eigene Gems</h2>
              </div>
              <HorizontalNav 
                items={gemCategories.map(cat => ({ id: cat, label: cat }))}
                activeId={gemFilter}
                onSelect={setGemFilter}
              />
            </div>
            
            <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
              {filteredGems.map(gem => (
                <div key={gem.id} className="group bg-white border border-slate-200 rounded-3xl p-6 transition-all hover:border-blue-400 hover:shadow-xl hover:shadow-blue-500/5 flex flex-col h-full shadow-sm">
                  <div className={`inline-flex items-center justify-center p-3 rounded-2xl bg-gradient-to-br ${gem.color} mb-4 text-white shadow-md`}>
                    {gem.icon}
                  </div>
                  <div className="flex-grow">
                    <span className="text-[10px] uppercase tracking-widest text-blue-600 font-black bg-blue-50 px-2.5 py-1 rounded-full border border-blue-100">
                      {gem.category}
                    </span>
                    <h3 className="text-lg font-bold text-slate-900 mt-3 mb-2 group-hover:text-blue-600 transition-colors">
                      {gem.title}
                    </h3>
                    <p className="text-slate-500 text-sm leading-relaxed mb-6 font-medium">
                      {gem.description}
                    </p>
                  </div>
                  <a href={gem.link} target="_blank" rel="noopener noreferrer"
                    className="flex items-center justify-center gap-2 w-full py-3 bg-slate-900 hover:bg-blue-600 text-white rounded-2xl font-bold transition-all shadow-sm"
                  >
                    Gem öffnen <ExternalLink className="w-4 h-4" />
                  </a>
                </div>
              ))}
            </div>
          </div>
        )}

        {/* TAB: KI-TOOLBOX */}
        {activeTab === 'tools' && (
          <div className="animate-in slide-in-from-bottom-2 duration-400">
            <div className="mb-12">
              <div className="flex items-center gap-3 mb-6 justify-center md:justify-start">
                <div className="w-8 h-1 bg-blue-600 rounded-full" />
                <h2 className="text-3xl font-black tracking-tight uppercase">KI Toolbox</h2>
              </div>
              <HorizontalNav 
                items={TOOLS_LIST}
                activeId={activeToolboxCat}
                onSelect={setActiveToolboxCat}
              />
            </div>

            <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
              {TOOLS_LIST.find(c => c.id === activeToolboxCat).items.map((tool, idx) => (
                <a key={idx} href={tool.url} target="_blank" rel="noopener noreferrer"
                  className="p-6 bg-white border border-slate-200 rounded-3xl hover:shadow-xl hover:border-blue-400 transition-all group shadow-sm flex flex-col justify-between"
                >
                  <div>
                    <div className="flex justify-between items-center mb-3">
                      <h4 className="font-bold text-lg text-slate-900 group-hover:text-blue-600 transition-colors">{tool.name}</h4>
                      <div className="p-2 bg-slate-50 rounded-xl text-slate-300 group-hover:text-blue-500 transition-colors">
                        <ExternalLink className="w-4 h-4" />
                      </div>
                    </div>
                    <p className="text-sm text-slate-500 leading-relaxed font-medium">{tool.desc}</p>
                  </div>
                </a>
              ))}
            </div>
          </div>
        )}

        {/* TAB: WORKFLOWS */}
        {activeTab === 'workflows' && (
          <div className="animate-in slide-in-from-bottom-2 duration-400">
            <div className="mb-12">
              <div className="flex items-center gap-3 mb-6 justify-center md:justify-start">
                <div className="w-8 h-1 bg-blue-600 rounded-full" />
                <h2 className="text-3xl font-black tracking-tight uppercase">Workflows</h2>
              </div>
              <HorizontalNav 
                items={WORKFLOW_GROUPS.map(g => ({ id: g.id, label: g.title, icon: g.icon }))}
                activeId={activeWorkflowGroup}
                onSelect={setActiveWorkflowGroup}
              />
            </div>

            <div className="grid grid-cols-1 lg:grid-cols-2 gap-10">
              {WORKFLOW_GROUPS.find(g => g.id === activeWorkflowGroup).items.map((wf, idx) => (
                <WorkflowCard 
                  key={idx} 
                  wf={wf} 
                  colorClass={activeWorkflowGroup === 'lehrkraefte' ? 'bg-blue-500' : 'bg-emerald-500'} 
                />
              ))}
            </div>
          </div>
        )}

      </main>

      {/* Footer */}
      <footer className="bg-white border-t border-slate-200 py-16 mt-20">
        <div className="max-w-7xl mx-auto px-6">
          <div className="flex flex-col md:flex-row justify-between items-center gap-10 mb-12">
            <div className="flex items-center gap-3">
              <div className="bg-slate-900 p-2 rounded-xl">
                <Sparkles className="w-5 h-5 text-white" />
              </div>
              <span className="font-black text-xl tracking-tighter uppercase">KI-WERKSTATT</span>
            </div>
            <div className="flex flex-wrap justify-center gap-8 text-xs font-black text-slate-400 uppercase tracking-widest">
              <button onClick={() => setShowImpressum(true)} className="hover:text-blue-600 transition-colors">Impressum</button>
              <button onClick={() => setShowDatenschutz(true)} className="hover:text-blue-600 transition-colors">Datenschutz</button>
              <a href="mailto:cneugebauer@gmx.net" className="hover:text-blue-600 transition-colors flex items-center gap-2">
                <Mail className="w-4 h-4" /> Kontakt
              </a>
            </div>
          </div>
          <div className="text-center pt-8 border-t border-slate-100">
            <p className="text-sm text-slate-500 font-black mb-1 uppercase tracking-tight">
              Christian Neugebauer • Berufliche Schulen Bebra
            </p>
            <div className="flex justify-center gap-4 mt-8">
              <a href="https://github.com" className="p-3 bg-slate-50 rounded-2xl text-slate-400 hover:text-slate-900 transition-all border border-transparent shadow-sm">
                <Github className="w-5 h-5" />
              </a>
              <a href="#" className="p-3 bg-slate-50 rounded-2xl text-slate-400 hover:text-blue-600 transition-all border border-transparent shadow-sm">
                <Info className="w-5 h-5" />
              </a>
            </div>
          </div>
        </div>
      </footer>
    </div>
  );
}
