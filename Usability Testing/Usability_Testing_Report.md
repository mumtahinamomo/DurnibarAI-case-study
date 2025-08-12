# Usability Testing Report – DurnibarAI

**Method:** In-person, task-based usability testing with NASA TLX cognitive load assessment  
**Prototype Tested:** High-fidelity prototype of DurnibarAI

---

## 1. Overview
This usability testing session was conducted to evaluate the clarity, ease of navigation, and cognitive workload of key tasks within the DurnibarAI prototype before moving forward with MVP development. The test measured both qualitative observations and quantitative workload metrics using the NASA Task Load Index (TLX).

Participants completed tasks in the prototype while verbalizing their thought process. After completing each task, they filled out the NASA TLX questionnaire to rate perceived workload across Mental Demand, Physical Demand, Temporal Demand, Performance, Effort, and Frustration.

---

## 2. Participants & Tasks

### Participant 1: Arthur – Casual Fitness User
- **Task:** Locate and interpret streak progress; review notifications related to daily fitness goals.  
- **Raw TLX Results:** [View PDF – TLXScale Arthur](./TLXScale_Arthur.pdf)

### Participant 2: Noah – Recovery-Focused Athlete
- **Task:** View workout progress graphs; explore AI-generated workout recommendations.  
- **Raw TLX Results:** [View PDF – TLXScale Noah](./TLXScale_Noah.pdf)

---

## 3. Methodology

**Testing Environment:**
- Conducted in-person with individual sessions lasting ~20–30 minutes.
- Prototype displayed on a laptop to simulate real application interaction.

**Procedure:**
1. Introduction to the test and prototype.
2. Participant assigned a specific task matching their fitness persona.
3. Observation of navigation behavior, hesitations, and errors.
4. Post-task completion of NASA TLX to quantify perceived workload.

**Metrics Collected:**
- Task completion rate.
- NASA TLX scores (mental, physical, temporal demand; performance; effort; frustration).
- Observed navigation time and error patterns.

---

## 4. Results Summary

### Arthur – Streaks & Notifications
- **Observations:** Found streak feature easily but notifications lacked visibility and motivational tone.
- **Cognitive Load:** Low mental and physical demand; minimal frustration.
- **Implication:** Feature is discoverable but lacks engagement hooks to sustain motivation.

### Noah – Progress Tracking & AI Recommendations
- **Observations:** Required additional steps to locate progress graphs; understood AI recommendations but lacked context for why they were suggested.
- **Cognitive Load:** Higher mental demand than Arthur; moderate temporal demand; low physical demand.
- **Implication:** Navigation flow could be streamlined; recommendation clarity could improve trust in AI.

---

## 5. Key Findings

1. **Navigation Efficiency Needs Improvement**  
   During testing, both participants required extra steps to move between primary sections of the app. The absence of a persistent navigation element increased cognitive load, particularly for Noah, who had to reorient herself multiple times when switching features. This indicates the need for a more direct and consistent navigation mechanism.

2. **Motivational Reinforcement in Notifications is Limited**  
   While Arthur easily located the streak feature, he noted that notifications did not effectively draw his attention or create a sense of achievement. The current notification design lacks strong visual cues and motivating language to reinforce streak progress or highlight milestones, reducing its ability to maintain user engagement over time.

---

## 6. Recommendations

1. **Introduce a Persistent Bottom Navigation Bar**  
   Implement a bottom navigation bar that is visible across all primary screens (e.g., Home, Progress Tracking, AI Recommendations, Nutrition) to enable faster and more intuitive switching between sections. This will reduce the need for users to repeatedly navigate back to the home screen, lowering cognitive load and improving task completion time.

2. **Redesign Notifications to Reinforce Motivation**  
   Enhance notification visibility and engagement by integrating visual badges, progress indicators, and motivational microcopy (e.g., “You’re on a 5-day streak — keep going!”). This will make streak tracking more prominent and reinforce positive behavior through clear, encouraging feedback.

---

## 7. Next Steps

1. **Design Updates**  
   - Integrate bottom navigation into the prototype and ensure it is consistent across all main screens.  
   - Redesign notifications with stronger visual hierarchy and motivational content.  
   - Update AI recommendation cards to display a brief “reason for suggestion” message.

2. **Prototype Iteration & Internal Review**  
   - Update the clickable prototype with the above design changes.  
   - Conduct an internal review with the design and engineering teams to confirm feasibility and alignment with the product roadmap.

3. **Second-Round Usability Testing**  
   - Recruit at least 5 participants with diverse fitness profiles.  
   - Repeat key tasks from this round to measure improvements in navigation speed, notification engagement, and trust in AI recommendations.  
   - Compare NASA TLX scores pre- and post-changes to validate reduction in cognitive load.
