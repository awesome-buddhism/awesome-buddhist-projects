# Awesome-Buddhist-Open-Sourse Projects
- **♊ [Gemini](https://github.com/awesome-buddhism/awesome-buddhist-projects/tree/main?tab=readme-ov-file#gemini-1)**
- **🤖 [Claude](https://github.com/awesome-buddhism/awesome-buddhist-projects/blob/main/README.md#claude)**
- **💬 (Chatgpt)** 
- **🧠 (Perplexity)**

### Gemini
#### Phase 1: Gathering Authentic Buddhist Sources
- [buda-base](https://github.com/buda-base): (Github) Umbrella organization for BDRC's open-source projects, supporting digitization and preservation infrastructure. Robust ontology, Linked Open Data structure, various tools for managing Buddhist texts.
- [OpenPecha/Toolkit / toolkit-v2](https://github.com/OpenPecha): (Github) Tools for creating, editing, and exporting texts and annotations, foundational for processing gathered sources. Comprehensive text management, annotation capabilities.

#### Phase 2: Preserving as Audio and Images
- [buda-base/tibetan-ocr-app](https://github.com/buda-base/tibetan-ocr-app): Offline OCR application for Tibetan manuscripts and PDFs. Batch OCR, plain text/PageXML export, dewarping, Wylie conversion.
- [buda-base/tibetan-ocr-training](https://github.com/buda-base/tibetan-ocr-training ): raining code for Tibetan OCR models. Supports development and improvement of Tibetan OCR accuracy.
- [buda-base/buda-iiif-server](https://github.com/buda-base/buda-iiif-server): Image server based on IIIF standards for displaying digitized content. IIIF compliance for image sharing and interoperability.

#### Phase 3: Converting into Searchable Digital Text
- [buda-base/tibetan-ocr-app](https://github.com/buda-base/tibetan-ocr-app ): Offline OCR application for Tibetan manuscripts and PDFs. Batch OCR, plain text/PageXML export, supports various Tibetan styles.
- [GmGniap/Burmese-Table-OCR](https://github.com/GmGniap/Burmese-Table-OCR): Extracts text from tables in Burmese images using OpenCV and PyTesseract. Table detection, Burmese text extraction.
- [nchanko/Myanmar-Ebook-OCR](https://github.com/nchanko/Myanmar-Ebook-OCR) : OCR tool using Tesseract for Myanmar-based text in PNGs and PDFs. Converts images/PDFs to TXT, supports Myanmar and English.
- [OpenInstituteCambodia/KhmerOCR_Website](https://github.com/OpenInstituteCambodia/KhmerOCR_Website): Simple homepage for Khmer OCR with an API for image-to-text conversion. API for OCR, supports Khmer.

####
####
####
- []() 
### Claude
#### Phase 1-2 Collection Assessment & Physical **Preparation**
- [BDRC Platform Components](https://github.com/buda-base): Buddhist Digital Resource Center's core technical infrastructure manages 28+ million pages across multiple Buddhist traditions. Collection management, metadata organization, preservation planning
- [BDRC Public Digital Library]( http://library.bdrc.io): Main web interface for Buddhist Digital Archives. IIIF-compliant manuscript viewing, advanced search. Collection access, digital preservation interface

#### Phase 3-4: Image Capture & Preprocessing
- [BDRC IIIF Server](https://github.com/buda-base/buda-iiif-server): IIIF image server for digitized manuscripts. Zoom, annotation, multi-manuscript comparison. High-resolution image serving, image processing.
- [BDRC Mirador Viewer](https://github.com/buda-base/mirador): Multi-up manuscript viewer with annotation support. Zoom-pan-rotate, collaborative annotation. Image viewing, comparative manuscript analysis
- [BDRC Thumbnail Generator](https://github.com/buda-base/buda-thumbnail-generator): Automated thumbnail generation for manuscript images. Batch processing, multiple size variants. Image preprocessing, access copy generation

#### Phase 5-6: Layout Analysis & Script Classification
- [BDRC SCAM Tool](https://github.com/buda-base/scam): Advanced manuscript processing for layout analysis. Automatic region detection, manuscript structure analysis. Page segmentation, layout analysis.

#### Phase 7: Optical Character Recognition
- [Tibetan OCR offline app](https://github.com/buda-base/tibetan-ocr-prototype): Breakthrough desktop OCR application for Tibetan scripts. Offline processing, multiple script support, Bdrcbdrc 91.99% accuracy. OCR for Uchan, Ume, and manuscript scripts.
- [sanskrit-ocr]( https://github.com/ihdia/sanskrit-ocr): Classical Sanskrit document OCR system. Multiple models (IndicOCR, CNN-RNN, Attention-LSTM), GPU optimization. Sanskrit text recognition, Devanagari script processing.
- [pe-ocr-sanskrit]( https://github.com/ayushbits/pe-ocr-sanskrit): Post-OCR text correction for Sanskrit texts. Error detection and correction, validation tools. OCR quality improvement, text validation.

#### Phase 8-9: Text Processing & Annotation
- [Pecha.org](https://github.com/OpenPecha/Pecha.org): Web interface for Buddhist texts (Sefaria fork). Highly active, Collaborative annotation, source sheet creation, API integration, Text annotation, collaborative editing, publication.
- [toolkit-v2](https://github.com/OpenPecha/toolkit-v2): Core Python library for Buddhist text processing, Active development (MIT license), Text processing pipelines, format conversion, Text markup, format standardization, validation.
- [Lopenling-App](https://github.com/OpenPecha/Lopenling-App): Critical edition creation platform for Tibetan texts, Active development, Multi-witness comparison, critical apparatus, Scholarly annotation, critical text creation.

#### Phase 10: Linguistic Processing
- [Botok](https://github.com/OpenPecha/Botok): Tibetan word tokenizer in Python, Highly active (69 stars, 17 forks), Word segmentation, POS tagging, lemmatization, custom dialects, Tibetan text tokenization, morphological analysis.
- [pybo](https://github.com/OpenPecha/pybo): Comprehensive NLP library for Tibetan, Active (funded by Khyentse Foundation) Text preprocessing, segmentation, BOTOK integration, Tibetan linguistic analysis, NLP pipeline.
- [actib](https://github.com/lothelanor/actib): NLP pipeline for Old and Classical Tibetan. BOTOK integration, Memory-Based Tagger, syllable classification. Classical Tibetan analysis, POS tagging, parsing.
- [bophono](https://github.com/Esukhia/bophono): ibetan phonetics engine in Python. Maintained by Esukhia network. Phonetic analysis, pronunciation generation. Phonological processing, linguistic annotation.
- [PaliNLP](https://github.com/daalft/PaliNLP): Morphological analyzer and generator for Pāli. Research-grade tool. Handles irregular declensions, morphological generation. Pāli linguistic analysis, grammatical processing.

#### Phase 11-12: Database Integration & Publication
- [digitalpalireader](https://github.com/digitalpalireader/digitalpalireader): Comprehensive Pāli study application. Tipitaka integration, multiple dictionaries, cross-platform. Text publication, scholarly access, educational tools
- [buddhist-dictionary](https://github.com/alexamies/buddhist-dictionary): NTI Buddhist Text Reader with Chinese-English dictionary. Taishō Tripiṭaka integration, web-based reading. Text publication, dictionary integration, user interface
- [lds-queries]( https://github.com/buda-base/lds-queries): BUDA Linked Data Server query system. Semantic queries, SPARQL endpoints, data integration. Database integration, semantic search, data access.

#### Cross-Phase Utilities
- [pyewts (OpenPecha)]( https://github.com/OpenPecha/pyewts): Tibetan Unicode ↔ Wylie transliteration converters(Python). idirectional conversion, ACIP support. Text conversion, format standardization, encoding.
- [ewts-converter (BDRC)](https://github.com/buda-base/ewts-converter): Tibetan Unicode ↔ Wylie transliteration converters(Java). idirectional conversion, ACIP support. Text conversion, format standardization, encoding.
- [OCR4all](https://www.ocr4all.org/): Comprehensive OCR workflow for historical texts. Complete workflow, ground truth production, model training. End-to-end OCR workflow, quality assurance.
