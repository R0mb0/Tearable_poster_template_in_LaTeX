# LaTeX template for a tear-off flyer suitable for any type of announcement

[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/74daa4fe605e4efe9ff2c339c65db976)](https://app.codacy.com/gh/R0mb0/Tearable_poster_template_in_LaTeX/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Compilation_Test](https://github.com/R0mb0/Tearable_poster_template_in_LaTeX/actions/workflows/Compilation_Test.yml/badge.svg)](https://github.com/R0mb0/Tearable_poster_template_in_LaTeX/actions/workflows/Compilation_Test.yml)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Sushi_Order_Sheet)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Sushi_Order_Sheet)
[![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

## Demo image

![Demo_Image](https://github.com/R0mb0/Tearable_poster_template_in_LaTeX/blob/main/ReadMe_Images/ReadMe_Image.png)

---

## How to create your personal tearable poster online for free!

1. Fork this repository by pressing the second button at the top right.
2. Rename the repository as you want and change the description then Fork it!
3. ⚠️ You have to activate "Actions" on your repo; go to "Actions", click on
 "I understand my workflows, go ahead and enable them" ⚠️
4. Personalize the document properties!
   1. Access "Tearable_poster" folder from main page and click on "Tearable_poster.tex".
   2. Now click on "Edit this file" (the pencil on top right).
   3. Follow the comments to personalize the document properties
    ```tex
      % ================================================================================
      % 									Parameters
      % ================================================================================
      
      % Number of tabs at the bottom of the page
      \newcommand{\numTabs}{12}
      
      % Page Width (A4 = 21cm)
      \newcommand{\pageWidth}{21}
      
      % Margins in cm (Left and Right)
      \newcommand{\marginLeft}{2}
      \newcommand{\marginRight}{2}
      
      % Bottom margin in cm (It matches the height of the tabs)
      \newcommand{\marginBottom}{2.5}
      
      % Vertical distance from the bottom of the tabs in cm
      \newcommand{\tabTextYOffset}{0.1}
      
      % Radius of the box corners in mm
      \newcommand{\boxarc}{6}
      
      %  Width of the box corners in pt
      \newcommand{\boxlinewidth}{3}
      
      % Main text of the Announce 
      \newcommand{\mainTitle}{Main Title}
      \newcommand{\mainDesc}{Main description}
      \newcommand{\mainDetails}{Main details}
      \newcommand{\mainContact}{Call: \underline{Phone number}}
      
      % Text on tabs
      \newcommand{\tabText}{Contact: Phone number}
      
      % ================================================================================
      % 								End	Parameters
      % ================================================================================
    ```
5. Now "Commit changes"!
6. Wait 2 minutes, got to "Actions" -> "Compile" -> click on the last one (look at
 the date on right) -> scroll down the page and click on "artifact file".  
7. Done! now you have your tearable poster :) .

---

## License

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
