# Task-Optimizer
This script is designed to optimize system performance by prioritizing tasks, adjusting CPU affinity, and setting real-time priorities for critical processes. It begins by defining functions to change various parameters such as CPU affinity, process priorities, and IRQ affinities. 

The main optimization function applies these settings to specific tasks and threads, ensuring that critical tasks run on performance cores while less important tasks are relegated to power-saving cores. Additionally, it adjusts priorities for system services, graphics rendering, touch input handling, and more.

The script is initiated triggering the optimization process, which is indicated by notifications at the beginning and end. Overall, it aims to enhance system responsiveness and efficiency by fine-tuning resource allocation and task scheduling.
