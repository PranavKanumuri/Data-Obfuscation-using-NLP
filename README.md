# Data-Obfuscation-using-NLP

This is a simple NLP proejct that automatically obfuscates sensitive information from Perosnal Credit Information (PCI), Personal Health Information (PHI) and Court Hearings. It identifies and masks entities such as person names, organizations, dates, and monetary values to protect privacy while preserving the document structure and non-sensitive content.

It uses NER to identify entities and they are represented using BeautifulSoup. Since the data being used in this exmaple is court hearings, I selected the entities that I deem to be of sensitive content and select those entities to be obfuscated or hidden. With the addition of other sentences as keywords, I obfuscated words that have not been identified by NER. 

In Conclusion, the project relies on SpaCy as the core NLP library providing entity recognition capabilities. BeautifulSoup handles XML parsing and navigation, while displaCy offers entity visualization for debugging and verification when needed.

