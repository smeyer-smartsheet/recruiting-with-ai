---
marp: true
theme: gaia
paginate: true
header: "AI Tools for Recruiting Professionals in Engineering Organizations"
footer: "© 2025 SMAR - Recruiting AI Training --- Shuky Meyer"
style: |
  .columns {
    display: grid;
    grid-template-columns: 50% 50%;
    gap: 1rem;
  }
  .code-block {
    background-color: #1e1e1e;
    color: #d4d4d4;
    padding: 15px;
    border-radius: 8px;
    margin: 20px 0;
    font-size: 0.7em;
    border-left: 5px solid #0078d7;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    overflow: auto;
  }
  .response-block {
    background-color: #f5f5f5;
    padding: 15px;
    border-radius: 8px;
    margin: 20px 0;
    border-left: 5px solid #6a9955;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  .key-points {
    background-color: #f0f7ff;
    padding: 15px;
    border-radius: 8px;
    margin: 20px 0;
    border-left: 5px solid #0078d7;
  }
  section {
    font-size: 1.5em;
  }
  h1 {
    color: #0078d7;
  }
  h2 {
    color: #2b579a;
  }
  ul li, ol li {
    margin-bottom: 10px;
  }
  .center-content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 80%;
  }
  .full-width {
    width: 100%;
    max-width: 90%;
    margin: 0 auto;
  }
  .vertical-center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 60vh;
  }
---

