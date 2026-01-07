## Model Decision Matrix
- Decision Criteria - Wrong, Missing, User, Creativity.

### Q1. How bad is it if the answer is WRONG?
- Very bad → choose safest model
- Mild → choose expressive model

### Q2. Is missing information worse than extra information?
- Missing is worse → completeness model
- Extra is worse → safety model

### Q3. Who will read the output?
- Lawyer / auditor → conservative
- Customer → clearer tone
- Internal analyst → balanced

### Q4. Is creativity allowed?
- No → low temperature, strict model
- Yes → higher temperature, expressive model

| Use Case                        | Chosen Model | Why                                             |
| ------------------------------- | ------------ | ----------------------------------------------- |
| Legal policy summarization      | Claude       | Minimizes hallucination and interpretation risk |
| Internal compliance review      | GPT          | Maximizes coverage for analyst validation       |
| Customer-facing refund summary  | Gemini       | Balanced tone with adequate constraint          |
| Incident response documentation | Claude       | Strict adherence to source text                 |
| Draft knowledge base article    | GPT          | Rich detail with human review                   |

### Model trade-offs
- GPT provides high completeness but tends to introduce interpretive phrasing that increases compliance risk.

- Claude minimizes hallucination risk but may omit secondary policy details due to aggressive compression.

- Gemini balances tone and structure but can simplify nuanced rules, reducing legal precision.