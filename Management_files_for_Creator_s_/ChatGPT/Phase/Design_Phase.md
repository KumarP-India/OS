# Design Phase

Parent: [__Phase__](../../Phase.md)



## Defining the Backgroud for OS Development

> Intial Development is done in Nvidia Jetson Nano 2GB Development Kit (India)

> Although Jetson nano has reached EOL, we are using because it was already owned by us. And as we will progress we will enetually have to use more powerfull resources.

1. What specific ARM processor architecture will be targeted? (e.g., ARMv7, ARMv8)

- I've chosen Jetson Nano 2GB Development Kit for development in the initial development phases.
- Thefore answer is the ARMv8 architecture, which is the one used in the Jetson Nano.
- This architecture is known for its support of 64-bit processing and improved memory management, among other features.


2. What is the target device for the operating system (e.g., laptop, tablet, smartphone)?

- The answer is laptops, desktop PCs, and tablets.
- Laptop will be ideal users and Desktop will be second.


3. What are the minimum and recommended hardware specifications for the device?

- Currently, there are no specific hardware requirements, but it can be assumed that the operating system will need to support the hardware specifications of the Jetson Nano, as well as other devices that we plan to target.


4. What are the system requirements for the operating system (e.g., memory, storage, display resolution)?

- As explained in Q3. This is currently unknown.


5. What input/output devices will the operating system support (e.g., keyboard, touch screen, microphone)?

- The operating system will likely support a wide range of input/output devices, including keyboards, touchscreens, and microphones.

- It's important to ensure that the operating system is compatible with as many devices as possible to provide a good user experience.



6. Will the operating system support hardware acceleration for graphics, video, or other functions?

- The answer is yes, hardware acceleration will be supported.


7. Will the operating system be optimized for power efficiency, performance, or a balance of both?

- The answer is a balance of both, with the potential for user-selectable modes in the future.


8. Will the operating system support virtualization or containerization for running multiple operating systems or applications simultaneously?

- In short he answer is yes, virtualization will be supported.

- It will be implemented at core maximumizing the efficiency & performance of Virtualization.


9. What programming languages and tools will be used for the operating system development?

- This is currently undecided.


10. What is the target user demographic for the operating system, and what features or capabilities are important to them?

- The operating system is being developed for a wide range of users, and a startup form will be created so that users can select what matters most to them, with the goal of providing an OS optimized for their needs.



## Footnote

- This file may have been edited and contains text from ChatGPT and other AI, if not whole document.

### License


    This Readme file contains essential information about the Design Phase defined in Phase.md.
    Copyright (C) 2023  Prabhas Kumar <work.kumar.prabhas@gmail.com>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.
    
    To contact Prabhas Kumar, please email work.kumar.prabhas@gmail.com or message +91 76674 47235 via SMS, iMessage or/and WhatsApp.
