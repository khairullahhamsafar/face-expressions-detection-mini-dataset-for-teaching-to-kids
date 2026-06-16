# Facial Expressions Mini Dataset for Kids

A small, kid-friendly facial expression dataset designed for teaching machine learning and computer vision concepts to children.

## 📁 Dataset Structure

```text
facial-expressions-mini/
├── angry/      # 300 angry face images
├── disgust/    # 300 disgust face images
├── fear/       # 300 fear face images
├── happy/      # 300 happy face images
├── neutral/    # 300 neutral face images
├── sad/        # 300 sad face images
└── surprise/   # 300 surprise face images
```

- **Seven classes**: `angry`, `disgust`, `fear`, `happy`, `neutral`, `sad`, `surprise`
- **Images per class**: 300
- **Total images**: 2,100

## 🎯 Purpose

This dataset is perfect for:
- Introduction to machine learning and computer vision for kids
- Facial expression recognition projects
- Learning about image classification
- Hands-on AI and coding activities for beginners

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 7 (angry, disgust, fear, happy, neutral, sad, surprise) |
| Images per class | 300 |
| Total images | 2,100 |
| Dataset size | Mini/small |
| Source | Compiled from larger online datasets |

## 🚀 Quick Start

```python
from pathlib import Path

dataset_dir = Path("facial-expressions-mini")

for class_dir in dataset_dir.iterdir():
    if class_dir.is_dir():
        print(f"{class_dir.name}: {len(list(class_dir.glob('*')))} images")
```

## ⚠️ Notes

- Images were collected and prepared from various publicly available larger datasets
- Ideal for educational purposes and beginner AI/ML projects
- Small size makes it suitable for quick training and experimentation on local machines

## 📝 License

Public dataset for educational use.
