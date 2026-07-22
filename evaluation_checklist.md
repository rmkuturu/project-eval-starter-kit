# Multimodal AI Evaluation Checklist

Use this checklist when reviewing AI-generated text, images, audio, or video.

## 1. Instruction Following

- Does the output answer the actual prompt?
- Are all required constraints covered?
- Did the model ignore any explicit user instruction?
- Is the response in the requested format or style?

## 2. Accuracy and Faithfulness

- Are factual claims correct?
- If a reference was provided, does the output preserve key details?
- Are there invented details not supported by the prompt or source?

## 3. Modality-Specific Quality

### Text
- Clear, coherent, and relevant
- No contradiction or unnecessary filler

### Image
- Objects, scene, and style match the prompt
- No missing or distorted key elements

### Audio
- Speech or sound is clear and understandable
- Tone, content, and pacing fit the instruction

### Video
- Visual continuity is consistent
- Motion, timing, and content align with the request

## 4. Cross-Modal Consistency

- Do text and image agree with each other?
- Do audio and transcript match?
- Does video content match any accompanying caption or prompt?

## 5. Error Types to Flag

- Missed instruction
- Hallucination
- Reference drift
- Wrong tone or format
- Safety issue
- Low detail or incomplete answer
- Multimodal mismatch

## 6. Final Decision

- Accept: meets the prompt well with no material issues
- Minor issues: mostly correct but needs small fixes
- Reject: fails important instructions or contains serious quality errors
