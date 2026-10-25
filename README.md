# pulmonary_stenosis


data, statistical reports and markdown files for hair cortisol paper

This GitHub contains the following:

data file. contains the data supporting the pulmoic stenosis project.

R Markdown files. .rmd files for final models and senstivitiy analyses

HTML files showing statisical reports from all models.

There are now two data files... one file (pulmonic_stenosis_data.xlsx) has a single row per dog... used for all survival analyses except those involving treatments.  The latter used the second version of the data (pulmonic_stenosis_data_it_bias.xlsx)... which included different periods for pre-treatment and post-treatment as relevant.

All of the statistics files and htmls and files have also been updated.  This was required to address the comments of reviewers.  In particular, there was a need to revise statistical analyses for treatment variables... to address the possible impact of immortal time bias.  Please see the it_bias files for details of these models.

Finally, please note that it was not possible to include an HTML file for pulmonic_stenosis_cox (neutral prior models) because it was >25 MB.  Zipping the file did not work.  A copy of this file can be sent separately if required.
