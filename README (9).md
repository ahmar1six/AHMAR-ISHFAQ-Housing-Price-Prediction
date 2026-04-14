# 🏠  Multimodal Housing Price Prediction System

A state-of-the-art multimodal deep learning model that predicts housing prices by combining **tabular data** (house features) with **visual features** extracted from house images using a pre-trained CNN (ResNet-18).

## 📁 Project Files

| File | Description |
|------|-------------|
| `Multimodal Housing Price System.ipynb` | Complete Google Colab notebook with training & GUI |
| `requirements.txt` | Python dependencies for the project |
| `house.JPG` | Sample house image input |
| `input.JPG` | Input interface screenshot |
| `output.JPG` | Prediction output screenshot |
| `output01.JPG` | Additional output example 1 |
| `output02.JPG` | Additional output example 2 |

## 🎯 Project Overview

This project demonstrates a production-ready multimodal approach to real estate price prediction. By fusing structured data with computer vision, the model captures both quantitative metrics (square footage, bedrooms, etc.) and qualitative visual cues (curb appeal, condition, aesthetics).

### Key Results

| Metric | Score |
|--------|-------|
| **Mean Absolute Error (MAE)** | $42,495 |
| **Root Mean Square Error (RMSE)** | $63,573 |
| **R² Score** | 0.473 |
| **Mean Absolute Percentage Error (MAPE)** | 23.05% |

## 🖼️ Model in Action

**House Image Input**

![House Image](house.JPG)

*Sample house image uploaded to the model*

---

**Input Form**

![Model Input](input.JPG)

*House image and tabular features fed into the model*

---

**Output: Price Prediction**

![Model Output](output.JPG)

*Model predicts sale price with confidence intervals*

---

**Additional Examples**

![Output Example 1](output01.JPG)

*Sample prediction 1*

![Output Example 2](output02.JPG)

*Sample prediction 2*

## 🚀 Quick Start

### 1. Installation

```bash
# Clone repository
git clone https://github.com/yourusername/multimodal-housing-price.git
cd multimodal-housing-price

# Install dependencies
pip install -r requirements.txt
