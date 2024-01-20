# Japa_onnx
### Instalation
1. CLone the repo
2. cd \scripts\whisper
3. Download the onnx models from drive from [here](https://drive.google.com/drive/folders/1Hk2jWrIAoAxLEjEhP_8oQN3C6a5REeBf?usp=sharing).
4. Post downloading the weights place all of them inside the whisper directory 
5. conda create -n japa python=3.8
6. conda activate japa
7. pip install -r requrements.txt
8. python ./test.py --encoder ./medium-encoder.int8.onnx --decoder ./medium-decoder.int8.onnx --tokens ./medium-tokens.txt ./Gurumantra_.wav --language hi
