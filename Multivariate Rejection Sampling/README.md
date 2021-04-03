[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Projeto-Jupiter/RocketPaper/blob/main/MRS/multivariate_rejection_sampling_example.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Projeto-Jupiter/RocketPaper/main?filepath=MRS%2Fmultivariate_rejection_sampling_example.ipynb)


## MRS - Multivariate Rejection Sampling

MRS is an algorithm which can be used to study results from Monte Carlo analyses with more flexibility.
MRS facilitates the calculation of results of a Monte Carlos analysis subjected to new inputs without having to rerun the entire analysis.
If an analysis has already been completed, MRS can filter the inputs and outputs of the run to present what would the results be considering the new inputs.
The main benefit of MRS is being able to get new Monte Carlo results in a fraction of a second, compared to hours or days necessary to run a typical analysis. This can save a lot of time.


### Files description:

- README.md : 

      Markdown file describing the contents in the present folder.

- MRS_results_v1.pdf :

      Resulting PDF image of an MRS calculation.
      
- multivariate_rejection_sampling_example.ipynb : 

      Jupyter notebook used for the MRS calculation example.
      The badge "Open in Colab" is recommended to run this file.

- all_members_mrs_test/, all_members_orginal/, ensemble_member_4_mrs_test/, ensemble_member_4_original/, ensemble_member_comparison/ :

      Monte Carlos Analysis inputs and outputs for the Valetudo rocket. This is used by the MRS example.