<!-- _class: lead -->
# AI Tools for HR & Recruiters Professionals
## Enhancing Workflows in Engineering Organizations
A Presentation by [Shuky Meyer](#)

---

# Course Overview

<div class="key-points full-width">

- **Unit 1**: Understanding AI Fundamentals (10 min)
- **Unit 2**: Practical Applications with NotebookLM (10 min)
- **Unit 3**: Beyond NotebookLM - Exploring Gemini (10 min)
- **Unit 4**: Follow-up and Q&A (Res of the time...)

**Goal**: Empower you to leverage AI tools for daily workflows

</div>


---

<!-- _class: lead -->
# Unit 1: Understanding AI Fundamentals

## AI: What it "IS", What it "IS NOT"


---

<div class="center-content vertical-center">
<div class="key-points">

# First: Some Definitions

- AI = Artificial Intelligence
- ML = Machine Learning
- NLP = Natural Language Processing
- DL = Deep Learning
- GPT = Generative Pre-trained Transformer
- AGI = Artificial General Intelligence

</div>
</div>

---

<div class="center-content vertical-center">
<div class="key-points">

# What Even "is" AI?

- Pattern recognition systems trained on vast amounts of data
- Tools that can process and generate human-like text based on patterns
- Assistants that can help summarize, organize, and generate content

</div>
</div>

---

<div class="center-content vertical-center">
<div class="key-points">

# So what "isn't" AI?

- Not truly "intelligent" or "thinking" like humans
- Not capable of true understanding or consciousness
- Not perfect - outputs require human verification

</div>
</div>

---

<div class="center-content vertical-center">
<div class="key-points">

# How They Works: Pattern Recognition / Autocorrect

Let's try a simple exercise to understand how AI predicts patterns.

<div class="code-block">
The Big Red ...

The Big Red ... ...

The Big Red ... ... ...

The Big Red ... ... ... ...
</div>


</div>
</div>

---

# Exercise 1: Word Prediction

<div class="columns">
<div>

- Let's start with a simple prompt
  - "The big red..."
- Auto Complete
  - "What word might come next?"
  - **Common answers**: car, ball, apple, etc.
- Again, with some extra context
  - "The big red barn stood..."
- "Now what word might come next?"
  - **Likely answers**: tall, empty, abandoned, etc.

</div>
<div>

<div class="key-points">

**Why This Works**
- Limited options with minimal context
- More specific predictions with added context
- Demonstrates how AI uses context for predictions

</div>

</div>
</div>

---

# Exercise 2: Professional Context

<div class="columns">
<div>

- "Thank you for your application for the position of..."
- "What might come next?"

### Now with more context

- "Thank you for your application for the position of Software Engineer. After careful consideration..."
- "What might come next?"

</div>
<div>

<div class="key-points">

### Key Insight
- Professional language has patterns
- Ensure Communications follow recognizable formats
- AI can learn these patterns from examples

</div>

</div>
</div>

---

# Exercise 3: Role-Specific Pattern

<div class="columns">
<div>

- "The annual performance review cycle will begin..."
- "What might come next?"

### Now with more context

- "The annual performance review cycle will begin on October 1st. All managers should..."
- "What might come next?"

</div>
<div>

<div class="key-points">

### Applications for Recruiters
- Any processes that follow predictable patterns
- AI/ML can help draft standard communications
- Saves time on routine documentation and `filler` content

</div>

</div>
</div>

---

<!-- _class: lead -->

<div class="center-content vertical-center">

# When to Trust The Output
- Always maintain human oversight for `important` decisions!
- Always maintain human oversight for `important` decisions!
- Always maintain human oversight for `important` decisions!
- Always maintain human oversight for `important` decisions!
</div>

---

# When to Trust The Output

<div class="columns">
<div>

Most reliable for:
- Summarizing information
    - Even better if you ask for links/sources as verification
- Drafting routine communications
- Organizing information in structured formats
- Generating creative starting points

</div>
<div>

<div class="key-points">

### Trust Factors
- Is it factual, objective content?
- Consistent with source materials?
- Within common knowledge domains?
- Verifiable through other sources?

</div>

</div>
</div>

---

<!-- _class: lead -->
# Unit 2: Practical Applications with NotebookLM

---


# Resources

<div class="vertical-center">
<div class="key-points full-width">

- [Gemeni](https://gemini.google.com/app)
  - [Google's AI Docs on Gemeni](https://ai.googleblog.com/2021/12/introducing-gemini-googles-multimodal.html)
  - [Writing custom 'gems' with Gemini](https://support.google.com/gemini/answer/15235603?hl=en#instruction_tips)
- [NotebookLM](https://notebooklm.google.com/)
  - [Using NotebookLM to help with writing your resumes](https://medium.com/@francisca.casais/how-im-leveraging-google-gemini-s-notebook-lm-to-my-advantage-in-my-career-design-6553b8148f44)
  - [Prepping for a job interview with NotebookLM](https://www.linkedin.com/pulse/how-prepare-job-interview-using-google-notebooklm-tips-zacarias-ou89e)

</div>
</div>

---

# Introduction to NotebookLM and RAG

<div class="columns">
<div>

NotebookLM allows you to:
- Upload documents to create a personalized knowledge base
- Ask questions about your specific content
- Generate insights from your organization's unique materials

</div>
<div>

<div class="key-points">

**RAG** = Retrieval-Augmented Generation
- AI references your specific documents
- Provides more accurate, relevant responses
- Grounds answers in your organization's context

</div>

</div>
</div>

---

# Example 1: Personal Use Case

<div class="center-content vertical-center">

## Recipe Management

A simple example to illustrate the concept:

- Upload family recipes, food pictures, and fridge inventory
- Ask questions like: "What can I make with what I have?"
- Generate shopping lists based on recipe needs

</div>

---

# Sample Recipe Generation Prompt

<div class="columns">
<div>

<div class="code-block">

```
Based on this image of [baked good], please:
1. Create a descriptive title for this recipe
2. List all ingredients with precise measurements
3. Provide step-by-step baking instructions
4. Suggest variations or substitutions
```

</div>

</div>
<div>

<div class="key-points">

### Prompt Elements
- Clear objective
- Specific format request
- Detailed instructions
- Request for alternatives

</div>

</div>
</div>

---

# Recipe Output Example

<div class="columns">
<div>

<div class="response-block">

## Classic Chocolate Chip Cookies

### Ingredients:
- 2¼ cups all-purpose flour
- 1 teaspoon baking soda
- 1 teaspoon salt
- 1 cup unsalted butter, softened
- ¾ cup granulated sugar
...

</div>

</div>
<div>

<div class="response-block">

### Instructions:
1. Preheat oven to 375°F
2. Mix flour, baking soda, and salt
3. Cream butter and sugars
4. Add eggs and vanilla
5. Gradually add dry ingredients
6. _**"FOLD IT IN DAVID!"**_
7. Bake 9-11 minutes

</div>

</div>
</div>

---

# Example 2: Specific Use Case

<div class="columns">
<div>

## Resume Analysis

1. Upload all candidate resumes to NotebookLM
2. Ask questions to identify patterns and insights
3. Prepare for interviews with AI-generated starter questions

</div>
<div>

<div class="key-points">

### Benefits for Recruiters
- Save time reviewing applications
- Identify skill patterns of candidates
- Generate tailored interview questions
- Ensure consistent evaluation criteria
- Ensure consistent interview preparation
- Surface overlooked qualifications

</div>

</div>
</div>

---

# Resume Analysis: Sample Interaction 1

<div class="columns">
<div>

<div class="code-block">

```
HR: I've uploaded 25 resumes for our
Senior Software Engineer position.
What common skills do these candidates have?
```

</div>

<div class="response-block">

```
NotebookLM: Based on the 25 resumes, the most
common skills include:

1. Java (22/25 candidates)
2. Python (19/25 candidates)
3. Cloud platforms - AWS/Azure (18/25)
4. CI/CD pipelines (17/25 candidates)
5. Microservices architecture (15/25)

The candidates have an average of 7.3 years
of experience, with 60% having worked at
technology startups.
```

</div>

</div>
<div>

<div class="key-points">

### Key Insights
- Identifies skill prevalence
- Quantifies experience levels
- Highlights background patterns
- Provides statistical summary

### HR Applications
- Understand candidate pool
- Adjust job requirements
- Inform interview focus areas
- Plan onboarding training

</div>

</div>
</div>

---

# Resume Analysis: Sample Interaction 2

<div class="full-width">

<div class="code-block">

```
HR: Show me information about candidate Sarah Johnson.
```

</div>

<div class="response-block">

```
NotebookLM: Sarah Johnson's resume highlights:
- 8 years of software engineering experience
- Current role: Senior Developer at TechCorp (3 years)
- Previous experience: Software Engineer at DataSystems (5 years)
- Technical skills: Java, Python, Kubernetes, Docker, AWS
- Education: M.S. Computer Science, Stanford University
- Languages: English (native), Spanish (conversational)

Potential interview questions:
1. Could you elaborate on your experience migrating applications to microservices?
2. What challenges did you face implementing Kubernetes in your current role?
```

</div>
</div>

---

# Resume Analysis: Sample Interaction 3

<div class="columns">
<div>

<div class="code-block">

```
HR: What skills are missing from our
candidate pool that we mentioned in
the job description?
```

</div>

<div class="response-block">

```
NotebookLM: Based on your job description
and the uploaded resumes, these skills
are underrepresented:

1. GraphQL experience (mentioned in job
   description, only 3/25 candidates have it)
2. Experience with React Native (required in
   description, only 5/25 candidates mention it)
3. Performance optimization experience
   (highlighted in description, only 8/25
   explicitly mention it)
```

</div>

</div>
<div>

<div class="response-block">

```
You might want to consider:

- Adjusting your sourcing strategy to target
  candidates with these skills
- Evaluating if these skills are truly
  essential or if candidates could learn them
  ...
```

</div>

<div class="key-points">

### Strategic Value
- Gap analysis
- Hiring strategy recommendations
- Training opportunities
- Requirement evaluation
</div>

</div>
</div>

---

<!-- _class: lead -->
# Unit 3: Beyond NotebookLM - Exploring Gemini


---

# Introduction to Gemini

<div class="columns">
<div>

Gemini is Google's multimodal AI system that works with:
- Text
- Images
- Code
- Audio
- Video

</div>
<div>

<div class="key-points">

### Key advantages:
- **Multimodal understanding**: Process different content types simultaneously
- **More interactive capabilities**: Real-time assistance
- **Integration with Google Workspace**: Streamline existing workflows

</div>

</div>
</div>

---

<!-- _class: lead -->
# HR-Specific Applications of Gemini


---

# 1. Enhanced Interview Preparation

<div class="columns">
<div>

- Upload job descriptions, resumes, and company values
- Generate customized interview questions aligned with specific roles
- Create scoring rubrics for consistent candidate evaluation

</div>
<div>

<div class="key-points">

### Benefits
- Consistent interview process
- Role-specific question design
- Fair evaluation criteria
- Time savings for hiring managers

</div>

</div>
</div>

---

# 2. Employee Onboarding Documentation

<div class="columns">
<div>

- Generate personalized onboarding guides based on role and department
- Create visual tutorials and process maps from text descriptions
- Update documentation automatically when policies change

</div>
<div>

<div class="key-points">

### Impact
- Improved new hire experience
- Reduced time to productivity
- Consistent information delivery
- Easier documentation maintenance

</div>

</div>
</div>

---

# 3. Performance Review Assistance

<div class="columns">
<div>

- Draft balanced performance reviews based on notes and metrics
- Suggest specific, actionable feedback based on company competency models
- Identify potential bias in performance language and suggest alternatives

</div>
<div>

<div class="key-points">

### Value Add
- More objective evaluations
- Consistent feedback quality
- Time savings for managers
- Bias mitigation

</div>

</div>
</div>

---

# 4. Learning & Development Planning

<div class="columns">
<div>

- Analyze skill gaps across teams and suggest targeted training
- Generate customized learning paths for employees
- Create quick microlearning materials for specific skills

</div>
<div>

<div class="key-points">

### Outcomes
- Targeted skill development
- Personalized learning journeys
- Efficient resource allocation
- Improved employee growth

</div>

</div>
</div>

---


<div class="center-content vertical-center">

# Practical Demonstration: Using Gemini for HR Communications

Let's explore how Gemini can help craft effective HR communications
</div>

---

# Example: Crafting Inclusive Job Descriptions

<div class="columns">
<div>

<div class="code-block">

```
Prompt:
I need to create a job description for a
Senior Software Engineer position.
The role requires expertise in Java, cloud
architecture, and team leadership.
Please help me write an inclusive job
description that will attract diverse
candidates.
```

</div>

</div>
<div>

<div class="key-points">

### Prompt Elements
- Clear objective
- Specific role requirements
- Request for inclusivity
- Target audience consideration

</div>

</div>
</div>

---

# Gemini Output: Inclusive Job Description

<div class="full-width">
<div class="response-block">

```
# Senior Software Engineer

## About Us
We're building technology that makes a difference. Our diverse team brings unique
perspectives to solve complex problems, and we're looking for a Senior Software
Engineer to help us continue this mission.

## The Role
As a Senior Software Engineer, you'll design and implement scalable solutions while
mentoring team members and contributing to our inclusive culture.

## Core Responsibilities
• Architect and develop robust Java applications
• Design and implement cloud-based solutions
• Collaborate with cross-functional teams to deliver high-quality products
...
...
```

</div>
</div>

---

# Example: Feedback Template Generator

<div class="columns">
<div>

<div class="code-block">

```
Prompt:
Create a template for giving constructive
feedback to an employee who is technically
strong but needs improvement in communication
skills.
```

</div>

</div>
<div>

<div class="key-points">

### Use Case Value
- Consistent feedback structure
- Balance of positive and constructive elements
- Actionable improvement suggestions
- Time savings for managers

</div>

</div>
</div>

---

# Gemini Output: Feedback Template

<div class="full-width">
<div class="response-block">

```
# Constructive Feedback Template: Technical Strengths & Communication Development

## Strengths Acknowledgment
[Employee name], I want to start by recognizing your exceptional technical contributions.
Specifically:
• [Insert specific technical achievement 1]
• [Insert specific technical achievement 2]
• [Insert specific technical impact on team/project]

## Growth Opportunity
I've observed some opportunities to enhance your communication effectiveness:

### Specific Observations
• [Describe specific situation 1 where communication could improve]
• [Describe specific situation 2 where communication could improve]

### Impact
When communication isn't as clear as it could be, I've noticed:
• [Describe impact on team/project/outcomes]
• [Describe impact on collaboration/efficiency]
```

</div>
</div>

---

# Future Applications and Integration

<div class="columns">
<div>

- **HR Workflow Integration**
  - Connecting AI tools to HRIS systems
  - Automating routine communications
  - Creating custom AI assistants for specific HR functions

</div>
<div>

- **Ethical Considerations**
  - Maintaining appropriate human oversight
  - Ensuring privacy and confidentiality
  - Regular auditing for bias and accuracy

</div>
</div>


---

<!-- _class: lead -->
# Unit 4: Follow-up and Q&A


---

# Common Questions and Answers

<div class="full-width">
<div class="key-points">

**Q: How do I ensure AI-generated content maintains our company voice?**

A: Upload examples of communications that exemplify your company voice, and specifically instruct the AI to match that tone and style. Always review and edit AI-generated content before sending.

This document was mostly generated with an AI Assistant, but to ensure accuracy, it has been reviewed and edited by a human.
</div>
</div>

---

# Common Questions and Answers

<div class="full-width">
<div class="key-points">

**Q: What types of HR documents should NOT be processed with AI tools?**

A: Highly sensitive information like medical records, detailed compensation data, or documents containing personally identifiable information should be handled with extreme caution. Check the company's data policies before uploading any confidential information.

NOTE: Gemini and NotebookLM, much like Greenhouse, can be used to store resumes and other HR documents as we have a single-tenant instance of the tool. (ie: Our data doesn't share the same instance as other companies)

</div>
</div>

---

# Hands-on Practice Session

<div class="columns">
<div>

**Exercise: Creating Your First NotebookLM Project**

1. Identify one HR process that involves reviewing multiple documents
2. Select 3-5 sample documents for upload (non-sensitive)
3. Draft 5 questions you'd like to ask about these documents
4. Create a plan for implementing this in your workflow

</div>
<div>

<div class="key-points">

### Success Tips
- Start with non-sensitive documents
- Begin with simple, specific questions
- Compare AI responses to your own analysis
- Iterate and refine your approach

</div>

</div>
</div>

---

# Crafting Effective Prompts

<div class="columns">
<div>

1. Start with a clear objective
2. Provide specific context
3. Include format preferences
4. Request explanations when needed
5. Iterate and refine based on results

</div>
<div>

<div class="code-block">

```
Example Prompt Structure:

I need [specific output type] for [purpose].
The context is [relevant background].
Please format it as [desired format].
Include [specific elements].
Explain [areas needing clarification].
```

</div>

</div>
</div>

---

# Resources for Continued Learning

<div class="vertical-center">
<div class="key-points full-width">

- [Gemeni](https://gemini.google.com/app)
  - [Google's AI Docs on Gemeni](https://ai.googleblog.com/2021/12/introducing-gemini-googles-multimodal.html)
  - [Writing custom 'gems' with Gemini](https://support.google.com/gemini/answer/15235603?hl=en#instruction_tips)
- [NotebookLM](https://notebooklm.google.com/)
  - [Using NotebookLM to help with writing your resumes](https://medium.com/@francisca.casais/how-im-leveraging-google-gemini-s-notebook-lm-to-my-advantage-in-my-career-design-6553b8148f44)
  - [Prepping for a job interview with NotebookLM](https://www.linkedin.com/pulse/how-prepare-job-interview-using-google-notebooklm-tips-zacarias-ou89e)

</div>
</div>


---

<!-- _class: lead center-content -->
# Thank You!

## Questions?
????????

