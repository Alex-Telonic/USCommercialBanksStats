This repository contains python code that generates statistical output from balance sheet data of U.S. commercial banks. Feel free to use the output...

To get started:

1. Clone repository
2. Download data from http://pages.stern.nyu.edu/~pschnabl/research/callreports_final.zip
3. Move stata file callreports_final.dta into same folder where repository resides.
4. Run notebook of interest

The output files are saved under the path LatexVorlage/graphs/... . The actual filepath depends on the path written in the code. In the code your output of interest should have something like plt.save({{path}}).  