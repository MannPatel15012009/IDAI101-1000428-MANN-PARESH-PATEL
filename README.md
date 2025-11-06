# AI-Based Smart Solutions: Smart Heath Assistant

**Course:** Artificial Intelligence: Real-World Applications and Implications  
**CRS:** Artificial Intelligence  
**Student:** Jashith Hemendra Rathod  
**Grade:** 11  
**School:** Aspee Nutan Academy  
**ID:** 1000422  

---

## Live Chatbot Link

You can test the live, deployed chatbot here:  
[Smart Campus Assistant (Dialogflow Demo)](https://console.dialogflow.com/api-client/demo/embedded/7c49fa8f-f5f9-4c7a-8b27-c2ead25d1f35)

---

## Project Overview

This repository contains the **Smart Campus Assistant**, a chatbot built using **Google Dialogflow**.  
It serves as a summative assessment project for the WACP course, *Artificial Intelligence: Real-World Applications and Implications*.

The primary goal of this chatbot is to assist newcomers and regular campus users — including students, parents, staff, and visitors — by providing quick, accurate answers about:

- Department locations  
- Event venues  
- Office hours  
- Campus policies  
- Transportation options  
- Emergency contacts  

This AI assistant acts as a reliable, interactive guide that enhances the overall campus experience.

---

## Target Users

The chatbot is designed to support the following groups:

- New Students  
- Staff Members  
- Parents  
- Visitors and Guests  

---

## Intents and Entities

This chatbot was implemented with **15 intents** and **10 custom entities** to efficiently process user inputs and provide relevant responses.

---

### Intents

| Intent Name             | Description                                                                 | Example User Queries                                    |
| :---------------------- | :-------------------------------------------------------------------------- | :------------------------------------------------------ |
| Default Welcome Intent  | Greets the user and starts the conversation.                                | “Hi”, “Hello”, “Hey there”                              |
| Default Fallback Intent | Handles unknown or unrecognized user inputs.                                | “??”, “I don’t understand”, “What?”                     |
| any                     | When the user has no specific preference or restriction.                    | “Anything works”, “I’m fine with any”                   |
| Avoid dairy and gluten. | Captures users who want to exclude dairy or gluten from their diet.         | “Avoid dairy”, “No gluten please”, “Lactose intolerant” |
| Golden                  | Handles responses related to the *Golden* diet package tier.                | “Tell me about the golden plan”, “I want golden”        |
| hey there               | Friendly greeting intent.                                                   | “Hey there!”, “Hi bot”                                  |
| No allergies            | Captures users who have no allergies.                                       | “No allergies”, “I can eat anything”                    |
| non veg                 | Captures users who eat non-vegetarian food.                                 | “I eat meat”, “Non-veg”, “Chicken is fine”              |
| Peanuts                 | Allergy-specific intent for peanuts.                                        | “I’m allergic to peanuts”, “Avoid peanuts please”       |
| Platinum                | Handles responses related to the *Platinum* diet package tier.              | “Platinum plan”, “Tell me about platinum”               |
| purpose                 | Identifies the user’s goal (e.g., fitness, weight loss, muscle gain, etc.). | “I want to gain muscle”, “My purpose is fitness”        |
| Silver                  | Handles responses related to the *Silver* diet package tier.                | “Silver plan”, “I want silver”                          |
| Thank you               | Handles gratitude and polite closure.                                       | “Thanks”, “Thank you”, “Appreciate it”                  |
| veg                     | Captures users who prefer vegetarian food.                                  | “I’m vegetarian”, “Veg only please”                     |
| vegan                   | Captures users who prefer a vegan diet.                                     | “I’m vegan”, “No animal products”                       |
| yes                     | Positive confirmation intent.                                               | “Yes”, “Sure”, “Okay”                                   |

---

### Entities

| Entity Name   | Description                                                   | Examples                                                       |
| :------------ | :------------------------------------------------------------ | :------------------------------------------------------------- |
| @diet_type    | Captures the user’s dietary preference.                       | “Veg”, “Non-veg”, “Vegan”, “Any”                               |
| @allergy_type | Captures specific food allergies or intolerances.             | “Peanuts”, “Dairy”, “Gluten”, “Soy”                            |
| @package_tier | Captures the selected diet plan tier or subscription level.   | “Silver”, “Golden”, “Platinum”                                 |
| @restriction  | Captures specific food restrictions or avoidance preferences. | “Avoid dairy”, “No gluten”, “No sugar”                         |
| @confirmation | Captures user confirmation or consent.                        | “Yes”, “Sure”, “Okay”, “Go ahead”                              |
| @greeting     | Captures user greetings.                                      | “Hello”, “Hey there”, “Hi”                                     |
| @purpose      | Captures the user’s fitness or health goal.                   | “Weight loss”, “Muscle gain”, “Stay fit”                       |
| @gratitude    | Captures expressions of thanks or politeness.                 | “Thanks”, “Thank you”, “Appreciate it”                         |
| @no_allergy   | Captures when the user indicates they have no allergies.      | “No allergies”, “I can eat everything”, “No food restrictions” |

---

## Integration Details

- **Platform:** Built and hosted on *Google Dialogflow Essentials*.  
- **Slot-Filling:** Used in certain intents (e.g., `find_professor_office`) to gather all required parameters before responding.  
- **Rich Responses:** Implemented to improve engagement and user experience.  

### Rich Response Types
- **Suggestion Chips:** Offer navigation or quick-reply options such as “View Map” or “Get Directions.”  
- **Media Responses:** Display relevant images (like maps, menus, or banners) to enhance clarity and visual appeal.  

---

## Deployment Instructions

The chatbot is already live and accessible through the link shared above.  
To explore or modify the agent:

1. Open **Google Dialogflow Console**.  
2. Import the agent using the `.zip` file or recreate intents/entities manually.  
3. Test responses in the integrated simulator.  
4. Optionally, embed the chatbot into a website using Dialogflow’s HTML iframe code.  

---

## Conclusion

The **Smart Campus Assistant** demonstrates how conversational AI can make everyday campus interactions faster, friendlier, and more efficient.  
By blending **AI-based intent recognition** with **custom entities**, the chatbot personalizes responses and enhances the overall user experience.

---

*Created by Jashith Hemendra Rathod — Aspee Nutan Academy (Grade 11)*  
*Course: Artificial Intelligence — Real-World Applications and Implications*
