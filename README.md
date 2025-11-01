# llmuxresearch

The goal: explore whether large language models can simulate user feedback as realistically as human respondents.

👥 Simulated Personas
Using prompt-based generation, I created ~25 synthetic personas across varied age groups, occupations, demographics, and motivations — each representing a different customer archetype for a q-commerce scenario.

🖼️ Experience Evaluation
I captured the full IM HP webpage and used a Vision API to have each persona describe — in 2–3 sentences — their first impression, purchase intent, and reasoning.

📊 Quantifying Insights
Each response was converted into a Likert-style rating by mapping feedback to anchor statements using cosine similarity. This approach produced more diverse and realistic results than simply asking an LLM to “rate” a homepage — which often leads to uniformly positive outputs.

💡 What I Found
The results mirrored human-like patterns (KS ≈ 0.88 as noted in the research), with richer “why” explanations behind each intent. It opens possibilities for creating AI-powered Digital Twins or automated customer advisory panels, replacing traditional, slow UX surveys with faster, deeper, and more scalable feedback loops.

⚠️ Caveats
Careful anchor design is critical, and it performs best for familiar product domains where the model has prior exposure.

📂 The full persona feedback and scoring workflow — mostly automated with minimal manual touchpoints — is documented in my shared sheet.
