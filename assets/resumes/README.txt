HOW TO MAKE THE RESUME DOWNLOADS WORK
=====================================

Put 4 PDFs in THIS FOLDER (assets/resumes/), renamed EXACTLY as below.
The names must match character-for-character: capital letters, underscores,
and the ".pdf" ending. No spaces.

  Button on the website     ->  Filename you must use in this folder
  ------------------------      -----------------------------------------
  "AI / ML & Engineering"   ->  Vireen_AI_ML_Resume.pdf
  "Data Analyst"            ->  Vireen_Data_Analyst_Resume.pdf
  "Business Analyst"        ->  Vireen_Business_Analyst_Resume.pdf
  "Robotics"                ->  Vireen_Robotics_Resume.pdf


WHICH OF YOUR FILES GOES WHERE
------------------------------
  Your file "Vireen Chowdary Vesangi.pdf"      (Applied ML / Data Eng / Full-Stack)
      rename to ->  Vireen_AI_ML_Resume.pdf

  Your file "Vireen_Data_Analyst_Resume.pdf"
      rename to ->  Vireen_Data_Analyst_Resume.pdf     (already correct - just copy it in)

  Your file "Vireen_Business_Analyst_Resume.pdf"
      rename to ->  Vireen_Business_Analyst_Resume.pdf (already correct - just copy it in)

  Your robotics resume (whatever it's currently called)
      rename to ->  Vireen_Robotics_Resume.pdf

Note: the old "General" button was removed and replaced with "Robotics",
so you do NOT need Vireen_General_Resume.pdf anymore.


STEPS
-----
1. Copy the 4 PDFs into this folder.
2. Rename each one to match the table above exactly.
3. In GitHub Desktop, you'll see the 4 new files appear as changes.
4. Write a summary like "add resume PDFs", click "Commit to main", then "Push origin".
5. Wait ~1 minute, then reload https://vireen555.github.io and test the buttons.


TROUBLESHOOTING
---------------
Button gives a "404 / Not Found" page  ->  the filename doesn't match exactly.
   Check for: a capital letter that should be lowercase (or vice versa),
   a space instead of an underscore, or a double extension like ".pdf.pdf"
   (Windows hides extensions by default - turn on View > File name extensions
   in File Explorer so you can see the real name).

Want different buttons or labels? Edit the `downloads` array in index.html,
inside the "resume" section of CONFIG.
