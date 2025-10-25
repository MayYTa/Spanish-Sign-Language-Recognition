# Spanish Sign Language Recognition Program

**(espanhol/spanish)**
Desarrollar un sistema de reconocimiento de frases en Lengua de Señas Española (LSE) orientado al ámbito educativo de primaria. El sistema usará señal visual y datos estructurados de manos (posición 2D/3D, orientación, estado de dedos) extraídos por un detector de manos preentrenado. Sobre esas características temporales se entrenará un modelo secuencial (LSTM) para reconocer un conjunto acotado de frases. El sistema producirá una traducción literal en forma de secuencia de tokens de señas, que luego será pasada a un modelo de lenguaje natural para convertir esa representación literal en oraciones legibles en español. Se evaluará precisión de reconocimiento, calidad de la traducción literal y comprensibilidad del texto final por hablantes nativos. 

**(ingles/english)**
Develop a phrase-level recognition system for Spanish Sign Language (LSE) targeting primary-education vocabulary. The system will use visual input and structured hand data (2D/3D coordinates, orientation, finger states) extracted by a pre-trained hand/keypoint detector. Temporal sequences of those features will be modeled with a sequential network (LSTM). The system will output a literal translation as a sequence of sign tokens, which will be fed to a natural language model or rule-based postprocessor to produce fluent Spanish sentences. Evaluation will measure recognition accuracy, literal-translation quality, and final text comprehensibility by native speakers.

---


