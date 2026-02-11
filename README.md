# MATLAB Minidrone Competition - Reference Model

This repository contains the reference model for the MathWorks Minidrone Competition. This competition challenges participants to develop innovative algorithms for controlling a Parrot Mambo Minidrone using MATLAB and Simulink. The reference model provides a starting point for participants to build upon and test their own control strategies.
One common problem statement involved developing a line-following algorithm.

## Demonstration


## Table of Contents

1.  [Demonstration](#demonstration)
2.  [How to Use This Repository with MATLAB](#how-to-use-this-repository-with-matlab)
3.  [MATLAB Minidrone Competition Overview](#matlab-minidrone-competition-overview)
4.  [How to Open this File on MATLAB](#how-to-open-this-file-on-matlab)
5.  [Further Information](#further-information)


A demonstration of the final implementation is shown below.

<video src="https://github.com/lakhmanisahil/MATLAB_Minidrone_Competition/blob/main/media/final.mp4" controls title="A brief demonstration of the project">
  Your browser does not support the video tag.
</video>

## How to Use This Repository with MATLAB

This repository includes a MATLAB project file (`.mlproj`) and a zipped solution (`.zip`) to help you get started quickly. Follow these steps to use the code:

1.  **Open the MATLAB Project:** Double-click the `.mlproj` file located in the `solution/` folder. This will open the project in MATLAB and automatically set up the necessary paths and dependencies.
2.  **Import the Zipped Solution (if needed):** If you prefer to start with the zipped solution, extract the contents of the `.zip` file located in the `solution/` folder to a directory of your choice. Then, open the corresponding project file.
3.  **Explore the Model:** The Simulink model is the core of this project. Open and explore the model to understand the control algorithm and how it interacts with the Parrot Mambo Minidrone.
4.  **Run the Simulation:** Simulate the model in Simulink to test the control algorithm in a virtual environment.
5.  **Deploy to Hardware:** Using the Simulink Support Package for Parrot Minidrones, you can directly deploy the algorithm to the Parrot Mambo hardware and test it in the real world.

## Further Information
To participate in the MATLAB Minidrone Competition, you'll typically need to:

*   Develop a line-following algorithm using MATLAB and Simulink.
*   Utilize the Simulink Support Package for Parrot Minidrones.
*   Design your algorithm within the provided 'flightControlSystem' model.
*   Ensure your model is code generation capable.

## MATLAB Minidrone Competition Overview

The MathWorks Minidrone Competition introduces participants to Model-Based Design using Simulink. It offers an opportunity to gain expertise in developing an autonomous line-following algorithm for a quadcopter, utilizing the relevant MATLAB & Simulink toolboxes. The competition is conducted in two formats: In-Person and Virtual, both consisting of two rounds.

*   Round 1: Simulation Round - Design a Minidrone line follower algorithm.
*   Round 2: Format-Specific
    *   In-Person: Hardware Deployment Round - Deploy the Simulink model onto a Parrot Mambo Minidrone.
    *   Virtual: Video Presentation Round - Submit a video explaining your approach.

## How to Open this File on MATLAB

For detailed instructions, rules, and resources related to the MATLAB Minidrone Competition, please visit the [MATLAB Minidrone Competition](https://www.mathworks.com/academia/student-competitions/minidrone.html) website.
To access the competition starting point model, participants must install the ‘Simulink support package for parrot minidrones’ and run the command `parrotMinidroneCompetitionStart`. This opens a new project, where participants should develop their algorithm inside the ‘flightControlSystem’ model. For more details on accessing the model, please watch the Minidrone video series.

## Team Members

*   Sahil Lakhmani (Team Leader): [LinkedIn](https://www.linkedin.com/in/lakhmani-sahil/)
*   Aryan Gupta: [LinkedIn](https://www.linkedin.com/in/aryan-gupta-4bb02b25b/)
