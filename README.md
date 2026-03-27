# Yoga Pose Detection - ML Project

An AI-powered yoga pose detector that identifies 8 fundamental yoga asanas using a custom-trained CNN.

## 📋 Detectable Poses

1. **Adho Mukha Svanasana** - Downward Dog
2. **Virabhadrasana I** - Warrior I
3. **Virabhadrasana II** - Warrior II
4. **Vriksasana** - Tree Pose
5. **Bhujangasana** - Cobra Pose
6. **Balasana** - Child's Pose
7. **Dandasana** - Staff Pose
8. **Chaturanga Dandasana** - Low Plank

## 🛠️ Installation

```bash
pip install -r requirements.txt
```

## 📁 Project Structure

```
├── data/                        # Training & validation datasets
│   ├── train/                  # Training images
│   └── val/                    # Validation images
├── yoga_augmented/             # Augmented dataset versions
├── yoga_model.pth              # Pre-trained model weights
├── yoga_pose_classifier.ipynb  # Main classification notebook
├── yoga_augmentation.ipynb     # Data augmentation pipeline
├── download_yoga_dataset.ipynb # Dataset download script
├── yoga_api.ipynb              # API endpoint notebook
├── yogalens.html               # Web interface
└── requirements.txt            # Dependencies
```

## 🚀 Usage

### Train Model
Run the `yoga_pose_classifier.ipynb` notebook to train the CNN from scratch.

### Web Interface
Open `yogalens.html` in your browser for the interactive detection UI.

### API
Run `yoga_api.ipynb` to start the prediction API endpoint.

## 📊 Model Details

- **Architecture**: Custom CNN trained from scratch
- **Framework**: PyTorch
- **Classes**: 8 yoga poses
- **Confidence Scoring**: Softmax probability distribution

## 📝 Requirements

See `requirements.txt` for all dependencies.

## 📄 License

This project is open source.

---

**YogaLens** - AI-Powered Pose Detection
