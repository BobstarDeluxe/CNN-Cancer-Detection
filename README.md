# Histopathologic Cancer Detection

## Overview

This project focuses on developing a Convolutional Neural Network (CNN) for binary classification of histopathologic scans to detect metastatic cancer tissue in lymph node sections. The model automatically classifies image patches as either containing metastatic tissue (positive) or normal tissue (negative), supporting critical medical diagnosis decisions.

## Problem Statement

**Objective**: Build a CNN model that can accurately identify the presence of metastatic cancer in small histopathologic image patches.

**Classification Task**:
- **Positive (1)**: Contains metastatic tissue (cancer present)
- **Negative (0)**: Normal tissue (no cancer detected)

## Dataset

**Source**: Modified version of the PatchCamelyon (PCam) benchmark dataset, derived from the Camelyon16 Challenge. The Kaggle version has been cleaned to remove duplicate images from the original PCam dataset.

**Image Specifications**:
- **Format**: RGB histopathologic image patches
- **Dimensions**: 96 × 96 pixels
- **Classification Region**: Center 32 × 32 pixel area
- **Channels**: 3 (RGB)
- **File Type**: TIF images
- **Naming Convention**: Unique image IDs

**Clinical Significance**: Early and accurate detection of cancer metastasis can significantly impact patient treatment decisions and outcomes, making this a high-stakes medical imaging application.
