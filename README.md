# D-FINE-ONNX-Sample
[Peterande/D-FINE](https://github.com/Peterande/D-FINE)のPythonでのONNX推論サンプルです。<br>
変換自体を試したい方は、Google Colaboratory上で[Convert2ONNX.ipynb](Convert2ONNX.ipynb)を使用ください。<br><br>
![image](https://github.com/user-attachments/assets/f8597453-f9a5-478f-bfe9-e402166adc76)

# Requirement 
* OpenCV 4.5.3.56 or later
* onnxruntime 1.11.0 or later

# Convert
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kazuhito00/D-FINE-ONNX-Sample/blob/main/Convert2ONNX.ipynb)<br>
Colaboratoryでノートブックを開き、上から順に実行してください。<br>

# Demo
デモの実行方法は以下です。
```bash
python sample_onnx.py
```
* --device<br>
カメラデバイス番号の指定<br>
デフォルト：0
* --movie<br>
動画ファイルの指定 ※指定時はカメラデバイスより優先<br>
デフォルト：指定なし
* --image<br>
画像ファイルの指定 ※指定時はカメラデバイスより優先<br>
デフォルト：指定なし
* --model<br>
ロードするモデルの格納パス<br>
デフォルト：model/dfine_s_obj2coco.onnx
* --score_th<br>
検出閾値<br>
デフォルト：0.6
* --unuse_gpu<br>
GPU推論なし（CPU推論）<br>
デフォルト：指定なし

# Reference
* [Peterande/D-FINE](https://github.com/Peterande/D-FINE)

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
D-FINE-ONNX-Sample is under [Apache 2.0 License](LICENSE).

# Note
サンプルの画像は[ぱくたそ](https://www.pakutaso.com/)様の「[ものすごい数のバイクの列（ベトナムホーチミン）](https://www.pakutaso.com/20170628178post-12228.html)」を使用しています。
