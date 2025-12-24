# Summary: The TCREI Framework for Effective Prompting

This article outlines a structured approach to prompt engineering called **TCREI**. The author emphasizes that the first three steps (**TCR**) are the most critical for generating high-quality AI responses on the first try.

## The TCREI Framework

### 1. Task (The "What")

Define clearly what you want the AI to do.

- **Persona:** Assign a specific role to the AI to set the tone and expertise (e.g., "Act as an expert nutritionist").
- **Output Format:** Explicitly state how you want the result presented (e.g., a markdown table, a JSON file, a bulleted list).

### 2. Context (The "Situation")

Provide background information to help the AI understand the constraints and nuances.

- **Details:** Include the target audience, limitations, or specific goals.
- _Example:_ instead of just asking for a meal plan, specify: "This plan is for a college student with a low budget and only a microwave."

### 3. References (The "Examples")

Provide data or examples for the AI to emulate. This is crucial for guiding the style and structure.

- **Technique:** This is often referred to as "Few-shot prompting." Providing even one or two examples of the desired output significantly improves accuracy compared to providing none ("Zero-shot").

### 4. Evaluate

Review the generated output to see if it meets your requirements and standards.

### 5. Iterate

If the result isn't perfect, refine your prompt—usually by tweaking the **Task**, adding more **Context**, or clarifying the **References**—and ask again.

---

## Key Takeaways

- **Prioritize TCR:** The core of a good prompt lies in the **Task**, **Context**, and **References**.
- **Mnemonic:** To remember the essential steps easily, the author suggests the phrase **"Truffle Chocolate Rum"** (for **TCR**).

## 출처

- https://drayseozturk.org/2025/02/05/prompting/

## 한글요약

```text
핵심 요약: TCREI 프레임워크
이 글은 AI에게 원하는 답변을 정확히 얻기 위한 **5단계 공식(TCREI)**을 설명하고 있습니다. 저자는 이 중 앞의 3단계(TCR)가 가장 중요하다고 강조합니다.

Task (임무): AI에게 시킬 일을 명확히 정합니다.

팁: AI에게 특정 **페르소나(역할)**를 부여하고, 원하는 **결과물 형식(표, 리스트 등)**을 지정하세요.

예시: "너는 식물성 식단 전문 영양사야(역할). 아침, 점심, 저녁이 포함된 주간 식단표를 표 형식으로 만들어줘(형식)."

Context (배경 상황): AI가 상황을 이해할 수 있도록 구체적인 정보를 줍니다.

팁: 누가 사용할 것인지, 어떤 제약이 있는지 알려주세요.

예시: "이 식단은 예산이 적고 기본 조리기구만 있는 대학생을 위한 거야."

References (참고 자료): AI가 참고할 예시를 제공합니다.

팁: 예시를 하나도 안 주거나(제로 샷), 하나만 주거나(원 샷), 여러 개 주는(퓨 샷) 방법이 있습니다. 예시가 많을수록 AI가 스타일을 더 잘 따라 합니다.

예시: "아래 두 가지 식단 예시를 참고해서 작성해 줘..."

Evaluate (평가): AI의 답변이 마음에 드는지 확인합니다.

Iterate (반복/수정): 마음에 들지 않으면 질문을 조금씩 고쳐서 다시 물어봅니다.

한 줄 요약: 좋은 질문을 하려면 "어떤 역할로(Task), 어떤 상황에서(Context), 무엇을 참고해서(References)" 답해야 하는지 알려주면 됩니다. 저자는 이를 기억하기 쉽게 **"트러플 초콜릿 럼(TCR)"**이라고 부르자고 제안합니다.

```
