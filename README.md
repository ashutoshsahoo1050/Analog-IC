# Analog-IC
# Course Information

1. **Analog Integrated Circuits (Analog IC) is a course focused on transistor-level design and analysis of circuits in modern electronics.**
2. **Learnt About MEMS MIC Using Analog2Discover with waveform applications.**
3. **It covers MOS and BJT device modeling, helping you understand how transistors operate in integrated circuits.**
4. **You will study single-stage and multi-stage amplifiers, current mirrors, and differential pairs as key building blocks.**
5. **The course explains operational amplifiers (Op-Amps), voltage/current references, and output stage design.**
6. **Frequency response, feedback, stability, and compensation in analog circuits are analyzed in detail.**
7. **Practical sessions involve using CAD tools for simulation and verification of circuit performance.**
8. **Noise, nonlinearity, and mismatch in analog IC design are also discussed to improve real-world circuit robustness.**
9. **By the end, you will be able to design, simulate, and analyze small to medium-scale analog and mixed-signal ICs.**
 
-  **COURSE OUTCOME**:
   - Design of Analog ICs in the context of electronic system design
   - Deriving IC specifications from the host electronic system.
   - A good understanding of CMOS devices & technology.
   - Proficiency in analog circuit design and analysis.
   - Mastery of design tools: ngspice, xscheme, magic & Python.

- **COURSE DETAILS**
  - **Introduction to an electronic system design, a plug-n-play USB-MIDI microphone.**
    - Microphone pre-amplifier and interface circuit design.
    - Select an widely available Op-Amp for the preamplifier e.g. TI OPA 344
    - Derive the important specs for the CMOS Op-Amp design.
  - **Introduction to linear circuits and passive devices**
    - Understanding passive devices (RLC) using basic EM principles.
    - Principle of linearity and superposition
    - Network analysis: KCL, KVL, node theorems, Thevenin, Norton
    - Emphasis on interfacing circuits and power transfer principle.
  - **Basics of MOS device physics**
    - Introduction to pn junctions.
    - MOS as capacitor.
    - Threshold voltage.
    - IV characteristics.
    - Parasitic capacitance.
  - **Basics of analog building blocks**
    - Current mirror design: simple, cascode and wide-swing mirrors
    - Basic understanding of differential amplifiers.
    - Introduction to AC analysis: stability analysis of a 2-stage amplifier.
    - Design of a folded cascode amplifier using CMOS 130nm.
  - **Implementation of the design**
    - All the designs will be done using Skywater 130nm CMOS technology.
    - Schematic capture using open-source _xschem_.
    - Simulation will be done using _ngspice_.
    - Layout and final verification will be done using _magic_ and _netgen_.
  - **Design, test and characterization of a USB-MIDI microphone.**
    - System design and simulation using  with ngspice (or. LTSpice).
    - PCB design with Eagle.
    - Reference schematic & PCB will be provided to expedite it.
    - Test & characterization using Python libraries numpy, scipy and matplotlib.
# Summer Internship Program on Analog IC Design  
*A Student’s Journey & Resource Hub*

***

## 👋 Welcome!

Hello and welcome!  
If you’re curious about what it’s like to dive into analog IC design—or just looking for some solid, hands-on resources—you’ve landed in the right place. I’m a B.Tech student who recently completed the **Summer Internship Program on Analog Integrated Circuit (IC) Design**, and this repo is both my portfolio and a guide for anyone following in my footsteps.

***

## 🌱 Why I Signed Up

I wanted something more than just lectures and theory—I was itching to actually design real circuits, learn industry tools that professionals use, and discover how an abstract MOSFET drawing becomes a working microchip. A USB-MIDI microphone front-end as a project? Count me in!

***

## 🚀 What I Learned (and What You Can Too!)

### Things That Just “Clicked”

- **CMOS Device Physics:** Not just a chapter—it's the magic behind every transistor!
- **Designing Key Building Blocks:** Built current mirrors, differential amps, and cascodes by hand.
- **EDA Tools (Open-Source!):**  
  - **ngspice:** for circuit simulations.
  - **xschem:** for making my schematics “come alive.”
  - **magic:** making layouts that actually get fabricated.
  - **KICAD:** won me over for PCB design.
  - **Python (numpy, scipy, matplotlib):** because real engineers aren’t afraid of data.

- **“Big Picture” System Design:** Got to see all these blocks power a real-world application—USB-MIDI mic front-end—for the first time.

***

## 📅 How the Program Rolled Out

- **Duration:** 3 weeks, ~100 hours (it flies by!)
- **Setup:** Split between morning theory, afternoon labs, and a final project sprint.
- **Batch:** Just 25 of us—plenty of peer learning and one-on-one help.

### Week-at-a-Glance

| Week | We Explored... |
|------|----------------|
| 1    | Linear circuits, resistors/caps/coils, intro to MOSFETs, running basic simulations |
| 2    | MOS physics deep-dive, advanced simulation, building analog “lego blocks” |
| 3    | Full-chip design in Skywater 130nm, layout in magic, PCB builds, testing—plus demo day! |

***

## 🎯 My Personal Project

My main focus? Designing the full analog front-end for a **USB-MIDI microphone**. The journey:

- Drawing schematics in xschem (it was intimidating at first!).
- Running endless simulations in ngspice (coffee required).
- Laying out everything in magic, pixel by pixel.
- Prepping for real-world fabrication thanks to the TinyTapeout platform.

If you want to peek at all the files—simulations, code, even my final report—it’s all in `/projects`.

***

## 🗂️ Your Guide to the Repo

- `/materials` – All my lecture notes, slides, and handpicked references.
- `/labs` – Lab handouts, simulation files, and my own handwritten solution attempts.
- `/projects` – My mic front-end project and some great examples from friends.
- `/setup` – Straightforward steps to install and configure all those open-source EDA tools.

***

## ✨ What Made This Special

- **Everything was hands-on:** We didn’t just read; we designed, we built, we tested.
- **True open-source:** You can do all of this at home—no licenses, just learning.
- **Inspiring mentors:** Experts from Synopsys and professors who actually cared.
- **Peer power:** I learned as much from my batchmates as my instructors.

***

## 📝 Some Advice from Someone Who’s Been There

- **Ask questions—always.** The only dumb question is the one you don’t ask.
- **Simulate everything.** Try breaking stuff! You’ll learn more fixing it.
- **Document your process.** Seriously—future-you will thank you.
- **Take creative detours.** Once you finish a lab, tweak the circuit and see what happens.

***

## 👏 Thank Yous

Deep gratitude to **Dr. Saroj Rout**, **Prasant Swain**, and **Mrinal Das**—not just for the technical guidance, but for all the encouragement. You made the program what it was!

***

## 📄 License

All materials are for learning and sharing only—please credit anyone whose work you use or remix.

***

**Happy building, and don’t be shy—fork this repo, raise issues, or add your own contributions! Analog IC design is meant to be explored together.**
