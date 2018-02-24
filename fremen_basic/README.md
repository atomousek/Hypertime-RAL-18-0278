### Section 5A of RAL-18-0278

To re-run the experiments described in Section 5A, first go to the src and type *make* to compile the predictive framework.
Then, go to the eval_scripts and type *make* to compile the t-test utility.

Then, type:

*./process_dataset.sh greg_door_2016_min* 

if it runs well, type

*./summarise_results.sh greg_door_2016_min* 

and then check the summary.png file, which should look similarly to Fig 2.
