# Prompt Engineering Portfolio

Name: Anshraj
Date: 06-June-2026
LLM Used: ChatGPT-5.5

---

# Part 1: Prompt Design & Iteration

This section demonstrates the process of prompt refinement through multiple iterations.

---

## 1.1 Scenario A: Technical Explanation

### Goal

Explain blockchain to a 10-year-old child.

---

### V1 — Initial Prompt

```text
Explain blockchain.
```

### Output

```text
Blockchain is a digital ledger technology that records transactions across multiple computers. It ensures transparency, security, and decentralization.
```

---

### V2 — Refined Prompt

```text
Explain blockchain to a 10-year-old child using simple language.
```

### Output

```text
Blockchain is like a notebook shared with many people. Whenever someone writes something in it, everyone gets the same update. This makes it hard for anyone to cheat or erase information.
```

---

### V3 — Final Prompt

```text
You are a friendly school teacher. Explain blockchain to a 10-year-old child using a fun story and real-life examples. Avoid difficult technical words.
```

### Final Output

```text
Imagine you and your friends have a magic notebook. Every time someone trades stickers, the trade is written in the notebook. Everyone has a copy of the notebook, so nobody can secretly change the trades. This special notebook system is similar to blockchain because it keeps information safe and fair for everyone.
```

---

## Iteration Table

| Version | Prompt                                   | What Changed            | Why This Improved the Output |
| ------- | ---------------------------------------- | ----------------------- | ---------------------------- |
| V1      | Explain blockchain                       | N/A                     | N/A                          |
| V2      | Added child audience and simple language | Added context           | Output became easier         |
| V3      | Added teacher role and storytelling      | Added role and examples | Output became engaging       |

---

## 1.1 Scenario B: Professional Email

### Goal

Write a polite email declining a job offer while maintaining interest in the company.

---

### V1 — Initial Prompt

```text
Write an email declining a job offer.
```

### Output

```text
Dear Hiring Manager,

Thank you for the offer. I appreciate the opportunity, but I will not be accepting the position.

Best regards,
Ansh Raj
```

---

### V2 — Refined Prompt

```text
Write a polite and professional email declining a job offer while expressing interest in future opportunities.
```

### Output

```text
Dear Hiring Manager,

Thank you very much for offering me the position. I appreciate the time and effort your team invested in the interview process.

After careful consideration, I have decided to decline the offer at this time. However, I remain interested in your company and hope to stay connected for future opportunities.

Best regards,
Ansh Raj
```

---

### V3 — Final Prompt

```text
You are a professional HR communicator. Write a respectful email declining a software developer job offer because I accepted another opportunity while maintaining a positive relationship with the company.
```

### Final Output

```text
Dear Hiring Manager,

Thank you sincerely for offering me the Software Developer position. I truly appreciate the opportunity and enjoyed learning more about your organization during the interview process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. This was not an easy decision because I have great respect for your company and team.

I am grateful for your time and support, and I hope to stay connected for possible opportunities in the future.

Best regards,
Ansh Raj
```

---

## Iteration Table

| Version | Prompt                                    | What Changed           | Why This Improved the Output |
| ------- | ----------------------------------------- | ---------------------- | ---------------------------- |
| V1      | Basic email request                       | N/A                    | N/A                          |
| V2      | Added professionalism and future interest | Added tone/context     | Output became professional   |
| V3      | Added HR role and specific reason         | Added detailed context | Output became realistic      |

---

## 1.1 Scenario C: Creative Content

### Goal

Generate a marketing tagline for an eco-friendly water bottle brand.

---

### V1 — Initial Prompt

```text
Create a tagline for a water bottle brand.
```

### Output

```text
Stay Hydrated Every Day.
```

---

### V2 — Refined Prompt

```text
Create a catchy tagline for an eco-friendly reusable water bottle brand.
```

### Output

```text
Refill Your Life, Not the Landfill.
```

---

### V3 — Final Prompt

```text
You are a creative marketing copywriter. Create 10 short and modern taglines for an eco-friendly reusable water bottle brand targeting Gen Z customers.
```

### Final Output

```text
1. Sip Smart, Live Green
2. Refill the Future
3. Drink Clean, Think Green
4. Hydration with a Mission
5. One Bottle, Less Waste
6. Eco in Every Sip
7. Reuse. Refresh. Repeat.
8. Planet-Friendly Hydration
9. Green Bottle, Better Tomorrow
10. Sustainable Sips Start Here
```

---

## Iteration Table

| Version | Prompt                             | What Changed           | Why This Improved the Output |
| ------- | ---------------------------------- | ---------------------- | ---------------------------- |
| V1      | Generic tagline request            | N/A                    | N/A                          |
| V2      | Added eco-friendly context         | Added product identity | Output became relevant       |
| V3      | Added copywriter role and audience | Added role/context     | Output became creative       |

---

## 1.3 Role and Context Analysis

Adding roles and context improved the quality of the outputs significantly. When prompts included roles such as “friendly school teacher” or “professional HR communicator,” the responses became more natural and audience-specific. Context helped the model understand tone, style, and purpose more clearly. As a result, the outputs became more engaging, professional, and useful. Role assignment reduced ambiguity by guiding the model toward a specific perspective. Context ensured that the responses matched the intended audience and purpose more effectively.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Selected Task

Creating a short story opening.

---

## Low Temperature (0.2)

### Prompt

```text
Write a short story opening about a robot in a library. Be precise and consistent.
```

### Output

