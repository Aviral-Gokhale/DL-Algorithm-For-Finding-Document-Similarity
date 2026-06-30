# Deep learning for finding document similarity
A robust, framework developed to assess document similarity, sort documents, and detect potential fraud by comparing test files against original templates. The system uniquely leverages a dual-stream pipeline—combining textual data extracted via Tesseract OCR and visual structural features extracted via a Convolutional Neural Network (CNN)—to compute an accurate, multi-layered similarity score.

🚀 Key Features
- Dual-Stream Evaluation: Integrates text-based similarity with visual feature matching for a comprehensive analysis.
- High Precision Metrics: Achieves 97% precision for text-based matching and 91% precision for automated document sorting.
- Normalized Scoring Mechanism: Combines distinct text and image similarity vectors into a unified, normalized final similarity score.
- Interactive MATLAB UI: Includes a fully functional user interface to easily upload documents, run validations, and view granular similarity reports.

🛠️ Architecture & Tech Stack
- Core Environment: MATLAB
- Text Extraction Engine: Tesseract OCR
- Visual Feature Extraction: Convolutional Neural Networks (CNNs)
- Analysis Domains: Document Analysis, Structural Feature Extraction, and Fraud Detection

📊 How It Works
- Document Input: The user uploads an original template and a test document via the MATLAB UI.
- Text Processing Stream: Tesseract OCR processes the documents to extract textual content, followed by a text similarity comparison.
- Visual Processing Stream: A CNN analyzes the layout, formatting, and visual components of the documents to generate feature maps.
- Hybrid Fusion: The system normalizes and merges the text and visual scores to output a final fraud-detection / similarity rating.

💻 Getting Started
Prerequisites
- MATLAB (R2021a or later recommended)
- Computer Vision Toolbox
- Deep Learning Toolbox
- Tesseract OCR engine wrapper configured for MATLAB
