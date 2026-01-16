# 01 Setup
To use it, simply add the CharacterFireVFX (Actor Component) to your character Blueprint or Actor. Once added, the component automatically assigns the overlay fire material to the character mesh and sets up the required Niagara systems.


## Step 1
Add the Character Fire VFX Actor Component to your character Blueprint or Actor.

<img width="200" height="141" alt="Setup01_0" src="https://github.com/user-attachments/assets/41b76a04-5d90-41e4-92a7-2412e3acce06" />


## Step 2
Assign your character’s Skeletal Mesh Component and the Niagara System Component to the Fire Actor Component function - 'Initialize Character Fire VFX'.

<img width="653" height="387" alt="Setup01_1" src="https://github.com/user-attachments/assets/f54e70af-8155-4195-90a6-8a0994610cef" />


## Step 3
Fine-tune all parameters in Actor Component - 'Character Fire VFX'.

<img width="1677" height="942" alt="Setup01_2" src="https://github.com/user-attachments/assets/3b1ece94-7cd8-4526-9da9-5fe79e3519af" />

## Note
The component automatically assigns the required Niagara system to the Default Actor Niagara System. However, if you want to adjust its parameters, you will need to manually reassign the Niagara system. Once assigned, the parameters will appear in the Details panel for easy editing.

<img width="1920" height="938" alt="AssignNiagara" src="https://github.com/user-attachments/assets/50390d31-ffdd-40c4-9d91-454b73081467" />

