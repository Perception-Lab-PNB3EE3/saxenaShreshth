# JsPsych 2 assignment

The solutions demonstrates two ways to modify the stimulus in myNewExperiment. 

- **Solution 1** [myNewExperiment_imgEdit.html](myNewExperiment_imgEdit.html) shows how we can modify the stimulus images using any common image editor and use the new images in our experiment.
- **Solution 2 (Recommended)** [myNewExperiment_stimWidth.html]myNewExperiment_stimWidth.html) uses the ***stimulus_width*** parameter from the ***image-keyboard-response*** Jspsych plugin to modify the stimulus presentation.

There are always multiple ways to solve a single problem when you're programming. From the two solutions we upload here, we recommend following the more sophisticated **Solution 2** where we use a pre-existing Jspsych parameter (stimulus_width) to manipulate the stimulus instead of generating a new image file for each manipulation.  





## General Feedback on your submissions

### Completeness

- Make sure you include all files and folders (including images that you used)
- Use the naming conventions that we talked about in class (i.e., `camelCase.html`)
- Jspsych should be imported in your code from the downloaded local copy.

### Reproducibility

- A common error was the stimulus size manipulations. It should be changed only for the orange circle and the change is should persist in all trials.
- Another common error was in the filtering of blue and orange stimulus reaction times for the debrief block. 

### Documentation

- Changes made to the code should be commented. 
- Remember to also change your instructions for the experiment if you change the experiment stimulus!
- Take note of comment styles in `.html` files
  - `.html` comments: `<!--- comment --->`
  - JavaScript comments: either `/* comment */` for multi line or `// comment` for single line
  - Only use javascript comments inside the `<script> ... </script>` tags in a `.html` file
- Formatting of the README.md:
  - Use `#` for headings only (do not use `#` for the text under headings)
  - Be descriptive and welcoming such that a naive visitor can understand and contribute to your code.
