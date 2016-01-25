# bag-of-words

 Bag of Words for Image Recognition using OpenCV and Scikit-learn

## Training the classifier
```
python findFeatures.py -t dataset/train/train100

or

python findFeatures.py -t dataset/train/train1000

```

## Testing the classifier
* Testing a number of images
```
python getClass.py -t dataset/test/cat --visualize

or

python getClass.py -t dataset/test/dog --visualize
```
The `--visualize` flag will display the image with the corresponding label printed on the image/

* Testing a single image
```
python getClass.py -i dataset/test/cat/cat.10000.jpg --visualize
```

