# Automata-Driven Validation of Musical Chord Progressions Using an NFA Model

## 📌 Project Overview
This project implements a **real-time chord progression validator** based on **functional harmony** and **automata theory**. It models harmonic movement using a **Nondeterministic Finite Automaton (NFA)** that allows chord progressions to be evaluated incrementally as they are entered.

Rather than relying on opaque machine-learning models, the system encodes **explicit harmonic rules** derived from common-practice Western tonal music. Each chord is interpreted according to its harmonic function **(Tonic, Predominant, or Dominant)**, and transitions between chords are validated against the NFA’s transition logic.

The goal of the project is to provide a transparent, rule-based, and educational tool that supports music learning and composition by giving immediate feedback on harmonic correctness.

---

## ✨ Objectives
**1. Functional Harmony–Based Validation**
- Validates chord progressions using the standard functional-harmony model (Tonic → Predominant → Dominant → Tonic). 

**2. Nondeterministic Finite Automaton (NFA)**
- Supports harmonic ambiguity by evaluating multiple possible functional interpretations in parallel.

**3. Real-Time Feedback**
- Chord progressions are checked incrementally as they are entered, with immediate valid/invalid indicators.
  
**4. Rule-Based Transparency**
- All validation logic is based on explicit harmonic rules rather than statistical inference or black-box models.
  
**5. Educational Focus**
- Designed to help learners understand why a progression is valid or invalid according to tonal harmony.
   
**6. Web-Based Prototype**
- Runs locally in a browser using a modern JavaScript development environment.

---

## 🛠️ Tech Stack
- JavaScript / TypeScript
- Node.js
- npm
- Web-based UI framework (e.g., React / Vite, depending on implementation)
- Finite Automata logic (custom NFA engine)

---

## 📋 Getting Started

### Prerequisites
Make sure you have the following installed:

- Node.js (v16 or later recommended)
- npm (comes with Node.js)

You can check your installation with:

```cmd
node -v
npm -v
```

### Installation
Clone the repository and install dependencies:

```cmd
git clone <your-repository-url>
cd <project-folder>
npm install
```

### Running the Project
Start the development server using:

```cmd
npm run dev
```

---

## 🎵 How to Use
1. Enter chord symbols (e.g., I, ii, IV, V, vi) into the input field.
2. Chords are processed sequentially as part of a progression.
3. The system evaluates each chord transition using the NFA.
4. Visual feedback indicates whether the progression remains valid or has violated harmonic rules.
5. Invalid transitions are flagged immediately.

---

## 🎶 Harmonic Model Summary
Chords are classified into harmonic functions:
- Tonic
- Predominant
- Dominant

The NFA enforces:
- Goal-directed harmonic flow
- Resolution to tonic for acceptance
- Rejection of functional retrograde motion
- Controlled flexibility (e.g., predominant prolongation, plagal resolution)

---

## ⚠ Limitations
- Supports common-practice Western tonal harmony only
- No modulation or key detection
- No audio input (symbolic chord input only)
- Jazz extensions and non-functional harmony are not supported
- Prototype-level UI and feature set

---

## Group 4 Members
- Bernabe, Julliane Triselle H.
- Bolante, Gabriel B.
- Fortus, Ralph Wendel M.
- Petero, Sean Richard C.
- Punzalan, Sherinne Deziree D.
- Salazar, Clarisse Jem T.
- Vicedo, Christian D.

---

<p align="center">✨ Functional harmony, now state-approved ✨</p>
