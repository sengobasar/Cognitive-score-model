# 🧠 Cognitive Score Model (Behavioral Intelligence Estimate)

## ✨ Hypothesis

Traditional "g" models tend to reduce intelligence to narrow, testable traits like logic, pattern recognition, and abstract reasoning.

However, this view is **cognitively narrow and psychologically incomplete**. Intelligence is not merely abstract performance — it's also the ability to:

- Attend wisely (low addictive screen exposure, high content quality)
- Reflect deeply (self-directed awareness, meaningful environment)
- Act maturely (lifestyle choices, behavioral health)

This model proposes a **behaviorally embodied** understanding of cognitive health — not as IQ, but as an index of mental maturity, attentional quality, and lived intelligence.

---

## 📊 Dataset Variables

| Variable              | Description                                         |
|-----------------------|-----------------------------------------------------|
| `screen_time`         | Hours per day on screen                             |
| `screen_quality`      | Thoughtfulness of consumed content (0–10)           |
| `tobacco_usage`       | Binary indicator (0 = no, 1 = yes)                  |
| `environment_score`   | Quality of home/study environment (0–10)            |
| `nutrition_score`     | Quality of nutritional habits (0–10)                |
| `attitude_score`      | Self-reflection and motivation (0–10)               |
| `academic_score`      | Educational engagement (0–10)                       |
| `media_content_score` | Preference for thoughtful vs passive content (0–10) |
| `cognitive_score`     | Final composite cognitive-health estimate (0–100)   |

This is a **synthetic dataset** — values are generated based on a weighted logic model with assumptions grounded in behavioral research.

---

## 📁 Files Included

- `generalised_cognitive_dataset.csv` — synthetic dataset with 100 entries
- `cognitive_model.ipynb` — exploratory notebook with visualizations, correlation matrix, scatter plots, and logic explanation
- `LICENSE` — MIT License (open for reuse with attribution)
- `README.md` — this document

---

## 🔮 Future Work

To enhance the realism and psychological depth of the model, future versions may consider:

### 🧠 Better Independent Variables
- **Mindfulness**: Use *Mindful Attention Awareness Scale (MAAS)* to measure reflective awareness
- **Emotional resilience**: Trait measures of optimism, self-efficacy, or coping skills
- **Sense of purpose / directionality**: Self-reported purposefulness or attachment security
- **Cognitive load / multitasking behavior**: Measured using *NASA-TLX* or multitasking frequency
- **Information-seeking vs avoidance**: Health-related info behavior scales
- **Socioeconomic Status (SES)**: Composite of education, income, occupation
- **Sleep quality**: Hours of rest and regularity (linked to attention + memory)
- **Creative engagement**: Frequency of writing, music, puzzle-solving

### 🔍 Improved Modeling
- Allow **learned weights** via regression or machine learning
- Explore **nonlinear interactions** (e.g., screen time × content quality)
- Add **noise and outliers** to better mimic real-world datasets

### 🌐 Generalization & Validation
- Expand across age groups or regional cultures
- Validate via survey data or expert interviews
- Eventually explore real-life behavioral datasets (anonymized)

---

## 💡 Final Note

This project is not a claim about clinical IQ — it is a **framework for thinking about intelligence as something embodied, contextual, and behavioral.**

Its goal is not accuracy — but **insight.**

> “True intelligence is not simply solving puzzles — it's sensing meaning, attending to the right thing, and acting with awareness.”

---
