# Ex.No.3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques  

**Date:**  29-08-2025 

**Register Number:**  212223060206

---

## Aim  
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns ranging from task-oriented to persona-driven prompts.

---

## Algorithm / Procedure  

1. **Direct Instruction Prompts**  
   - **Objective:** Provide concise responses to customer inquiries.  
   - **Prompt Example:**  
     > "When a customer asks for the status of their order, reply with:  
     > 'Your order is currently being processed and will be delivered by [date].'"

2. **Contextual Prompting**  
   - **Objective:** Incorporate specific context from previous interactions.  
   - **Prompt Example:**  
     > "If the customer previously mentioned that they haven’t received their order, say,  
     > 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

3. **Persona-Based Prompting**  
   - **Objective:** Make the chatbot adopt a specific persona for more engaging interactions.  
   - **Prompt Example:**  
     > "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as  
     > 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

4. **Few-Shot Prompting**  
   - **Objective:** Teach the chatbot using examples to generalize for similar queries.  
   - **Prompt Example:**  
     ```
     'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'  
     'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'  
     Now, respond to: 'My app keeps crashing.'  
     ```

5. **Chain of Thought Prompting**  
   - **Objective:** Solve complex issues with step-by-step reasoning.  
   - **Prompt Example:**  
     > "When a customer reports their laptop overheating, guide them through:  
     > - Ask if using laptop on soft surface.  
     > - Suggest moving it to flat, hard surface.  
     > - Ask if vents are cleaned.  
     > - Recommend restart if issue persists.  
     > Now, solve: 'My laptop fan is making a loud noise.'"

6. **Instruction with Constraints**  
   - **Objective:** Provide responses within constraints (length/tone).  
   - **Prompt Example:**  
     > "Respond to order inquiries in no more than 50 words and avoid technical jargon.  
     > Example: 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

7. **Reflective Prompting**  
   - **Objective:** Reduce misunderstandings by reflecting the user’s query.  
   - **Prompt Example:**  
     > "If a customer asks 'How can I reset my password?' respond with  
     > 'You're asking how to reset your password, correct? Here’s how you can do it.'"

---

## Tabular Summary  

| Prompt Type              | Objective                   | Prompt Example                                                                 |
|--------------------------|-----------------------------|-------------------------------------------------------------------------------|
| Direct Instruction       | Concise answers             | "Your order is currently being processed and will be delivered by [date]."    |
| Contextual               | Use prior context           | "I see that you mentioned your order hasn't arrived yet..."                   |
| Persona-Based            | Friendly voice              | "Hey there! I’m here to help..."                                              |
| Few-Shot                 | Learn from examples         | `'My phone isn't charging.' → recommended reply`                              |
| Chain of Thought         | Step-by-step troubleshooting| "Guide: check surface → vents → restart"                                      |
| Instruction with Constraints | Respect length/tone    | "Respond in ≤50 words; avoid jargon"                                          |
| Reflective               | Confirm user intent         | "You're asking how to reset your password, correct?"                          |

---

## Result  
The various types of prompting techniques such as Direct Instruction, Contextual, Persona-Based, Few-Shot, Chain of Thought, Instruction with Constraints, and Reflective Prompting were successfully applied in chatbot development.  

**Thus, the prompts were executed successfully.**
