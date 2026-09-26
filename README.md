# Midterm-Final-Project-Proposal
# Waste Classification Recycling Helper

## Team Members

* Syed Ayan

## Project Tier

**Tier 1: Core**

This project fits Tier 1 because it uses one computer vision model to perform one main task: classify waste items into different categories.

## Problem Statement

People often have difficulty deciding how to properly sort household waste. Incorrect sorting can cause recyclable materials to be placed in the trash and can make recycling less effective. This project is designed to help households, schools, businesses, and recycling programs identify common types of waste.

## Solution Overview

The Waste Classification Recycling Helper will use computer vision to identify the category of a waste item from an image. A user will provide an image, the image classification model will analyze it, and the system will return the predicted waste category.

**Input → Model → Output**

Waste image → Image classification model → Waste category

For example:

**Image of plastic bottle → Plastic**

## Technical Approach

* **CV Technique:** Image Classification
* **Model Architecture:** CNN
* **Model:** MobileNet
* **How we will use it:** Transfer learning using a pretrained model
* **Framework:** TensorFlow / Keras
* **Why this approach:** MobileNet is a lightweight image classification model that is appropriate for a Tier 1 project and can be used with free computing resources.

## Dataset

* **Source:** TrashNet public dataset
* **Size:** Approximately 2,500+ labeled images
* **Labels:** Plastic, Paper, Metal, Glass, Cardboard, and Trash
* **Link:** To be verified and added before final submission

The images will be divided into training and testing data so the model can be evaluated using images it has not seen during training.

## Success Metrics

### Primary Metric

**Classification Accuracy**

Target: **At least 85% accuracy**

This will measure how often the model correctly identifies the waste category.

### Secondary Metric

**Inference Speed**

Target: **Under 1 second per image**

This will measure how quickly the model can classify an individual image.

Additional evaluation will include a confusion matrix, misclassified images, and performance across the different waste categories.

## Milestone Plan

| Phase               | Goal                                          | Target    |
| ------------------- | --------------------------------------------- | --------- |
| Blueprint           | Complete proposal and GitHub setup            | Week 5    |
| First Working Demo  | Run a pretrained model on sample images       | Week 6    |
| Make It Yours       | Train and test using the waste dataset        | Weeks 7–8 |
| Improve and Measure | Evaluate accuracy and improve the model       | Week 9    |
| Build               | Complete demo, README, and final presentation | Week 10   |

The First Working Demo will be completed before the major data and training work.

## Resources

* **Compute:** Google Colab
* **Backup Compute:** Kaggle Notebook
* **Framework:** TensorFlow / Keras
* **Dataset:** TrashNet
* **Cost:** $0
* **Model:** MobileNet

All project resources will use free-tier or open-source options.

## Risks and Mitigation

| Risk                                               | Probability | Plan B                                                                      |
| -------------------------------------------------- | ----------- | --------------------------------------------------------------------------- |
| Model accuracy is lower than expected              | Medium      | Improve preprocessing and image augmentation or test EfficientNet           |
| Training or Google Colab problems                  | Medium      | Use a pretrained model and focus on application and evaluation              |
| Some waste categories are difficult to distinguish | Medium      | Analyze misclassified images and improve the training data or preprocessing |

## Demo Video

Link will be added at the Final.

## AI Usage Log

See [`docs/AI_usage_log.md`](docs/AI_usage_log.md).

AI tools will be used as learning aids for brainstorming, understanding concepts, debugging, and improving code. Major AI interactions will be documented in the AI usage log.

## Current Status

* [x] Repository created
* [x] Project idea selected
* [x] Tier selected
* [x] Proposal slides created
* [ ] Proposal submitted
* [ ] First working demo
* [ ] System works on our data
* [ ] Metrics measured
* [ ] Final submitted
