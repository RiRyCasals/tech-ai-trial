# tech-ai-trial
体験授業向けAIデモ（[mediapipe](https://google.github.io/mediapipe/getting_started/python#ready-to-use-python-solutions)より）


# 動かし方

```
conda activate tech-ai-trial
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
conda env create -f ./tech-ai-trial.yaml
```

上記のコマンドが実行できない場合は下記のコマンドを実行する

```
conda create -n tech-ai-trial python=3.8.13
conda activate tech-ai-trial
pip install pillow==9.2.0 matplotlib==3.5.3 numpy==1.23.3 mediapipe==0.8.11
```