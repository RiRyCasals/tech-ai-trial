# tech-ai-0914
体験授業向けAIデモ（[mediapipe](https://google.github.io/mediapipe/getting_started/python#ready-to-use-python-solutions)より）


# 動かし方

```
conda activate tech-ai-0914
python demo-face-mesh.py
```

- demo-face-mesh.py
- demo-holistic.py
- demo-pose.py
- demo-selfie-segmentation.py
- demo-objectron.py


注）demo-objectron.py で認識できるのは次のもののみ

- shoe（靴）
- cahir（椅子）
- cup（コップ）
- camera（カメラ）


# Anaconda環境の作成

```
conda env -n tech-ai-0914 -f ./tech-ai-0914.yaml
```
