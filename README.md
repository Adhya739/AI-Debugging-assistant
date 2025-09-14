Python AI Debugging Assistant
This repository contains a Python-based AI Debugging Assistant designed to help students debug their Python code effectively. The assistant analyzes buggy code, highlights potential issues, and provides constructive hints without giving away the correct solutions. It aims to develop students' debugging skills and deepen their understanding of Python programming concepts.

Features
Analyzes Python code for common bugs and logical errors.

Highlights problem areas such as data types, variable scope, indentation, and function usage.

Explains the conceptual reasons behind errors and unexpected behaviors.

Guides students with probing questions to encourage critical thinking.

Suggests practical debugging strategies like print statements, reading error messages, and using debuggers.

Avoids providing the exact solution to promote learning and self-sufficiency.

Design Choices
Why the Prompt Was Worded This Way
The prompt is crafted to make the AI a debugging tutor, not just a fixer. It specifically guides the AI to:

Point out likely problem areas in the student's code.

Explain why these issues cause errors conceptually.

Encourage students to think critically through guided questions.

Suggest debugging methods without rewriting code or giving direct fixes.

This wording ensures the AI supports learners in understanding the source of their bugs and building durable debugging skills, rather than simply handing out answers that might hinder learning.

How It Avoids Giving the Solution
The prompt explicitly instructs the AI not to provide corrected code or direct solutions. Instead, it directs the AI to offer hints, conceptual explanations, and strategic guidance. This approach keeps students engaged in active problem-solving and prevents dependency on shortcuts.

How It Encourages Helpful, Student-Friendly Feedback
By emphasizing guiding questions, explanations, and debugging strategies, the prompt fosters a positive, encouraging tone that motivates learners. It also helps the AI adapt feedback to different skill levels, providing more detailed explanations for beginners and concise, reflective prompts for advanced users. The focus on teaching reasoning and exploration results in a supportive, educational interaction.

How the Assistant Supports Different Learners
Beginners receive detailed conceptual explanations, step-by-step debugging advice, and patient guidance.

Advanced learners get concise insights, prompts to reason at a higher level, and suggestions for advanced debugging tools.

This adaptability helps learners improve regardless of experience, building confidence and troubleshooting skills.

Usage
Clone the repository

Run the AI debugging assistant script .

Provide buggy Python code as input and receive guided debugging feedback.

License
