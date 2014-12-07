ITESM-thesis-LaTex-Template
===========================

LaTeX thesis template for ITESM. In accordance to 2014 format. 

Contents of the template
============

Files: 

1. **thesis_template.txt:** LaTex main file
2. **thesis_template.pdf:** compiled example in PDF format

Folders:

1. **bibliography:** contains `references.bib`
2. **chapters:** contains `content` and `format` folders
    * content folder: files to modify in order to add content
        * `abstract.tex`
        * `acknowledgments.tex`
        * `background.tex`
        * `conclusions_future_work.tex`
        * `dedicatory.tex`
        * `discussion.tex`
        * `introduction.tex`
        * `materials_and_methods.tex`
        * `results.tex`
        * `vita.tex`
    * format folder: format related files (is not necessary to modify them)
        * `commitee.tex`
        * `cover.tex`
        * `declaration_authorship.tex`
3. **class:** contains `thesis.sty` LaTeX package (format parameters, etc)
4. **images:** contains specific folders to add images
    * `background`
    * `format`
    * `introduction`
    * `materials_and_methods`
    * `results`


Define author variables
============

**File: thesis_template.tex**

1. **authorName:** set the author's name (First Middle ­Last ­Name)
    * *Default: Arthur Philip Dent*
2. **schoolProgram:** set the author's school program 
    * *Default: Master of Science in Intelligent Systems*
3. **thesisTitle:** set thesis title
    * *Default: APPLICATION OF EVOLUTIONARY ALGORITHMS 
                TO SOLVE THE INFINITE MONKEY THEOREM*
4. **schoolName:** set the author's school program 
    * *Default: Instituto Tecnológico y de Estudios Superiores de Monterrey*
5. **schoolCampus:** set campus
    * *Default: Campus Monterrey*
6. **schoolDepartment:** set department
    * *Default: School of Engineering and Sciences*
7. **schoolPlace:** set campus location
    * *Default: Monterrey, N.L.*
8. **thesisDate:** set month and year 
    * *Default: December, 2014*
9. **thesisYear:** set year 
    * *Default: 2014*

Define committee variables
============

**File: thesis_template.tex**

You can set for each committee member the following:

1. **advisorName:** set the advisor's name (First Middle ­Last ­Name)
2. **advisorSchoolName:** set advisor's school or institute
3. **advisorSchoolDepartment:** set advisor's department 
4. **advisorSchoolPlace:** set advisor's school or institute location 

Compile document
============

In a terminal and inside file path, type:

~~~
pdflatex thesis_template.tex
bibtex thesis_template.tex
pdflatex thesis_template.tex
pdflatex thesis_template.tex
~~~





