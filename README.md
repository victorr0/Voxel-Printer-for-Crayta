# Voxel-Printer-for-Crayta
Print any 3D model, from it's individual voxel positions, allowing custom import of models as plain text. Uses the SetVoxel()  from the Crayta API

# Convert 3D model
Take your desired 3D model and convert it to the voxel geometry data. This can be done with Blender, or Voxelizer https://drububu.com/miscellaneous/voxelizer/index.html
Download the coordinates as json, they go in a new script file as a property. 

# Add printerScript to mesh
Add printerScript to an empty voxelmesh, also add a script folder to that voxelmesh where the model geometry data script file should be added

# Set the properties 
Set the voxelmesh it's script properties, select the script from the script folder as your modelScript

# Now print your model
In Editor mode you can simulate the empty mesh that printerScript is attached to for some satisfying voxel magic. 

