# MGSM Reasoning Stability

## 1. Research Setup

- **Model:** Qwen 1.5B
- **Dataset:** MGSM
- **Languages:** English + Bengali
- **Problems:** 250 paired problems
- **Samples per problem per language:** 10
- **Planned reasoning traces:**  
  `250 × 2 × 10 = 5,000`

### Key Design

- The same underlying mathematical problem is compared across **English and Bengali**.
- Each problem is sampled **10 times per language**.
- **Bad, wrong, and repetitive reasoning traces are retained** rather than filtered out, allowing reasoning instability to be analyzed.

