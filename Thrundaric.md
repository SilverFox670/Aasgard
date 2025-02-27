# Thrundaric Language System Enhancements

## 0 Event-Driven Architecture Enhancements  
currently the application is all built through the UI. this is fine for now, but would be nice to have my infrastructure as code for more thorough testing of expected behaviors. especially for the AI/prompt engineering spaces.
- [ ] **Choose an IAC technology** Terraform, SAM, CDK, CDK For Terraform all have their advantages and disadvantages  
- [ ] **Rewrite and deploy infrastructure** 
- [ ] **Containerize and deploy application logic**

## 1 Event-Driven Architecture Enhancements  
- [ ] **Refactor Lambdas** to process batched events instead of single entries (better performance)  
- [ ] **Dead Letter Queue (DLQ)** for failed events (AWS SQS or SNS)  
- [ ] **Monitoring & Logging** (AWS CloudWatch to track ingestion issues)  

## 2 Query & Retrieval System  
Once words and rules are stored, **you need a way to retrieve and use them**:  
- [ ] **GraphQL or REST API** to expose the dictionary & grammar rules  
- [ ] **Search Indexing** (Elasticsearch/OpenSearch for efficient lookups)  
- [ ] **Precomputed Relations** (e.g., "Find all verbs derived from root X")  

## 3 AI-Based Language Agent 🤖  
An AI **agent** that interacts with the API to manage language creation and retrieval:  
- [ ] **Conversational API Access** (Chat-based interaction for querying Thrundaric rules, words, or grammar)  
- [ ] **Automated Word Suggestion** (AI suggests new words following phonotactic rules)  
- [ ] **Grammar & Syntax Validation** (AI verifies whether a sentence is grammatically correct)
- [ ] **Common English to Thrundaric Conversion** (AI can translate sentances into Thrundaric on demand)

## 4 Word Formation & Generation  
A dynamic **word generator** can ensure consistency when adding new words:  
- [ ] **Morpheme-Based Word Synthesis** (build new words dynamically using stored morpheme rules)  
- [ ] **Root-Based Word Derivation** (e.g., generate related words based on defined transformations)  
- [ ] **Phonotactic Constraint Checker** (to enforce language sound rules)  

## 5 Sentence Parsing & Construction  
To **validate sentence structure** in Thrundaric and construct new sentences:  
- [ ] **Parser** (validates if a sentence follows Thrundaric syntax rules)  
- [ ] **Sentence Generator** (given a meaning, generate Thrundaric sentence structures)  
- [ ] **Rule Conflict Detection** (check if new grammar rules contradict existing ones)  

## 6 Machine Learning / AI Integration  
For advanced language features and usability:  
- [ ] **Language Model Training** (Train a small model for natural Thrundaric sentence generation)  
- [ ] **Speech Synthesis & Recognition** (Convert written Thrundaric to speech & vice versa)  
- [ ] **Handwritten Input for Thrundaric** (AI deciphers handwritten words and translates them)  

## 7 Developer & User Tools  
To make Thrundaric accessible and usable:  
- [ ] **Web-based Dictionary & Grammar Explorer**  
- [ ] **CLI or API for automated word lookup & validation**  
- [ ] **Interactive Language Learning Tool** (think Duolingo for Thrundaric!)  

## 8 Writing System (Orthography) ✍️  
Thrundaric needs a **custom writing system**, leveraging AI to assist in character creation:  
- [ ] **AI-Generated Glyphs** (AI produces new Thrundaric characters based on phoneme mappings)  
- [ ] **Automated Character Storage** (Systematically stores and indexes glyphs for retrieval)  
- [ ] **Writing System Rules** (Defines how phonemes map to characters, handling diacritics, ligatures, etc.)  
- [ ] **Font & Script Generation** (Create a unique script or font for digital use)  
- [ ] **Handwriting Recognition** (Train AI to recognize written Thrundaric symbols)

## 9 Data Validation & Versioning  
- [ ] **Versioned Rulesets** (allow rollback of grammar changes)  
- [ ] **Audit Logs** (track changes to grammar rules, word entries, etc.)  

## 🔥 Future Expansions  
- [ ] **Text-to-Image Generation for Script Visualization**  
- [ ] **Thrundaric Name Generator** (Create character names following phonetic rules)  
- [ ] **AI-Assisted Storytelling** (Generate texts in Thrundaric based on prompts)  