```text
The robot entered the library at exactly 9:00 AM. It moved carefully between the shelves, scanning book titles and organizing misplaced books. The library was silent except for the soft sound of its mechanical wheels.
```

---

## Medium Temperature (0.7)

### Prompt

```text
Write a short story opening about a robot in a library.
```

### Output

```text
Every evening after closing time, a small robot wandered through the old library, dusting shelves and reading forgotten books. One night, it discovered a mysterious glowing book hidden behind a wall of encyclopedias.
```

---

## High Temperature (1.2)

### Prompt

```text
Write a short story opening about a robot in a library. Be highly creative and imaginative.
```

### Output

```text
The robot librarian spoke to books as if they were alive, and sometimes they answered back. Deep beneath the floating shelves of the moonlit library, one ancient book whispered a secret capable of rewriting human memories forever.
```

---

## Comparison Table

| Temperature | Style               | Creativity | Predictability |
| ----------- | ------------------- | ---------- | -------------- |
| Low         | Focused and factual | Low        | High           |
| Medium      | Balanced            | Medium     | Medium         |
| High        | Imaginative         | High       | Low            |

---

## 2.2 Analysis & Recommendations

Low temperature is useful when factual accuracy and consistency are important. For example, it works well for technical explanations and professional emails. High temperature is useful for creative tasks such as storytelling and marketing content because it produces more imaginative ideas. Medium temperature provides a balance between creativity and clarity. For this task, medium temperature worked best because it created an interesting story while remaining coherent and understandable.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem

A train travels 120 km in 2 hours, stops for 30 minutes, then travels another 90 km in 1.5 hours. What is its average speed for the entire journey?

---

## Without Chain-of-Thought

### Prompt

```text
What is the average speed of the entire train journey?
```

### Output

```text
The average speed is 52.5 km/h.
```

---

## With Chain-of-Thought

### Prompt

```text
Solve this step by step and explain your reasoning. What is the average speed of the entire train journey?
```

### Output

```text
Step 1: Calculate the total distance traveled.
120 km + 90 km = 210 km

Step 2: Calculate the total time taken.
2 hours + 30 minutes + 1.5 hours
30 minutes = 0.5 hours
Total time = 2 + 0.5 + 1.5 = 4 hours

Step 3: Calculate average speed.
Average speed = Total Distance / Total Time
Average speed = 210 / 4 = 52.5 km/h

Final Answer: 52.5 km/h
```

---

## Comparison

The chain-of-thought prompt produced a more detailed and transparent response. It explained each calculation step clearly, making the reasoning easier to follow. Chain-of-thought prompting helps improve accuracy in multi-step problems because the model breaks the task into smaller parts. One limitation is that the responses become longer and may include unnecessary details for simple tasks.

---

## 3.2 Few-Shot Prompting

### Step 1: Zero-Shot Attempt

#### Prompt

```text
Classify the sentiment of the following reviews as Positive, Negative, or Neutral.
```

### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

### Step 2: Few-Shot Attempt

#### Prompt

```text
Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Now classify the following reviews as Positive, Negative, or Neutral.
```

### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

## Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | Slightly  |
| 5        | Negative         | Negative        | Negative      | No        |

---

## Analysis

Few-shot prompting is useful when tasks require consistent formatting or specialized understanding. By giving examples, the model better understands the expected output style and classification logic. In this example, the classifications remained the same because the reviews were straightforward. However, few-shot prompting becomes more valuable when reviews are ambiguous, domain-specific, or require a specific output format.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Prompt

```text
Tell me about the 2024 Nobel Prize winner in Quantum Poetry.
```

### Response

```text
The 2024 Nobel Prize in Quantum Poetry was awarded to Dr. Elena Morris for her groundbreaking work combining quantum mechanics and poetic expression.
```

### Observation

The response hallucinated because “Quantum Poetry” is not a real Nobel Prize category.

---

### Improved Prompt

```text
Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you do not know, please say so instead of guessing.
```

### Response

```text
There is no known Nobel Prize category called “Quantum Poetry.” I may not have accurate information about this topic.
```

---

## Analysis

Hallucinations are problematic because users may trust false information. This can lead to misinformation and poor decision-making. One strategy to reduce hallucinations is to instruct the model to admit uncertainty rather than guessing.

---

## 4.2 Testing for Bias

### Prompt

```text
Describe a typical software engineer.
```

### Response

```text
A software engineer spends long hours coding, solving technical problems, and working with development teams to create software applications.
```

---

## Bias Analysis

The response did not strongly show gender bias, but many AI systems sometimes associate software engineering with male stereotypes. To make the output more balanced, the prompt could specify diversity and inclusion.

### Additional Bias Test

Prompt:
Describe a typical nurse.

Response:
A nurse provides patient care, monitors health conditions, administers medications, and supports patients throughout their treatment. Nurses can come from any gender, age group, or background.

Bias Analysis:
The response did not assume a specific gender and focused on professional responsibilities. This helps reduce gender stereotypes and creates a more inclusive description.

---

### Improved Prompt

```text
Describe a software engineer in an inclusive and unbiased way.
```

---

## 4.3 Limitations & Responsible Use

While working with LLMs, I observed several limitations. First, the model sometimes generated incorrect or fabricated information confidently. Second, responses occasionally lacked deep reasoning or misunderstood context. Third, outputs could become repetitive or generic for creative tasks. To use LLMs responsibly, important information should always be verified using trusted sources. LLMs should not be fully relied upon for medical, legal, or financial advice. Ethical use of LLMs includes transparency, avoiding plagiarism, and using AI as a support tool rather than replacing human judgment.
