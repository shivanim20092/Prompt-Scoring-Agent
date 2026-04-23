# Prompt-Scoring-Agent
Code from google colab
##Contents
-Agent logic
-Test result included for sample runs in the Text cells below the main code cells.
-Few more test results included below
##How to run
-Open the notebook in google colab.
-Run 2 code cells from top to bottom (to install packages and then the agent code)

**Test Results 3**:

**input**='Create a small bed time \nstory for kids age 8'
**Output** = 
*   **Clarity:** 9/10 - The prompt is very clear and easy to understand, with a straightforward goal.
*   **Specificity/Details:** 6/10 - "Small" and "bed time story" provide some direction, but more details on theme, characters, or plot elements would enhance the output.
*   **Context:** 8/10 - The target audience ("kids age 8") and the purpose ("bed time story") are clearly defined.
*   **Output format and constraints:** 6/10 - "Small" indicates length, and "bed time story" implies a gentle tone, but more precise constraints like word count or specific story elements are missing.
*   **Person defined:** 0/10 - No specific role or persona is assigned to the AI.

**Final Score:** 5.8/10

**Feedback:**
The prompt clearly states its main objective and target audience. However, it could benefit from more specific details to guide the story's content and structure, and it doesn't assign a persona for the AI to adopt.

**Improvement Suggestions:**
1.  **Add specific story elements:** Suggest a theme (e.g., friendship, bravery), a main character (e.g., a curious squirrel, a sleepy star), or a simple plot idea to make the story more unique.
2.  **Define length more precisely:** Instead of "small," specify a word count (e.g., "around 200 words") or a number of paragraphs.
3.  **Assign a persona:** Instruct the AI to "Act as a gentle children's author" or "Imagine you are a storyteller for young children" to influence the writing style and tone.

**Test Results 4** :
**Input** :  As a python code expert, help me with python problems on basic concepts, so that i can solve those
**Output** :
**Clarity:** 8/10
**Specificity/Details:** 3/10
**Context:** 5/10
**Output format and constraints:** 2/10
**Person defined:** 10/10

**Final Score:** 5.6/10

**Feedback:**
The prompt clearly defines the persona but is very general regarding the type of "python problems" and the nature of the "help" required. It lacks details on specific concepts, the user's current skill level, or the desired output format.

**Improvement Suggestions:**
1.  Specify the exact basic concepts you need help with (e.g., "loops and conditionals," "functions and data structures," "object-oriented programming basics").
2.  Clarify the type of help you're looking for (e.g., "provide practice problems," "explain concepts with code examples," "review my attempts," "give hints for specific challenges").
3.  Indicate the desired output format or length for the help (e.g., "list 3 problems with solutions," "explain each concept in a concise paragraph," "provide a single code snippet for each problem").

