# 🕊️ **BAYANI: Ang Mamatay Para Sa…**

> *“A reimagining of Philippine history through the lens of sacrifice, struggle, and the Filipino spirit.”*

---

## 📖 **Overview**

**BAYANI: Ang Mamatay Para Sa…** is a 3D third-person action-adventure prototype developed in Unity.
Players experience the final moments of iconic Filipino heroes — *Andres Bonifacio, Lapu-Lapu, and Benigno “Ninoy” Aquino Jr.* — from multiple perspectives.
Each level combines stylized low-poly art with cinematic storytelling and moral reflection on what it means to die for one’s country.

---

## 🎮 **Game Concept**

| Element         | Description                                                                                          |
| --------------- | ---------------------------------------------------------------------------------------------------- |
| **Genre**       | 3D Action Adventure / Narrative                                                                      |
| **Perspective** | Third-person, over-the-shoulder                                                                      |
| **Art Style**   | Low-poly, semi-realistic Filipino architecture and landscapes                                        |
| **Theme**       | Patriotism, sacrifice, national identity                                                             |
| **Core Loop**   | Play as a hero → fight against enemies → switch perspective to the opposing side → relive their fall |
| **Final Scene** | Ninoy Aquino assassination sequence symbolizing the cyclical nature of heroism and sacrifice.        |

---

## 🧱 **Project Structure**

```plaintext
Assets/
 ├─ Scenes/            → Level scenes (Intramuros, Mactan, NAIA)
 ├─ Scripts/           → Player, camera, UI, and gameplay logic
 ├─ Prefabs/           → Player, enemy, environment prefabs
 ├─ Models/            → Low-poly 3D assets
 ├─ UI/                → HUD and menu assets
Packages/
ProjectSettings/
.gitignore
README.md
```

---

## ⚙️ **Setup Instructions**

### 🪜 Requirements

* **Unity Version:** 2022.3 LTS or later (URP optional)
* **IDE:** Visual Studio Code / Visual Studio 2022
* **Version Control:** Git + GitHub

### 🧩 Steps to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/riella-0/BAYANI-Ang-Mamatay-Para-Sa.git
   ```
2. Open Unity Hub → *Add Project from Disk* → select the cloned folder.
3. Open the scene:

   ```
   Assets/Scenes/Intramuros.unity
   ```
4. Click **Play** in the Unity Editor to run the prototype.

---

## 🧑‍💻 **Development Workflow**

### 🪶 Branch Naming Convention

| Type    | Example                   | Purpose                    |
| ------- | ------------------------- | -------------------------- |
| Main    | `main`                    | Stable, tested builds only |
| Feature | `feature/player-controls` | New features or mechanics  |
| Fix     | `fix/ui-healthbar-bug`    | Bug fixes                  |
| Test    | `test/lighting-pass`      | Temporary experiments      |

### 🔄 Workflow

1. **Pull latest** changes from `main`.
2. **Create a new branch** for your feature.
3. Commit and **push to your branch**.
4. Create a **Pull Request** → wait for review.
5. Once approved, **merge** into `main`.

---

## 👥 **Team BAYANI**

| Role                                      | Member                             | Responsibilities                           |
| ----------------------------------------- | ---------------------------------- | ------------------------------------------ |
| **Project Manager / Lead Designer**       | [TBA]                              | Game design, direction, scheduling         |
| **Programmers**                           | [TBA]                              | Core mechanics, camera, and gameplay logic |
| **Machine Learning Engineer / QA Tester** | [TBA]                              | Player controls, testing, data systems     |
| **Environment & 3D Artists**              | [TBA]                              | Low-poly terrain, lighting, props          |
| **Animator / Technical Artist**           | [TBA]                              | Player and NPC animations                  |
| **Sound Designer**                        | [TBA]                              | Music and SFX integration                  |
| **UI/UX Designer**                        | [TBA]                              | HUD and menu design                        |
| **Narrative & Script Writer**             | [TBA]                              | Voiceover, narration, and dialogue         |

*(You can edit the “TBA” roles once final.)*

---

## 🎨 **Art & Technical Direction**

* **Art Style:** Low-poly inspired by Filipino cultural motifs and landscapes
* **Lighting:** Real-time directional light with baked shadows
* **UI Design:** Minimalist HUD using clean sans-serif typefaces
* **Camera System:** Over-the-shoulder tracking with cinematic transitions
* **Audio:** Filipino-inspired instrumental themes (kulintang, kudyapi, drums)
* **Engine:** Unity 2022 LTS (C#)

---

## 🧪 **Playtesting Log**

Playtest results and feedback are tracked via shared document:
**[Playtest Sheet – Week 2](#)** (replace with Google Sheets link)

Each playtest records:

* Date & Tester
* Build Version
* Feedback Summary
* Assigned Fix
* Status

---

## 📅 **Development Milestones**

| Week       | Deliverable                            | Description                                    |
| ---------- | -------------------------------------- | ---------------------------------------------- |
| **Week 2** | Scene Setup, Player Controls, Basic UI | Implement base environment and player movement |
| **Week 3** | Enemy AI, Perspective Shift System     | Create simple NPCs and camera switch mechanic  |
| **Week 4** | Combat Mechanics                       | Add melee/shooting functionality               |
| **Week 5** | Level Design & Cutscenes               | Polish environments, integrate narration       |
| **Week 6** | Demo Build & Presentation              | Prepare 2-minute playable demo                 |

---

## ⚠️ **Disclaimer**

> This project is a creative reimagining intended to **honor Filipino heroes** and provoke reflection on the meaning of sacrifice.
> It does **not** intend to trivialize historical events or portray violence disrespectfully.
> All historical figures depicted are treated with cultural and moral respect.

---

## 🏁 **License**

This project is developed for academic purposes at
**Our Lady of Fatima University – College of Computer Studies**
© 2025 Team BAYANI. All rights reserved.