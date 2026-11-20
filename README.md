# OptiScreen
# OptiScreen AI
### AI-powered Optometric Anamnesis Assistant

**OptiScreen AI** is an artificial intelligence agent designed to support opticians and optometrists in the preliminary analysis of a patient's visual and general anamnesis.

The system analyzes the information provided by the user, identifies relevant symptoms and visual factors, and suggests appropriate optometric tests, explaining the reasons behind each recommendation.

The project combines artificial intelligence, optometric knowledge and workflow automation to demonstrate how AI agents can support professional activities in the optical field.

---

## Project Overview

OptiScreen AI simulates a preliminary optometric assessment process.

The user interacts with a chatbot and provides information about the patient's:

- Age and general background.
- Visual symptoms and discomfort.
- Visual habits and digital device usage.
- Previous eye examinations.
- Current or previous optical correction.
- Medical and ocular history.
- Family history.

The AI agent processes this information and generates a structured preliminary assessment for the professional.

## Main Features

- **Anamnesis analysis:** organizes and interprets the information provided by the user.
- **Symptom identification:** highlights relevant visual symptoms and associated factors.
- **Optometric test recommendations:** suggests tests based on the reported symptoms and visual functions that may require further assessment.
- **Clinical reasoning support:** explains the purpose and relevance of each suggested test.
- **Follow-up questions:** identifies missing information and requests clarification when necessary.
- **Safety alerts:** highlights warning signs that may require medical assessment.
- **Structured report:** generates a preliminary assessment to support the optometrist's work.

## Optometric Tests

The knowledge and reasoning framework includes the following tests:

- Visual acuity at distance and near.
- Objective and subjective refraction.
- Retinoscopy.
- Cover test at distance and near.
- Phoria assessment.
- Near point of convergence.
- Accommodative amplitude.
- Accommodative facility.
- Fusional vergence.
- Tear film and ocular surface assessment.

The agent selects tests according to the information provided. It does not automatically prescribe a fixed examination protocol.

## Workflow Architecture

The application is built using **n8n**, a workflow automation platform, and an AI language model.

The main workflow consists of:

1. **Chat Trigger:** receives the user's anamnesis through a chat interface.
2. **AI Agent:** analyzes the information and generates recommendations.
3. **OpenAI Chat Model:** provides the language model used by the agent.
4. **Conversation Memory:** maintains conversational context when configured.
5. **Output:** returns a structured preliminary assessment in Italian.

The architecture can be extended with an optometric knowledge base, external databases and additional automation tools.

## Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation and orchestration |
| AI Agent | Anamnesis analysis and test recommendations |
| OpenAI API | Language model |
| Chat Trigger | User interaction |
| Conversation Memory | Context management |

## Demonstration

**Public Chat Interface**

[Open OptiScreen AI] https://optiscreen.app.n8n.cloud/webhook/63812346-0c68-47d2-91b0-7eae13ab223e/chat

**Explanatory Video**

[Watch the project demonstration https://drive.google.com/file/d/11iqMfIuakeUGVyA-CP96aggES6mVQmO8/view?usp=share_link

**Explanatory Image**

![OptiScreen AI – Project A[rchitecture](https://drive.google.com/file/d/1ncgyLYQxVd43ZiwS6chrkJVkt3Q7P1VZ/view?usp=share_link)] 

## Testing and Validation

The prototype should be tested using simulated patient scenarios, including:

1. Near-work discomfort and asthenopia.
2. Distance vision blur.
3. Intermittent diplopia.
4. Burning eyes and dry-eye symptoms.
5. Incomplete anamnesis.
6. Potentially urgent visual symptoms.

Testing focuses on the relevance of the suggested tests, the accuracy of the information provided, the handling of missing data and the recognition of warning signs.

## Ethical Considerations and Limitations

OptiScreen AI is an educational prototype designed to demonstrate the potential use of artificial intelligence in optometric practice.

It does not provide medical diagnoses, prescribe treatments or replace professional judgment.

All recommendations are preliminary suggestions. The optometrist remains responsible for selecting, performing and interpreting the tests.

Potential limitations include incomplete anamnesis, inaccurate user-provided information, and possible errors in AI-generated responses.

Only simulated patient data should be used for demonstrations and testing. Real patient information must not be entered into the public prototype.

## Project Objective

The objective is to demonstrate how an AI agent can combine domain-specific knowledge, natural language processing and automated workflows to support the preliminary organization of an optometric assessment.

OptiScreen AI connects theoretical knowledge from the optical and optometric fields with practical applications of artificial intelligence.

---

**Project:** OptiScreen AI  
**Field:** Optics, Optometry and Artificial Intelligence  
**Platform:** n8n  
**Language:** Italian  
**Type:** Educational AI Agent Prototype
