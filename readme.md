# Resume Template #

This will compile a latex resume with a template taken from [Seth Holloway's Blog](http://sethholloway.com/blog/2011/06/24/my-latex-resume-template/). 

Make changes to metadata.yml and run:

    $ rake

And you'll have a shiny new resume.pdf.

Within metadata.yml you can remove the first level entries if you
want to remove sections from the final output. 

Within each first level block, take care to keep the format of 
subentries the same, otherwise the script will break.

In order to use this you'll need ruby, rake, and LaTeX.

If you're on ubuntu or debian run:

    $ sudo apt-get install ruby rake texlive-full
