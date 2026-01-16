
Place the modular Fire VAT meshes (Cone, ,Semisphere, Sphere, Cylinder, and Tube) around the character. Adjust scale, rotation, and position to create a complete fire wrap.
<img width="1288" height="326" alt="FireMesh" src="https://github.com/user-attachments/assets/f412e3fe-9f2c-4609-bb4c-7ef6dfa215a7" />


## Step 1
Create a data asset, and choose class - 'CharacterFireMeshDA'

<img width="173" height="107" alt="FireMesh_01" src="https://github.com/user-attachments/assets/dcbc1ac1-97d6-40a1-915c-d5f783ed8429" />

<img width="637" height="419" alt="FireMesh_02" src="https://github.com/user-attachments/assets/518c9686-022b-4cf0-b5ff-03a350c7f63c" />

## Step 2
Assign the data asset to the CharacterFireVFX component in the details panel under 'Character Fire VFX/Config/Niagara System/Fire Mesh Data Asset and enable the Mesh Particle

<img width="1907" height="937" alt="FireMesh_03" src="https://github.com/user-attachments/assets/d90ba35b-7c2f-41b4-84d6-3378d2dab281" />

## Step 3
Create a child actor from your character Blueprint Actor.

<img width="392" height="791" alt="FireMesh_0" src="https://github.com/user-attachments/assets/355d949f-fc96-43c9-9e80-915a4d00ada4" />

## Step 4
Add the Fire Mesh (Static Mesh Component) above to your character Blueprint or Actor, put it under Skeletal Mesh and attach to a desire parent socket.

<img width="1918" height="950" alt="FireMesh_1" src="https://github.com/user-attachments/assets/40e2cd90-4178-4c9f-8d80-e15b08a63feb" />


## Step 5
In Construction Script, assign Skeletal Mesh Component and the Niagara System Component to the Fire Actor Component function - 'Bind Fire Mesh to Data Asset'

<img width="934" height="412" alt="FireMesh_2" src="https://github.com/user-attachments/assets/767ae0d5-14e4-48be-b342-cf136350eb9b" />

