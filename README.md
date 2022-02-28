# Automatic Speech Recognition 2021/2022 Labs Code

This repository contains the code for the labs of Automatic Speech Recognition course in academic year 2021/22.

Here are some explanations about the files in this repo.

* `asr_lab1.ipynb` is a notebook containing the exercises for Lab 1
* `asr_lab1_solutions.ipynb` is a notebook containing the solutions for Lab 1
* `introduction.pdf` gives a refresher on representing HMMs in WFST form (covered in Lecture 5)
* `helper_functions.py` contains two functions, `parse_lexicon()` and `generate_symbol_tables()`
* `lexicon.txt` is a lexicon used in all labs
* `lab1_template.py` is the submission template for lab1.

* `asr_lab2.ipynb` is a notebook containing the exercises for Lab 2
* `asr_lab2_solutions.ipynb` is a notebook containing the solutions for Lab 2

* `asr_lab3_4.ipynb` is a notebook containing the exercises for Lab 3 and Lab4.
* `asr_lab3_solutions.ipynb` is a notebook containing the solutions for Lab 3
* `asr_lab3_4_solutions.ipynb` is a notebook containing the solutions for Lab 3 and Lab 4
* `observation_model.py` is the python file containing the observation_model that you need in Lab3.
* `phonelist.txt` is the phone list in our `observation_model.py`. For instance, there is a phone `aa` in `phonelist.txt`, so `"aa_1"` is a valid `hmm_label` when calling `my_om.log_observation_probability(hmm_label, t)`.

* `asr_lab5.ipynb` is a notebook containing the exercises for Lab 5

For setup instructions, view the [Piazza post](https://piazza.com/class/ky4bimyglss6tm?cid=10)
