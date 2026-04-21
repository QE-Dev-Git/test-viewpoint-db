# Test Viewpoint Database (Project)

## Purpose
This document defines test viewpoints derived from defect analysis for this specific project.

---

## Failure Pattern List

---

### 1. In-Process × User Action

- Defect: UI inconsistency during screen transition while processing
- Condition: Processing (communication, save, load)
- Action: Screen transition, back, input
- State: Incomplete

Viewpoints:
- UI consistency during processing
- State preservation when interrupted
- Input control before process completion

---

### 2. State Transition Boundary

- Defect: State inconsistency during transition
- Condition: Before/after transition
- Action: Repeated actions, back
- State: Boundary

Viewpoints:
- Impact of actions before state confirmation
- State flag synchronization
- Post-transition action control

---

### 3. Communication Change

- Defect: Data inconsistency during network interruption
- Condition: Network ON/OFF, delay
- Action: Normal operation
- State: In communication / switching

Viewpoints:
- Behavior during network disconnection
- Resynchronization after recovery
- Timeout handling during delay

---

### 4. Boundary Values

- Defect: Failure when input reaches maximum value
- Condition: Max/Min/length limit
- Action: Save/update
- State: Normal

Viewpoints:
- Handling of boundary inputs
- Overflow error handling
- Handling of NULL/zero

---

### 5. Multiple Actions

- Defect: Duplicate execution due to rapid repeated actions
- Condition: Rapid repeated input
- Action: Button tapping
- State: Processing

Viewpoints:
- Duplicate execution prevention
- Concurrency control
- Input locking

---

### 6. Initial State

- Defect: Crash on immediate operation after screen load
- Condition: Initial display
- Action: Immediate operation
- State: Uninitialized

Viewpoints:
- Control before initialization completes
- Loading state UI handling

---

### 7. Inconsistent Data State

- Defect: System continues with incomplete data
- Condition: Partial data
- Action: Next operation
- State: Inconsistent

Viewpoints:
- Detection of invalid data
- Operation restriction under invalid state

---

### 8. High Load

- Defect: Delay under high load
- Condition: High system load
- Action: Normal operation
- State: Delayed

Viewpoints:
- Response control under load
- Timeout handling

---

### 9. Transition Input

- Defect: Data loss during screen transition input
- Condition: Screen transition
- Action: Input / back
- State: Transitioning

Viewpoints:
- Input handling during transition
- Data loss prevention

---

### 10. Recovery from Failure

- Defect: State inconsistency after abnormal recovery
- Condition: Crash / network failure
- Action: Resume
- State: Recovery

Viewpoints:
- State restoration
- Data consistency after recovery
