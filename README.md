1. Start (Initial State)
Description: The diagram begins with the “Start” state, representing the initiation of traffic monitoring at Gishushu. This state leads into the first identified traffic condition, which is generally Low Traffic unless there’s an immediate change.
2. Low Traffic
Description: Low Traffic represents the state during off-peak hours, where traffic flow is light. This state typically occurs in the early morning, late evening, or other low-activity times.
Transitions:
If it becomes Rush Hour (e.g., morning rush between 7–9 AM or evening rush between 5–7 PM), traffic state transitions to High Traffic.
If it’s not Rush Hour, the traffic stays in Low Traffic.
3. High Traffic
Description: High Traffic is a peak traffic state, representing congestion or heavy flow due to high demand, typically during rush hours.
Transitions:
If there’s an Accident or Incident (e.g., roadblock, accident), the state shifts to Incident.
If Rush Hour Ends or demand decreases (off-peak), traffic flow goes back to Low Traffic.
4. Incident
Description: The Incident state represents unexpected disruptions like accidents, roadblocks, or events that worsen traffic flow.
Transitions:
If the Incident is Cleared, the system assesses whether it’s still rush hour:
If yes, it returns to High Traffic.
If no, it moves to Low Traffic.
5. Resolved (Final State)
Description: The Resolved state signifies a return to normal, stable traffic conditions with no incidents or peak congestion.
Transitions:
This state can be re-entered after any incident or heavy traffic episode that resolves.
Summary of Workflow
The diagram flows from the Start state, entering Low Traffic initially. Depending on whether it’s a rush hour or there’s an accident, traffic can transition to High Traffic or Incident. Each state change is decided by specific conditions, guiding traffic flow management for smoother transitions.
