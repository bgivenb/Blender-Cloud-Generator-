Overview

Cloud Generator is a powerful Blender addon designed to create realistic and dynamic cloud formations, including Cumulus, Cumulonimbus, and Stratus clouds. With simple controls and customizable settings, artists and creators can generate volumetric cloud environments to enhance their 3D scenes.
Features

    Multiple Cloud Types:
        Cumulus: Fluffy, white clouds with distinct shapes.
        Cumulonimbus: Towering clouds often associated with thunderstorms.
        Stratus: Layered, flat clouds covering large areas.

    Customization Options:
        Hide Mesh: Option to hide the underlying mesh after generating volumetric effects.
        Add Sky: Automatically adds a realistic sky background to your scene.
        Target Detail: Adjust the level of detail in the generated clouds to balance between visual quality and performance.

    User-Friendly Interface:
        Easily accessible panel in the 3D Viewport sidebar.
        Intuitive controls and sliders for quick adjustments.

    Volumetric Effects:
        Realistic volumetric rendering for enhanced visual fidelity.
        Adjustable voxel settings for performance optimization.

Installation

    Download the Addon:
        Save the cloud_generator.py script to your computer.

    Install the Addon in Blender:
        Open Blender.
        Go to Edit > Preferences.
        Click on the Add-ons tab.
        Click Install... at the top.
        Navigate to where you saved cloud_generator.py and select it.
        After installation, enable the addon by checking the box next to Cloud Generator.

Usage

    Accessing the Addon:
        In the 3D Viewport, press N to open the sidebar.
        Navigate to the Cloud Generator tab.

    Generating Clouds:
        Cloud Type Selection:
            Choose between Cumulus, Cumulonimbus, or Stratus from the dropdown menu.
        Hide Mesh:
            Toggle the Hide Mesh checkbox to show or hide the underlying cloud mesh after applying volumetric effects.
        Add Sky:
            Enable the Add Sky checkbox to automatically add a realistic sky background to your scene.
        Target Detail:
            Adjust the Target Detail slider to control the decimation ratio. Lower values result in higher detail with more polygons, while higher values reduce polygon count for better performance.
        Generate Cloud:
            Click the Generate Cloud button to create the selected cloud type with your specified settings. NOTE: sometimes you may get a glitchy looking cloud, just delete it and try again. 
        Unhide Cloud Meshes:
            If you have hidden cloud meshes and wish to reveal them, click the Unhide Cloud Meshes button.


Customization

    Sky Texture Parameters:
        The addon sets up a default sky texture, but you can further customize it by modifying the Sky Texture node in the World shader:
            Select the World in the Shader Editor.
            Adjust parameters like Sky Type, Turbidity, and Ground Albedo to achieve different sky appearances.

    Extending Cloud Types:
        While the addon currently supports Cumulus, Cumulonimbus, and Stratus clouds, you can extend it by adding more cloud types following the existing structure in the script.

License

This project is licensed under the Creative Commons Zero (CC0 1.0 Universal) Public Domain Dedication. You are free to use, modify, and distribute this addon without any restrictions.
Support & Contact

For any questions, feedback, or support, please reach out via email:

📧 Email: bgivenb@gmail.com

Created by Given Borthwick
Troubleshooting

    Addon Not Appearing:
        Ensure that the addon is enabled in Edit > Preferences > Add-ons.
        Check for any syntax errors in the script if you're running it from the Text Editor.

    Cloud Not Generating Correctly:
        Verify that you have the correct settings selected in the Cloud Generator panel.
        Adjust the Target Detail slider to see if it affects the outcome.

    Performance Issues:
        Lower the Target Detail value to reduce polygon count and improve performance, especially on less powerful systems.

Contributing

This addon is released under the CC0 license, allowing you to use and modify it freely. If you have improvements or additional features you'd like to see, feel free to modify the script as needed.
