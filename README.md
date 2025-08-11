

# Medical Report Information Extractor


### Background
Structured information extraction from unstructured histopathology reports is essential for making clinical research data more accessible. Manual extraction by experts, while accurate, is time-consuming and costly, making it difficult to scale. Large Language Models (LLMs) offer an efficient alternative through zero-shot prompting, requiring only natural language instructions without the need for labeled data or additional training.  

This project evaluates the accuracy of LLMs in extracting structured information from **discharge summaries**, comparing their performance with manual extraction by a trained human annotator.

---

### Methods
We developed **Medical Discharge Summary Information Extractor**, leveraging LLMs for automated data extraction.  
Key steps:
- Created a **gold standard extraction dataset** to evaluate both human annotators and LLMs.
- Tested  LLMs, including:
  - **GPT-4o** – a leading proprietary model
- Dataset: **## reports** from the *## institute*.
- Extracted **## pathology features** as defined in the study’s data dictionary.

---

### Results
- **GPT-4o**: 


---

### Conclusion
We present an **open-source** tool for structured information extraction from unstructured medical text.  
Features:
- Customizable by non-programmers using natural language prompts
- Modular design for reuse across multiple extraction tasks
- Generates standardized, structured data to enhance accessibility and interoperability in clinical research

---


## License
This project is released under the **MIT License**. See `LICENSE` for details.

## Citation
If you use this work in your research, please cite it as:  
> *[Your Citation Format Here]*

---

## Contact
For questions or contributions, please open an issue or reach out via the repository’s discussion board.
