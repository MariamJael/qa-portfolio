# 🧪 QA Portfolio – Mariam

## 👤 About Me

I am a full-stack developer with a strong focus on Quality Assurance, test strategy, and system reliability.  
I work with both development and QA practices, including manual testing, Playwright automation, and structured bug reporting.

---

## 🎮 QA Approach

My testing approach focuses on real user behavior and system reliability:

- Validate core functionality through normal gameplay
- Identify edge cases and unexpected interactions
- Test UI and gameplay systems under rapid input conditions
- Reproduce issues consistently with clear steps
- Analyze player experience impact
- Document issues in a structured, developer-ready format

---

## 🧪 Exploratory Test – Vehicle & Interaction System (Brookhaven-style)

### 🎯 Objective

Test vehicle interaction, movement transitions, and system behavior under normal and rapid player actions.

---

## 🔁 Steps Performed

- Joined a live game session  
- Spawned and entered a vehicle  
- Drove normally around the map  
- Exited the vehicle  
- Re-entered the vehicle  
- Used vehicle interactions (horn/claxon and lights)  
- Switched to a bike and performed jump action  
- Exited bike and re-entered a vehicle  
- Resumed driving after multiple rapid transitions between systems  

---

## 📊 Expected Behavior

- Smooth transitions between vehicles and movement states  
- Vehicle controls (horn, lights) respond consistently  
- No delay or loss of input when switching between vehicles  
- Character animations remain stable across actions  
- No physics or state inconsistencies after repeated interactions  

---

## ⚠️ Observations / Risk Areas

- Potential inconsistency when switching rapidly between different vehicle types (car → bike → car)  
- Input timing sensitivity when performing multiple actions in sequence  
- Possible UI or control delay after repeated enter/exit actions  
- Risk of minor animation or state desynchronization during fast transitions  

---

## 🎥 Evidence

https://drive.google.com/file/d/1VgHLqudCgLfLdjJ8301QCEk-vE1PPuGG/view?usp=sharing

---

## 🧠 QA Thinking Summary

This test followed an exploratory testing approach:

- Started with normal gameplay (driving a vehicle)  
- Introduced system transitions (car ↔ bike)  
- Tested interaction features (horn, lights) during gameplay  
- Applied rapid state switching (enter/exit multiple times)  
- Observed system stability under real player-like behavior  

The goal was to evaluate how well the system handles continuous transitions between gameplay states and whether any inconsistencies appear under realistic user behavior.

---

## 🎯 Focus

My focus is on Quality Assurance in interactive systems where player behavior, real-time interactions, and system consistency are critical.
