### Unit 1: Introduction to Natural Language Processing
- **About NLP and Its Applications**
  - **Definition of NLP**: NLP is a field at the intersection of computer science, artificial intelligence, and linguistics, focused on the interaction between computers and human languages.
  - **Applications**:
    - **Sentiment Analysis**: Identifying and categorizing opinions expressed in text.
    - **Machine Translation**: Translating text or speech from one language to another.
    - **Chatbots and Virtual Assistants**: Automated conversational agents like Siri, Alexa.
    - **Information Retrieval**: Search engines like Google.
    - **Text Summarization**: Automatically generating summaries of large documents.
    - **Speech Recognition**: Converting spoken language into text.

- **Evaluate Language Understanding Systems**
  - **Evaluation Metrics**: Precision, recall, F1 score, BLEU score for translation, etc.
  - **Benchmarks**: Standard datasets and tasks used to measure system performance.

- **NLU Systems**
  - **Natural Language Understanding (NLU)**: Focuses on comprehending and interpreting human language in a meaningful way.
  - **Components**: Syntax (structure), semantics (meaning), pragmatics (context), and discourse (interaction).

### Unit 2: Semantics
- **Influence of NLP on Database Application Interfaces**
  - **Natural Language Interfaces to Databases (NLIDB)**: Enabling users to interact with databases using natural language queries.
  - **Examples**: SQL queries generated from user input.

- **Machine Translation Application**
  - **Approaches**:
    - **Rule-Based**: Using linguistic rules.
    - **Statistical**: Using statistical models trained on bilingual text corpora.
    - **Neural**: Using deep learning models, particularly neural networks.
  - **Challenges**: Ambiguity, context, idioms, cultural nuances.

- **Concept of Semantics**
  - **Semantics**: Study of meaning in language; understanding how words and sentences convey meaning.
  - **Lexical Semantics**: Meaning of words and relationships between them (synonyms, antonyms).
  - **Compositional Semantics**: How meanings of individual words combine to form the meaning of a sentence.

- **Concept of Knowledge**
  - **Knowledge Representation**: Ways to represent information about the world in a form that a computer system can utilize to solve complex tasks.
  - **Ontology**: A structured framework to organize information and define relationships.

### Unit 3: Grammar and Parsing
- **Parsing and Grammar**
  - **Parsing**: Process of analyzing a string of symbols in natural language according to the rules of grammar.
  - **Grammar**: Set of rules that define the structure of sentences in a language.

- **Top-Down and Bottom-Up Parsing Algorithms**
  - **Top-Down Parsing**: Starting from the highest-level construct (root) and breaking it down into its components (leaves).
    - Example: Recursive descent parser.
  - **Bottom-Up Parsing**: Starting from the input symbols and attempting to combine them into higher-level constructs until the root is reached.
    - Example: Shift-reduce parser.

- **System Grammar and Augmented Transition Network**
  - **System Grammar**: Frameworks defining how sentences are structured.
  - **Augmented Transition Network (ATN)**: A type of state machine used for parsing that includes actions to be performed at each state transition.

- **Morphological Analysis**
  - **Morphology**: Study of the structure and form of words.
  - **Morphological Analysis**: Process of understanding the structure of words and their parts (roots, prefixes, suffixes).

### Unit 4: Grammar for Natural Language
- **Verb Phrases**
  - **Structure and Usage**: How verb phrases are constructed and their role in conveying action, state, or occurrence.

- **Movement Phenomenon in Language**
  - **Syntactic Movements**: How elements in a sentence can be moved from one position to another (e.g., questions, passive constructions).
    - Example: "What did you eat?" (object "what" moved to the front).

- **Handling Questions in Context-Free Grammar**
  - **Context-Free Grammar (CFG)**: Type of grammar where production rules can be applied regardless of context.
  - **Parsing Questions**: Techniques for handling interrogative sentences.

- **Human Preference**
  - **Natural Preferences**: How humans naturally prefer to structure language and interpret sentences.
  - **Implications for NLP**: Understanding these preferences can improve the design of NLP systems to make them more intuitive.

### Unit 5: Ambiguity Resolution
- **Probabilistic Context-Free Grammar (PCFG)**
  - **PCFG**: Extension of context-free grammar where each production rule has a probability.
  - **Usage**: Helps in disambiguating sentences by considering the most likely parse.

- **Statistical Methods for Ambiguity Resolution**
  - **Statistical Models**: Using probabilities and statistics to resolve ambiguities.
  - **Techniques**: Hidden Markov Models (HMM), Conditional Random Fields (CRF), Maximum Entropy Models.

- **Probabilistic Language Processing**
  - **Approaches**: Using probabilistic methods to handle uncertainty and variability in language.
  - **Applications**: Part-of-speech tagging, named entity recognition, parsing.

- **Logical Form and Best First Parsing**
  - **Logical Form**: Representation of the syntactic structure and meaning of sentences.
  - **Best First Parsing**: Parsing method that explores the most promising nodes first based on a heuristic.