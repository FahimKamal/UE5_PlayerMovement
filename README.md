# Modified Unreal Engine Animation Sample Project

This repository contains a modified version of the official Unreal Engine Animation Sample Project, now enhanced with the SuperGrid Starter Pack to serve as a comprehensive template for level design and third-person game prototyping. The original animation project provides over 500 AAA-quality animations and a fully functional character with animation Blueprints, designed to showcase Unreal Engine's Motion Matching toolset. [1]

<p align="center">
  <img src="https://github.com/user-attachments/assets/311e2035-9d58-4404-81b1-ea15140ef3d3" alt="Animation System Overview" width="800">
</p>
<p align="center">
  <em>Image: Overview of the animation system in action</em>
</p>

## Original Project Overview (Animation Sample)

The Game Animation Sample Project from Epic Games is a free resource for developers. [1] It's designed to help users create high-quality character locomotion and other gameplay animation systems. [1]

**Key features of the original animation project include:**

*   **Over 500 AAA-quality animations:** A vast database to supercharge development. [1]
*   **Fully functional character and animation Blueprint:** Ready to use and learn from. [1]
*   **Motion Matching Toolset:** Demonstrates the capabilities of Unreal Engine's latest animation technology. [1]
*   **Suitable for AAA and Indie Developers:** Offers a sandbox for AAA pre-production and plug-and-play locomotion for indie projects. [1]
*   **Compatibility:** Animations are compatible with all UE Mannequins and can be retargeted. [1]
*   **Multiple Motion Matching Databases:** Showcases best practices for organizing animation data. [1]
*   **Advanced Animation Techniques:** Utilizes Choosers, Proxy Tables, and Pose Warping to manage animation selection and coverage. [1]
*   **Authoring and Debugging Tools:** Includes tools like the Rewind Debugger. [1]

https://github.com/user-attachments/assets/a595da73-ab0a-44a3-a89b-d776d0bf9ee9

<p align="center">
  <em>Image: Motion Matching in Action</em>
</p>

### What is Motion Matching?

Motion Matching is a technique that continuously selects the best animation frame to play from a large database based on the character's current pose and predicted future movement. [1] This allows for highly realistic and seamless transitions, even for complex actions like jumping, falling, and parkour. [1] The system can scale with the size of your animation dataset and uses Pose Warping to fill in any gaps. [1]

## Purpose of this Fork/Modification

This modified version of the Animation Sample Project, now including the SuperGrid Starter Pack, serves as a streamlined and enhanced template, primarily for **level design prototyping and early game development**.
The core third-person character animations are invaluable for quickly implementing player movement and controls. The addition of SuperGrid assets further accelerates the level blockout process, allowing for immediate focus on level layout, design, and gameplay mechanics without needing to build these foundational systems or basic prototyping assets from scratch.

The project has been adjusted to be more lightweight (regarding character models) and modular, facilitating easy migration of the animation system and SuperGrid assets into new Unreal Engine projects.

## Modifications Made

Here's a summary of the key changes and additions implemented in this version:

*   **Reduced Project Size by Removing High-Definition Character Models:**
    *   Description: Several of the original high-definition character models and their associated assets have been removed from the animation sample base. This significantly reduces the overall project size, making it quicker to clone, open, and manage.

*   **Enhanced Modularity for Easy Migration:**
    *   Description: The project structure has been refactored to make the core animation system and integrated assets like SuperGrid more modular. This simplifies migrating the entire setup into new or existing Unreal Engine projects.

*   **Integrated SuperGrid Starter Pack for Enhanced Level Prototyping:**
    *   Description: The [SuperGrid Starter Pack](https://fab.com/s/6507a4292775) (a free asset pack) has been integrated into this project. It provides a versatile collection of materials and Blueprint assets specifically designed to accelerate level design and prototyping. This inclusion helps make blocking out and iterating on game environments much easier and more efficient.

*   **Preparation for Future Plugin Integration:**
    *   Description: The project is structured to readily accommodate additional plugins that may be vital for specific level design or gameplay prototyping needs. *(This section can be updated once you integrate new plugins.)*

## How to Use This Modified Project

1.  **Prerequisites:**
    *   Unreal Engine version 5.4
    *   [Any other specific plugins or software needed, if any at this stage]
2.  **Setup:**
    *   Clone this repository: `git clone https://github.com/FahimKamal/UE5_PlayerMovement.git`
    *   Open the `.uproject` file with the specified Unreal Engine version.
3.  **Key Areas to Explore:**
    *   **Animation System:** Review the core Animation Blueprints and Motion Matching databases (typically found in `Content/[YourAnimationSystemFolder]`) to understand the locomotion setup.
    *   **SuperGrid Assets:** Explore the SuperGrid assets (typically found in `Content/SuperGrid/`) for materials, meshes, and Blueprints useful for rapid level blockouts.
    *   The project is structured for easy migration of the animation system folder and the `SuperGrid` folder to your target project.

## Original Project Resources & Included Assets

*   **UE Animation Sample - Official Blog Post:** [Get over 500 free animations with the Game Animation Sample Project](https://www.unrealengine.com/en-US/blog/game-animation-sample) [1]
*   **SuperGrid Starter Pack:** [Link to Asset on Fab/Marketplace](https://fab.com/s/6507a4292775)
*   **Project Documentation (Animation Sample):** (The blog post mentions "project documentation". If you find a direct link on the Unreal Engine site, it would be great to add here). [1]

## Contributing

As this is a personal modification primarily for streamlining a level design template, contributions are not actively sought. However, feel free to fork and adapt it for your own purposes. For contributions to the original Unreal Engine project, please refer to Epic Games' official channels.

## License

The original Game Animation Sample Project is provided by Epic Games, Inc. and is subject to their licensing terms (typically the Unreal Engine EULA). The SuperGrid Starter Pack is subject to its own licensing terms as provided on its store page.

The modifications and custom structure of this repository are open source and released under the [MIT License](LICENSE). Please include a `LICENSE` file in your repository containing the full text of the MIT License. Ensure compliance with all relevant licenses for included assets.