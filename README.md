# Midterm_SystemDiagram

AlignMate is a smart posture assistant that helps users maintain proper posture by detecting poor posture through simulated keyboard inputs and providing real-time feedback. Users press specific keys to represent their posture:

'G' → Good Posture

'F' → Forward Lean

'S' → Slouched Back

'L' → Leaning to One Side

The Frontend/Desktop App captures this input and sends it to the Analysis Module, which determines whether the posture is good or bad. If the posture is bad, the system requests feedback from the LLM Service, which generates personalized advice on how to correct the posture.

The processed posture state and feedback are then sent to the UI Dashboard, where the user can see their posture status, receive improvement suggestions, and track posture trends over time. The system follows a structured flow: User Input → Analysis → Feedback Generation → Visualization, ensuring clear and actionable posture monitoring
