# Photoshop Layer Remixer and Image Generator
// Forked from Simple art generator by HashLips <->


How it works:

1. Save the PSD file inside the Photoshop Layer Remixer and Image Generator folder
2. Open the PSD file
3. In Photoshop, go to File > Scripts ... Then navigate to where you saved the Photoshop Layer Remixer and Image Generator folder and choose the "generate.js" file
4. Follow the prompts on Photoshop
5. A folder called "completed" with subfolders "images" and "metadata" will be generated within the Photoshop scripts folder.

Functions needed:

1. Script MUST be able to make choosing a layer from a certain folder group as MANDATORY (ex. folder: "Outfit")
2. Layer-matching: When x layer from group aaa has been selected, only select y layer from group bbb (Skip some layers when a specific layer has already been selected by the script)
SAMPLE SCENARIO: When the layer from the FACE/BODY group selected is from the SKINNY subfolder (Face/Body > Skinny > Medium), only select layers from Nose > Skinny from the NOSE group folder.
2. Option to select multiple layers from a group (folder) within the file (Ability to have 2-3 selections from a grouped layer)
SAMPLE SCENARIO: Script selects 2 layers from Body Marks (Note: Selection should be randomized)
3. Set a weight percentage of how many times a layer can be selected from the total number of images generated (THIS IS ALREADY WORKING IN THE SCRIPT AS-IS)
4. Allow skipping an entire folder as part of the randomized image generation from being included in the generated image when the script is running. (Ex. skip group folder "Accessories" as part of the randomized selection
SAMPLE SCENARIO: If the design has 14 layer groups/folders, it will be possible that some will have only 9, 8, 7 more or less from the 14 total layered groups/folders).

Note:
A. The main function for the script is generating random layer combinations, executing from the rules described above.
B. Script must check for duplicates. There must be NO generated design with the exact same layer combinations.
