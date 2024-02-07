Custom Bash Prompt Configuration

This repository contains a customized .bashrc file with a colorful and visually appealing Bash prompt configuration. 
The configuration includes color customization for the prompt, setting a custom title for the terminal window/tab, 
and some explanatory comments for clarity.

Color Configuration
The color configuration defines ANSI escape sequences for various colors used in the Bash prompt:

COLOR_RESET: Resets the text color to the default.
COLOR_BOLD: Sets the text to bold.
COLOR_BLUE: Sets the text color to blue.
COLOR_PURPLE: Sets the text color to purple.
COLOR_PINK: Sets the text color to pink with bold formatting.
COLOR_GREEN: Sets the text color to green.
Customized Bash Prompt
The Bash prompt (PS1) is customized using the defined color variables to display the username, hostname, and current 
working directory in different colors:

PS1="${COLOR_BOLD}${COLOR_BLUE}\u${COLOR_RESET}@${COLOR_PINK}\h${COLOR_RESET}:${COLOR_GREEN}\w${COLOR_RESET}\$ "

\u: Inserts the username.
\h: Inserts the hostname.
\w: Inserts the current working directory.
${COLOR_BOLD}, ${COLOR_RESET}, ${COLOR_BLUE}, ${COLOR_PINK}, ${COLOR_GREEN}: Color formatting.

Usage
Save the changes and source the .bashrc file (source ~/.bashrc) to apply the modifications to your current Bash session.
