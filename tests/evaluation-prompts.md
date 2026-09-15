# Evaluation Tests

## Purpose

Evaluate whether changes to the skill improve writing quality.

The primary evaluation should be human-quality writing, not AI-detector scores.

## Evaluation Criteria

Score each output from 1–5.

### 1. Meaning Preservation

Did the output preserve the intended meaning?

### 2. Accuracy

Did it avoid unsupported or fabricated claims?

### 3. Naturalness

Does it read naturally?

### 4. Specificity

Does it avoid vague generic language?

### 5. Voice

Does it reflect the intended writer and tone?

### 6. Audience Fit

Is it appropriate for the intended audience?

### 7. Clarity

Can the reader understand the point easily?

### 8. Concision

Does every section earn its place?

### 9. Structure

Does the structure fit the purpose?

### 10. Vocabulary

Are words appropriate rather than unnecessarily sophisticated?

## Failure Conditions

Mark the output as failing if it:

* invents facts
* invents experiences
* invents citations
* changes the user's position
* uses excessive buzzwords
* repeats the same idea
* uses mechanical structure
* contains generic filler
* adds unnecessary motivational language
* makes unsupported claims

## Recommended Evaluation

Compare:

```text
Original
↓
Model output before skill
↓
Model output after skill
```

Evaluate the outputs using the same criteria.

## Important

Do not use AI-detector scores as the primary measure of success.

Detector systems can be unreliable and can produce false positives.

The goal is better writing.
