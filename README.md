# Cheat Engine Modification Guide 🚀

Welcome to the **Cheat Engine Modification Guide**! This comprehensive guide empowers you to delve into the intricacies of game memory modification with a futuristic twist. Use these techniques responsibly, respecting game terms and ethical boundaries.

## Cheat Codes 🕹️

| **Cheat Code** | **Description** | **Usage** |
| --- | --- | --- |
| `CTRL+B` | Open the Cheat Engine "Browse Memory Region" window for value scanning. | Scan for initial values in the game. |
| `CTRL+ALT+A` | Open the Auto Assemble window. | Inject custom assembly code. |
| `CTRL+I` | Open the Disassembler window. | View and analyze the game's assembly code. |
| `CTRL+D` | Toggle the Disassembler's "Show as hexadecimal" option. | Disassemble instructions. |
| `CTRL+L` | Open the "List of addresses" window. | View and manage memory addresses. |
| `CTRL+R` | Refresh the Cheat Engine process list. | Update information about the game. |

## Cheat Engine Step-by-Step Modification Guide: Become an Expert! 🎓

### Objective 🎯

Explore pointer and multi-pointer modifications in a game, focusing on health, movement speed, and dynamic health increase triggered by enemy actions.

### Prerequisites 🛠️

- [Download and Install Cheat Engine](https://www.cheatengine.org/downloads.php)
- Basic understanding of assembly code and game mechanics

### Step 1: Discover Initial Values 🚀

1. **Launch Cheat Engine:**
   - Open Cheat Engine and attach it to your game process.

2. **Scan for Initial Values:**
   - Observe your player attributes (e.g., health, speed).
   - Scan for initial values using Cheat Engine.

### Step 2: Infinite Health Pointer 💉

3. **Identify Health Pointer:**
   - Get damaged in the game.
   - Scan for changed health values.
   - Find pointers to the health address (CTRL+B).

4. **Infinite Health Script:**
   - Open Auto Assemble (CTRL+ALT+A).
   - Add the following code:
     ```assembly
     mov [health_pointer], 9999
     ```
   - Press F5 to apply changes.
   - **Advanced Note:** To make health dynamic, consider monitoring enemy actions and adjust health accordingly.

### Step 3: Increased Speed Pointer 🏃‍♂️

5. **Identify Speed Pointer:**
   - Observe your player's movement speed.
   - Scan for current speed values.
   - Find pointers to the speed address (CTRL+B).

6. **Increased Speed Script:**
   - Open Auto Assemble (CTRL+ALT+A).
   - Add the following code:
     ```assembly
     mov [speed_pointer], 2.0
     ```
   - Press F5 to apply changes.
   - **Advanced Note:** Experiment with speed adjustments based on game dynamics, such as different terrains or situations.

### Step 4: Enemy-Triggered Health Increase 💪

7. **Observation:**
   - Notice health increase when an enemy is damaged or killed.
   - Scan for changes after enemy damage or kill.

8. **Identify Code:**
   - Find the code responsible for health increase (CMP instructions).

9. **Injection Code:**
   - Open Auto Assemble (CTRL+ALT+A).
   - Add logic to increase your health when the enemy is damaged or killed.
   - **Advanced Note:** Implement conditions for varying health boosts based on enemy actions.

### Step 5: Verification and Refinement ✅

10. **Test Modifications:**
    - Test the modifications in the game.

11. **Observe Results:**
    - Confirm infinite health, increased speed, and dynamic health increase.

12. **Refinement:**
    - Fine-tune the injected code for optimal results.
    - Implement safety checks to avoid unintended consequences.
    - **Advanced Note:** Explore additional game dynamics for more refined modifications.

### Step 6: Address and Offset Update 🔄

13. **Update Pointers:**
    - Update health, speed, and multi-level pointers as needed.

### Final Notes 📝

- Always use Cheat Engine responsibly and ethically.
- Respect the terms of service of the game or application.
- Modifications may have unintended consequences; test in a controlled environment.
- Only use these techniques for educational purposes.
- Regularly check and update scripts based on game updates.

Congratulations! You've successfully completed the **Cheat Engine Modification Guide**. Keep experimenting and refining your skills to become an expert at game memory modification! 🚀



This advanced guide includes additional notes and examples to help users enhance their skills over time. Feel free to copy and paste this markdown content into your `README.md` file on GitHub.
