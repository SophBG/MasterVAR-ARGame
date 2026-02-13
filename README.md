# Whack-a-Mole AR 🔨

An Augmented Reality adaptation of the classic arcade game, developed for the **Microsoft HoloLens 2** using Unity and MRTK.

This project was developed as the **Final Project** for the Augmented Reality course within the **Master's degree in Virtual and Augmented Reality**.

## 📖 About the Project

The goal of this project was to explore physical interactions in AR. The game leverages the Mixed Reality Toolkit (MRTK) to simulate a tactile arcade experience.

## 🎮 How to Play

The game uses **Hand Tracking**. You don't need controllers; simply use your hands to interact with the moles.

* **Hit the Moles:** Punch or tap the moles when they pop up to score points.
* **Time Management:**
    * ✅ **Hit correctly:** You gain extra time.
    * ❌ **Miss:** You lose time.
* **Mole Types:**
    * **Standard Mole:** Requires **1 hit**.
    * **Tough Mole:** Requires **2 hits** to be defeated.
* **Avoid Bombs:** Do not hit the bombs, or you will lose the game!

## 📂 Project Structure & Setup

**⚠️ Important:** This project was built upon the standard **MRTK Template**.

To keep the project organized and separate from the core MRTK files, all custom assets, scripts, prefabs, and the main scene are located in a specific folder:

> **Location:** `Assets/WhackAMole/`

### To Run the Project:
1.  Clone this repository.
2.  Open the project in **Unity** (Ensure you have the MRTK dependencies installed).
3.  Navigate to `Assets/WhackAMole/`.
4.  Open the scene file located in that folder.
5.  Press **Play** in the editor (using MRTK Input Simulation) or deploy to HoloLens 2.

## 🛠️ Tech Stack

* **Engine:** Unity 3D
* **Framework:** Microsoft Mixed Reality Toolkit (MRTK)
* **Hardware Target:** HoloLens 2 (Tested via Unity Editor Simulation)
* **Language:** C#
