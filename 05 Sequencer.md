# 05 Sequencer

Enable Use Sequencer Time in the CharacterFireVFX component’s Details panel under Character Fire VFX / Sequencer Time.

This feature uses a Material Parameter Collection to drive the frame index through the CharacterFireTime subsequencer. By adding CharacterFireTime to the Demo Sequencer, the fire shader can be controlled frame by frame directly within Sequencer.

## Step 1
In the CharacterFireVFX component's Details panel, enable "Use Sequencer Time" to activate time control in sequcner.

<img width="1915" height="948" alt="image" src="https://github.com/user-attachments/assets/51d60d36-c92d-4014-9e64-efcf5e754e56" />

## Step 2
Add the character to Sequencer.

<img width="498" height="260" alt="image" src="https://github.com/user-attachments/assets/35d18030-18ef-4ab0-871a-7a26a07a17e9" />

## Step 3
Add subsequence track 'CharacterFireTime' to Sequencer.

<img width="357" height="445" alt="image" src="https://github.com/user-attachments/assets/9d454c53-3a1e-48d1-af81-2f45accb8a20" />
<img width="623" height="231" alt="image" src="https://github.com/user-attachments/assets/bd2b6e4c-33da-4a77-adcd-a4c34f38f563" />

## Step 4
Add Niagara to Sequencer.
<img width="515" height="371" alt="image" src="https://github.com/user-attachments/assets/1cdb146d-c642-42ea-ac91-131fc2aacfdc" />

## Step 5
Add Niagara System Life Cycle track
<img width="899" height="549" alt="image" src="https://github.com/user-attachments/assets/7a950e2f-7b92-4ab1-8e93-3310481fea5d" />

## Step 6
Swithc the Niagara System Life Cycle to Desired Age, and adjust the duration.
<img width="642" height="390" alt="image" src="https://github.com/user-attachments/assets/ed6a0d8b-2b01-4909-af54-f63a59eea62f" />


