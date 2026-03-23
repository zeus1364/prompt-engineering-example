# prompt-engineering-example
A structured prompt‑engineering case study demonstrating prompt refinement, reasoning control, and safe output design.


Prompt Engineering Example — Wi‑Fi Adapter Components, Resetting, and Security
Overview
This example demonstrates how I refine prompts to improve clarity, structure, and safety in AI‑generated responses.

The goal was to guide the model to produce a clear, accurate explanation of Wi‑Fi adapter components,
 safe reset procedures, and both physical and software‑level security practices.


1. Initial Prompt
Code
Explain the common components of a Wi‑Fi adapter, how to reset the adapter, and how to position it correctly to minimize physical security breaches and reduce the risk of software‑based security vulnerabilities.
Issues Identified
Output was vague and incomplete


No structure or formatting

No distinction between soft reset vs. factory reset

Weak physical‑security guidance

Generic or irrelevant software‑security advice

No clear audience or tone

The model responded with shallow, generic information because the prompt lacked structure and constraints.


2. Refined Prompt
Code
Explain the common components of a Wi‑Fi adapter, how to safely reset it, and how to position it to reduce physical tampering. 
Also include general software‑level practices that reduce security risks. 
Use clear section headings, short bullet points, and simple language suitable for non‑technical users.
Avoid brand‑specific advice.

Why This Prompt Is Better
Defines the audience (non‑technical users)

Specifies formatting (headings + bullet points)

Clarifies the scope (components, reset, physical security, software security)

Prevents vague or unsafe advice

Produces predictable, structured output

3. Improved Model Output
Common Components of a Wi‑Fi Adapter
Antenna: Sends and receives wireless signals.


Radio chip: Handles communication with the router.

Controller/processor: Manages data between the computer and the network.

Firmware: Low‑level software that controls the adapter’s behavior.

Driver: Software that lets the operating system communicate with the adapter.

USB or PCIe interface: The physical connection to your computer.

How to Safely Reset a Wi‑Fi Adapter
Soft reset (recommended first)
Turn off Wi‑Fi on your computer.

Unplug the USB adapter or disable the PCIe adapter in system settings.

Wait 10–15 seconds.

Plug it back in or re‑enable it.

Driver reset
Open Device Manager (Windows) or Network Settings (macOS/Linux).

Disable the adapter.

Re‑enable it.

Factory reset (only if the adapter has a reset button)
Press and hold the reset button for 5–10 seconds.

Restores firmware defaults and may erase custom settings.

How to Position the Adapter to Reduce Physical Tampering
Keep the adapter within your line of sight.

Avoid placing it in public or shared spaces.

Use a short USB extension cable to position it behind a monitor or inside a desktop case.

Prefer internal PCIe adapters for desktops.

Avoid leaving USB adapters plugged into laptops in public areas.

Software Practices to Reduce Security Risks
Keep drivers and firmware updated from official sources.

Disable WPS on your router.

Use strong WPA2/WPA3 passwords.

Avoid unofficial drivers or “signal boosting” utilities.

Remove unused Wi‑Fi profiles.

Use your operating system’s built‑in firewall.

4. Why the Improved Prompt Works
The refined prompt:

forces structure and clarity

defines the audience

reduces ambiguity

prevents unsafe or overly technical advice

guides the model to produce a layered, practical answer

results in predictable, repeatable output

This demonstrates effective prompt engineering:
shaping the model’s reasoning through constraints, structure, and specificity.
