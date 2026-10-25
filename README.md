# PsychoPy-SPR-Template
This is a template for creating moving window self-paced reading experiments in PsychoPy. 

# Motivation
As I began experimental work in psycholinguistics, I was frustrated by the lack of plug-and-play templates for commonly used paradigms in sentence processing that fit my needs. As a result, I'm making this template available with some no-nonsense instructions to get an experiment up and running.

# How to Use
To use this template, you must have PsychoPy installed. 
- **Built on PsychoPy version:** 2026.2.4
- **Download PsychoPy:** [https://www.psychopy.org/download.html](https://www.psychopy.org/download.html)

## Step-by-Step Instructions
1. **Download the Repo**  
Click the green "Code" button and select download ZIP, or clone the repo using Git.
2. **Open the File**  
Open PsychoPy Builder. Go to `File > Open` and select `spr_template.psyexp`.
3. **Customize the Conditions**  
To change the items, open the stimuli files (`/stimuli`) and change them. If you change the column names, you will have to update them in the experiment file.   
If you decide to add columns, like *wordlength* or *surprisal value*, this will not cause any issues running the experiment. The associated values will show up in the data file after running it.
4. **Test 'er Out**  
Click the green Run button to test out your experiment locally.

## Data Output
PsychoPy will generate a `data/` folder in the same directory as the experiment file. Each time you run a participant, PsychoPy generates three files: `.csv`, `.log`, and `.psydat`. For running analyses with the statistical software of your choice, you really only care about the `.csv` file. 

PsychoPy, by default, records a ton of information in the `.csv` data file. I have provided an R file template that combines all participant data files and strips unnecessary data.

## Notes
Sample stimuli in this template come from Frinsel and Christiansen (2024).

## How to Cite
If you use or adapt this template for your research, please cite it to support my work.

**APA Format:**
Pope, D. (2026). *PsychoPy-SPR-Template* (Version 1.0.0) [Computer software]. GitHub. https://github.com/decpo/psychopy-spr-template
