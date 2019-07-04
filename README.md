# image-classification

https://www.tensorflow.org/hub/tutorials/image_retraining

```
pip install tensorflow_hub
```

## Folder structure

```
imgs/
  biban/
  stiuca/
  somn/
  pastrav/
```

```
python retrain.py --image_dir=imgs

python label_image.py \
--graph=/tmp/output_graph.pb --labels=/tmp/output_labels.txt \
--input_layer=Placeholder \
--output_layer=final_result \
--input_height=224 --input_width=224 \
--image=path_to_img.png
```

https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2-tflite/#0
