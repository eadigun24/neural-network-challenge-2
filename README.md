# neural-network-challenge-2

## Challenge Notes
* This challenge was designed based on the module challenge details in bootcampspot.
* The Jupyter Notebook was edited via Google Colab.

* Moved the step to encode the "OverTime" column to just before the [train_test_split] function call. This was done to simplify the code and logic flow.

* Preprocessing the data after the [train_test_split] function was / is new and a bit confusing:
    - Therefore, since we are encoding the data after the [train_test_split] operation; there wasn't a need to concat the resulting series back into the source dataframe.

* Noticed that the loss values do not seem to be present / generated when executes in google colab.