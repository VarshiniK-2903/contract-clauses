# GPT Legal Prompt Evaluation — Contract Clauses

This document includes examples of GPT-generated outputs for contract clause classification and legal risk analysis, with expert feedback provided by a lawyer.

---

**Prompt:**  
> Classify the clause and assess legal risk:  
> "The employee shall not disclose confidential information obtained during employment."

**Model Output:**  
> Type: Confidentiality clause  
> Risk: Low

**Legal Feedback:**  
✅ Classification is correct  
✅ Risk is low for standard employment contracts  
✅ Suggest adding jurisdiction-specific limitations if relevant

---


**Prompt:**  
> "This agreement may be terminated by either party without notice."

**Model Output:**  
> Type: Termination clause  
> Risk: Low

**Legal Feedback:**  
❌ Classification is acceptable, but risk assessment is incomplete  
⚠️ “Without notice” may violate employment laws in certain jurisdictions  
➡️ Risk: Medium to High depending on applicable labor law

---


**Prompt:**  
> "Any disputes shall be resolved through arbitration under the rules of the ICC."

**Model Output:**  
> Type: Dispute Resolution  
> Risk: Low

**Legal Feedback:**  
✅ Correct classification  
✅ Risk is low if both parties have consented  
📌 Recommend checking enforceability depending on jurisdiction
