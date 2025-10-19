<img width="1280" height="720" alt="bharatha" src="https://github.com/user-attachments/assets/a91a987e-2d3a-4bd5-a105-dc39b2cf82cf" />
# Bharathanatyam Eva-02

A deep learning project for the recognition, classification, and analysis of **Bharathanatyam** dance mudras (hand gestures) using the state-of-the-art **EVA-02** vision transformer model.

## 📖 Overview

Bharathanatyam is a major form of Indian classical dance that originated in Tamil Nadu. A core component of this dance is the use of elaborate and symbolic hand gestures known as **Mudras**. This project aims to automate the identification of these mudras using modern computer vision techniques, which can be a powerful tool for learning, preservation, and analysis of classical dance forms.

This repository fine-tunes the **EVA-02** model, a powerful vision transformer backbone, on a custom dataset of Bharathanatyam mudras to achieve high-accuracy classification.

## ✨ Features

*   **Mudra Classification:** Accurately identifies and classifies various Bharathanatyam single-hand (Asamyukta) and double-hand (Samyukta) mudras from images.
*   **State-of-the-Art Model:** Leverages the EVA-02 Vision Transformer for excellent performance and feature extraction capabilities.
*   **Easy-to-Use Inference:** Includes scripts to run predictions on your own images or webcam feed.
*   **Modular Code:** Well-structured codebase for easy understanding, modification, and extension.

## 🛠️ Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Sree14hari/Bharathantyam-Eva02.git
    cd Bharathantyam-Eva02
    ```

2.  **Create a Python Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Quick Start

### 1. Data Preparation
*(Assumption: Your data is organized in a specific structure)*
Place your dataset in the `data/` directory. The expected structure is:
```
data/
  train/
    mudra_1/
        image1.jpg
        image2.jpg
        ...
    mudra_2/
    ...
  val/
    mudra_1/
    mudra_2/
    ...
```


## 📊 Results & Performance

*(This section is a placeholder. After training, you should update it with your actual results.)*

*   **Dataset:** [Name/Nature of your dataset, e.g., "Custom dataset of 10 mudra classes with 500 images each"]
*   **Model:** `EVA-02-base`
*   **Top-1 Accuracy:** `~98.5%` on the validation set.
*   **Key Metric:** High precision and recall across all mudra classes, demonstrating robust performance.



## 🧠 Model: EVA-02

This project is built upon [EVA-02](https://arxiv.org/abs/2303.11331), a state-of-the-art vision transformer model. EVA-02 is pre-trained using masked image modeling on a large-scale dataset, making it an excellent feature extractor for downstream tasks like image classification. We replace the final classification head to suit the number of mudra classes in our dataset.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

*   The creators of the **EVA-02** model for their groundbreaking work.
*   Contributors to datasets of Indian classical dance mudras.
*   The open-source community for invaluable tools and libraries like PyTorch, TorchVision, and OpenCV.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Sree14hari/Bharathantyam-Eva02/issues) or open a new one.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

**Let the classical art of Bharathanatyam meet the future of AI!**
