# Japa_onnx
### Instalation
1. CLone the repo
2. cd \sherpa-onnx\scripts\whisper
3. conda create -n japa python=3.8
4. conda activate japa
5. pip install -r requrements.txt
6. python ./test.py --encoder ./medium-encoder.int8.onnx --decoder ./medium-decoder.int8.onnx --tokens ./medium-tokens.txt ./Gurumantra_.wav --language hi
