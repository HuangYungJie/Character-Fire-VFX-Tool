# 04 Vertex Color

This function uses vertex color as a mask to control where fire appears on the mesh. Fire particles will only be generated in areas where vertex color is present, allowing you to erase or grow fire by painting vertex colors. This provides precise, artist-driven control over fire coverage on any static or skeletal mesh.

## Step 1
In the CharacterFireVFX component’s Details panel, enable "Use Vertex Color Mask (R)" to activate vertex color masking.

<img width="1884" height="920" alt="EnabelVertexColor" src="https://github.com/user-attachments/assets/67bfdebf-c7d1-4cb7-9275-88153f8ef5a3" />


## Step 2
Swtich to the Mesh Paint Mode and paint vertex colors directly onto the character.

<img width="1503" height="897" alt="VertexColorPaint" src="https://github.com/user-attachments/assets/a15bc264-da95-419d-b7d9-cccf85878be0" />

