
# 🚀 Training Faster R-CNN on Custom Dataset (PyTorch)

This repository provides a complete pipeline to train [Faster R-CNN](https://arxiv.org/abs/1506.01497) using **PyTorch** on a **custom dataset**. The notebook includes dataset loading, model setup, training, and evaluation — all built for flexibility and fast experimentation.

---

## 🧠 Features

- ✅ Faster R-CNN with ResNet-50 + FPN backbone (TorchVision)
- 🧾 COCO-format dataset support
- 🧪 Albumentations-based augmentations
- 📈 Training visualization
- 💾 Checkpoint saving

---

## 🗂️ Structure

```
.
├── Faster_RCNN.ipynb       # Main training notebook
├── dataset/                # Images (train & val)
└── annotations/            # COCO-style JSON annotations
```

---

## 🔧 Setup

```bash
git clone https://github.com/yourusername/Faster-RCNN-Custom-Training.git
cd Faster-RCNN-Custom-Training
pip install -r requirements.txt
```

---

## 🚀 Usage

1. Place your data in the `dataset/` and `annotations/` folders.
2. Open and modify the notebook paths if needed.
3. Run `Faster_RCNN.ipynb`.

---

## 🖼️ Example Output

![Example](assets/example.png)

---

## 📄 Citation

```bibtex
@article{fasterrcnn,
  title={Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks},
  author={Ren, Shaoqing and He, Kaiming and Girshick, Ross and Sun, Jian},
  journal={IEEE TPAMI},
  year={2015}
}
```

---

## 📜 License

MIT License
