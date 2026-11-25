---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

In this SoC Project, with help from labs and lectures we developed and displayed custom graphics on a 640x480 display

I am adding a test sentence here at 14:55 on 21/10/26.

## **Template VGA Design**
### **Project Set-Up**
Each Student was given a template folder that included the Basys3_Master constraints file, and testbench, ColourStripes VGA synch and VGA top files. Using the template ColourStripes file, students could edit the code to include static or dynamic images. To test this, the Testbench file simulates the inputs and outputs and tests them before sending the data to the FPGA, the VGA Sync file handles the timing of the image to the screen, and the ColourStripes file handles the design of what is displayed to the screen.

<img width="865" height="660" alt="Screenshot 2026-11-18 154250" src="https://github.com/user-attachments/assets/5535c337-37ea-4286-a66b-bf0a3314e721" />


### **Template Code**
We were given a stripes and colour cycle source code file with a VGA Top and TestBench file that showed colours of black, blue, green, cyan, red, purple, yellow and white. The VGA interface changes the digital image data with an analogue voltage system. 
### **Simulation**
To simulate the project, we're using vivado, which drives the module inputs using a TestBench file.
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).
### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
First I tested the board with a black and white striped screen

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
