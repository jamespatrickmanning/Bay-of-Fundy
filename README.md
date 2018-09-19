# Bay-of-Fundy
These are notes on the BoF manuscript to be editted by JiM, Huimin, and Xiaojian via "pull request".

These notes are organized according to Figures.  The plan is to finish this manuscript by a certain date
and then work on each figure one at a time.  We want to recreate all figures and the input files that
are needed for those figures.  The plan is for Xiaojian to spend time to find the programs he used, share them on Github, and Huimin will put htme in the "branches" where they belong, and then JiM will do the rest (modify, pull request, document, and create new figures).

Note: One option is for Xiaojian to make a large zip files of his laptop directories and send it to JiM.

Note: JiM will maintain the most up-to-date version of the manuscript on googledoc, export it occasionally to a doc file on his "notes" github branch, notify X & H when he does so.

Note: JiM will probably need acces to ALL the ROMS output files that are currently stored on /home/bling/xj/roms_xin where "xin" means "new" in Chinese.


     Fig 3
        needs better documentation within the code
        needs better README file
        needs explanation of where the following input files come from:
            k.npy
            latmm1.npy
            lonmm1.npy
    Fig 4
        JiM did a "pull-request" for Huimin to consider after he cleaned up the code considerably
            he found more than 50% of the code was not needed. Many import statements and even functions appeared more than once.
        needs explanation of where the following input files come from:
            binned_drifter12078.npz (what set of programs created this binned drifter field?)
            binned_model12078.npz  (apparently FVCOM's estimate)
            current_04hind_hourly.nc (is this just April field)
