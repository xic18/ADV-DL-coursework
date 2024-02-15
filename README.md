[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/N5cDDeBa)
# Assignment 1

## EECS E6691 2024 Spring

## Content

The assignment will require that you implement a simplified **Detection Transformer (DETR)** model in PyTorch.

**Before the add/drop DDL**, the assignment will be provided through a public Github repository. You may start working on the assignment in your **local environment** or [**Google Colab**](https://colab.research.google.com/).

**After the add/drop DDL**, the assignment will be provided again through **Github Classroom** and **GCP coupons** will be distributed. You will need to complete the assignment in GCP and submit your repository to Gradescope (can be navigated from Courseworks).

The goal is to:
- Introduce the principles and implementations of **Transformers** (slightly simplified).
- Introduce the training and evaluation of **Object Detection** models.
- Familiarize the usage of **PyTorch**.

The key references to study are:
- ***DETR Paper***: N. Carion, “End-to-End Object Detection with Transformers,” arXiv.org, May 26, 2020. https://arxiv.org/abs/2005.12872
- ***DETR Variants***: T. Shehzadi, “Object Detection with Transformers: A Review,” arXiv.org, Jun. 07, 2023. https://arxiv.org/abs/2306.04670.
- ***DETR Official Code Base***: https://github.com/facebookresearch/detr.

To be able to work on the assignment, you may be interested to know
- [How to use Github _effectively_](https://docs.github.com/en/get-started/quickstart/hello-world)
- [How to use Google Colab](https://colab.research.google.com/drive/16pBJQePbqkz3QFV54L4NIkOn1kwpuRrj)
- [How to setup local PyTorch environment](https://pytorch.org/get-started/locally/)
- [How to setup a VM instance on GCP](./GCPSetup.md) (Read GCPSetup.md in this repo)

## <span style="color:red">**TODO:**</span> Instructions

1. Complete All <span style="color:red">**TODO**</span> sections, fill in the blanks with your code and _briefly_ answer the questions (within 3-4 sentences).
2. Commit your changes regularly. <span style="color:red">***At least 3***</span> commits on your progress of the notebook is required before submitting a final version.
3. Without dramatically changing the notebook architecture, **feel free to make modifications outside of the TODO sections** as you explore what works best for you.

## <span style="color:red"><strong>TODO:</strong></span> (Re)naming of Repository

***INSTRUCTIONS*** for naming the student's repository for assignments (with one student):
* Students need to use the following name for the repository with their solutions: `e6691-2024spring-assign1-UNI` (the first part "e6691-2024spring-assign1" will be inherited from the assignment repository, so only UNI needs to be added)
* Initially, the system may give the repository a name which ends with a student's Github user ID. The student should change that name and replace it with the name requested above.
  * Good Example: `e6691-2024spring-assign1-zz9999`
  * Bad example: `e6691-2024spring-assign1-e6691-2024spring-assign1-zz9999`
* This can be done from the "Settings" on the repository webpage.

***INSTRUCTIONS*** for naming the students' solution repository for group assignments, such as the final project (students need to use a 4-letter groupID and the UNIs of all group members):
* Template: `e6691-2024spring-project-GroupID-UNI1-UNI2-UNI3`
* Example: `e6691-2024spring-project-MEME-zz9999-aa9999-aa0000`

## Submission

1. Make sure a working Jupyter Notebook is included in your repository. The notebook should be runnable with the provided image on GCP. **Please make direct edits to the provided notebook file instead of creating copies.**
2. Additionally, **export a PDF version** of your notebook and also include it in your repository.
3. **Make sure your changes are properly pushed to Github, including the exported PDF file.** Always open the repository webpage and check if you could see your modifications.
4. **Submit your repository to Gradescope** (can be found from Courseworks). Always open the "Codes" tab in Gradescope and check the completeness of the contents after submission.
