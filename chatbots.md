## AI Agent and Chatbot Development

Using Dialogflow CX

### 1. Language Tutor

This project is an interactive language-learning assistant designed to help users translate phrases, receive grammar tips or vocabulary quizzes, and practice conversations in different languages. The system is structured with a main “Start Page” connected to three functional modules—Translation, Tips or Quiz, and Conversation—each triggered through user options. The Translation module enables users to input a phrase and target language to generate translated sentences. The Tips or Quiz module offers grammar guidance or vocabulary quizzes based on the chosen language. The Conversation module provides realistic dialogue practice on user-selected topics. Each feature is powered by custom generators linked through intents and routes, supported by entities for input handling and event handlers to manage missing information, ensuring smooth and responsive user interactions.This project is an interactive language-learning assistant designed to help users translate phrases, receive grammar tips or vocabulary quizzes, and practice conversations in different languages. The system is structured with a main “Start Page” connected to three functional modules—Translation, Tips or Quiz, and Conversation—each triggered through user options. The Translation module enables users to input a phrase and target language to generate translated sentences. The Tips or Quiz module offers grammar guidance or vocabulary quizzes based on the chosen language. The Conversation module provides realistic dialogue practice on user-selected topics. Each feature is powered by custom generators linked through intents and routes, supported by entities for input handling and event handlers to manage missing information, ensuring smooth and responsive user interactions.

[Video demo](https://drive.google.com/file/d/1FbTe5jiv6ncUq-thoQ4EJ3T5PxV5oSWC/view?usp=drive_link)


### 2. Travel Booking Agent

This project is a travel booking agent that allows users to view, book, or cancel flights, hotels, and car rentals through an interactive system. The process begins with a “User Option” intent that routes users from the “Start Page” to specific booking pages such as “Book Flight,” “Book Hotel,” or “Book Car.” Key parameters—including destination, travel dates, number of travelers, and preferences—are used to personalize results. The system integrates webhooks (“Display Car,” “Display Hotel,” and “Display Flight”) connected to their respective pages, ensuring dynamic data retrieval. A JSON file stores details of available travel options, which the agent filters based on the user’s input, displaying only the relevant matches to streamline the booking experience.

[Video demo](https://drive.google.com/file/d/1dZ4vT9wNqhx7K9paCB6ekYwJbATZFvc-/view?usp=drive_link)


### 3. Appointment Scheduler

This project is an appointment scheduler designed to help users easily book, reschedule, or cancel appointments for doctors, salons, or spas. The process begins with an “Options” intent that connects the “Start Page” to the “Appointment” page based on the user’s selected service type. Within the Appointment page, the system collects key parameters such as the user’s name, preferred date, and time. A webhook named “Appointments” then cross-references these details with stored appointment data in a JSON file to confirm availability. If a matching slot exists, the appointment is successfully scheduled; otherwise, the system displays all available time slots. Additionally, the flow allows users to reschedule by redirecting them to the Start Page or cancel an appointment by ending the session, ensuring a smooth and user-friendly scheduling experience.

[Video demo](https://drive.google.com/file/d/1yxXyRzx024zOeJ9YCObibiYLBApNbd96/view?usp=drive_link)


### 4. Content generator

This project is a content generator designed to produce and customize information based on user-selected topics. The process starts with a “Topic” intent that links the “Start Page” to the “Content Generator” page. A generator named “Content Generator” retrieves and presents information about the user’s chosen topic using the variable $session.params.topic. The system then allows further refinement through a “Condition” intent, which connects the “Content Generator” page to a “Customize Content” page. Here, another generator, “Content Customization,” creates a personalized version of the original content stored in $session.params.content. This setup enables users to not only generate topic-specific content but also tailor it to their preferences, providing a dynamic and interactive content creation experience.

[Video demo](https://drive.google.com/file/d/12sudkYu6g99vqIHAF2j2hwkThTw-cslh/view?usp=drive_link)

