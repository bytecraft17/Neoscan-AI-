# NeoScan AI 🍼

AI-powered neonatal screening system detecting 15+ conditions using deep learning.

## Modules
- Module 1: Skin Analysis (Jaundice, Cyanosis, Anemia) — EfficientNetB3
- Module 2: Body Analysis (Limb defects, Hydrops) — ResNet-50
- Module 3: Eye Analysis (ROP, Cataracts) — InceptionV3
- Module 4: Face Analysis (Down Syndrome, Cleft Palate) — VGG16

## Datasets
## Datasets
All datasets are stored on Google Drive and are not included in this repo.

| Module | Dataset | Size |
|--------|---------|------|
| Skin | DermaNet Neonatal + CHOP Jaundice | 8,000+ images |
| Eye | ROP Retinal Dataset | 6,004 images |
| Face | VisAGe + Down Syndrome DB | 3,000+ images |
| Body | BabyPose Dataset | 10,000+ frames |

Dataset access available on request.

## Tech Stack
PyTorch, TensorFlow, OpenCV, FastAPI, React
