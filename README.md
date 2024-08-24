# IE-634 Course Project Starting Tips

August 23, 2024

---

## [1] Problem Identification

Whether the task is a,

- Supervised
- Semi-Supervised
- Unsupervised
- Classification Problem
- Regression Problem
- Object Localization
- Generation Problem
- Anomaly Detection, etc.

## [2] Past Work Done

- Check whether a similar task has been done before, using YouTube videos or a simple Google search.
- Check which model was used in that work.
- Identify the dataset used in that work.
- Some websites for looking work done:
- For Research papers:
    - [https://paperswithcode.com](https://paperswithcode.com)
    - [https://neurips.cc](https://neurips.cc)
    - [https://arxiv.org](https://arxiv.org)
- For Models:
    - [https://huggingface.co/models](https://huggingface.co/models)
    - [https://paperswithcode.com/sota](https://paperswithcode.com/sota)
- GitHub: [https://github.com/marketplace](https://github.com/marketplace)

## [3] Breaking the task into Smaller task

- Identify subtasks: Break the main task into clear, manageable parts.
- Prioritize and sequence: Order subtasks by importance or logical flow.

This approach sharpens focus, reduces overwhelm, and boosts project success.

## [4] Data Collection

- If a suitable dataset wasn't found during the search for past work, a similar dataset can be located on the websites below, based on the problem type identified in [*step [1]*](https://www.notion.so/IE-634-Course-Project-Starting-Tips-7069afad196e454bbe47f002589a29ff?pvs=21).
- Some websites for dataset:
    - [https://paperswithcode.com/datasets](https://paperswithcode.com/datasets)
    - [https://huggingface.co/datasets](https://huggingface.co/datasets)
    - [https://www.kaggle.com/datasets](https://www.kaggle.com/datasets)

## [5] Data Preprocessing

- If the dataset found cannot be used directly for our task, then some data curation, augmentation, and preprocessing must be done.
- Sometimes, to modify the found dataset into a useful one, extra models and techniques have to be utilized.

## [6] Model Selection

- Once we have the dataset ready, a suitable model (in terms of data size and data type) must be found.
- If our task requires fast inference, we should consider a model with less inference time.
- If the dataset size is small or data collection is a tedious process, then a pre-trained model can be used.
- For Pre-trained Models:
    - [https://huggingface.co/models](https://huggingface.co/models)
    - [https://paperswithcode.com/sota](https://paperswithcode.com/sota)
    - [https://timm.fast.ai/](https://timm.fast.ai/)
    - [https://pytorch.org/vision/stable/models.html](https://pytorch.org/vision/stable/models.html)

## [7] Training Model

- Proper hardware should be used for training the model at scale.
- GPU devices can be used to reduce training time.
- For GPU usage, [Kaggle](https://www.kaggle.com/page/GPU-tips-and-tricks) is a viable option.
- To use Kaggle effectively, intermediate progress (model weights, learning rate, results, etc.) can be saved.
- Unlike Colab, Kaggle offers a [Persistence](https://www.kaggle.com/discussions/product-feedback/355440) feature to save session data.

## [8] Inference Stage

- After training the model, a Python-based (or other) interface can be created for inference or showcasing model output.
- For Python based web apps framework: [Streamlit](https://docs.streamlit.io/)

---

# Automatic Class Attendance

Develop an automated system to mark student attendance from class photos using facial recognition. The system should accurately identify and log attendance for each student in the image. Ensure the solution is scalable and adaptable for varying classroom settings.

### [1] Problem Identification

### [2] Past Work Done

### [3] Data Collection

### [4] Data Preprocessing

### [5] Model Selection

### [6] Training Model

### [7] Inference Stage
