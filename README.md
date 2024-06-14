## Real Time Object Detection for Libras

To run the jupyter notebok use:

```
python3 -m notebook
```

To train, use:

```
python ~/Downloads/Tensorflow/models/research/object_detection/model_main_tf2.py --model_dir=Tensorflow/workspace/models/my_ssd_mobnet --pipeline_config_path=Tensorflow/workspace/models/my_ssd_mobnet/pipeline.config --num_train_steps=5000
```

# Tutorial

Environment instalation tutorial: https://neptune.ai/blog/how-to-train-your-own-object-detector-using-tensorflow-object-detection-api

Implementation tutorial: https://www.youtube.com/watch?v=pDXdlXlaCco

# Passo a passo:

1. Tirar as fotos que servirão para treinar a IA.

- Foram 426 fotos (16 por letra do alfabeto).

2. Rotular as fotos usando labelImg.
3. Criar um label map.
4. Treinar.
