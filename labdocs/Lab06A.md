# Lab 6A: Creating a Pipeline

You can use the Azure Machine Learning SDK to perform all of the tasks required to create and operate a machine learning solution in Azure. Rather than perform these tasks individually, you can use *pipelines* to orchestrate the steps required to prepare data, run training scripts, register models, and other tasks.

## Before You Start

Before you start this lab, ensure that you have completed [Lab 1A](Lab01A.md) and [Lab 1B](Lab01B.md), which include tasks to create the Azure Machine Learning workspace and other resources used in this lab.

## Task 1: Create a Pipeline

In this task, you'll create a pipeline to train and register a model.

1. In [Azure Machine Learning studio](https://ml.azure.com), view the **Compute** page for your workspace; and on the **Compute Instances** tab, ensure your compute instance is running. If not, start it.
2. When the compute instance is running, click the **Jupyter** link to open the Jupyter home page in a new browser tab.
3. In the Jupyter home page, in the **Users/DP100** folder, open the **06A - Creating a Pipeline.ipynb** notebook. Then read the notes in the notebook, running each code cell in turn.

> **Note**: If you intend to continue straight to the [next exercise](Lab06B.md), leave your compute instance running. If you're taking a break, you might want to close all Jupyter tabs and **Stop** your compute instance to avoid incurring unnecessary costs.
