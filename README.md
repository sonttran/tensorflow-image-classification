# Image recognition using Tensorflow official model
* Image classification using official <a href="https://github.com/tensorflow/models">Tensorflow model</a> trained with <a href="http://www.image-net.org/">ImageNet</a> dataset.

### Usage
* Have Python and Tensorflow installed
* Run
```
git clone https://github.com/sonttran/tensorflow-image-classification.git
cd tensorflow-image-classification
python3 classify_image.py --image_file <path/to/your/image/file> --num_top_predictions <integer (default 5)>
```
* Example
```
python3 classify_image.py --image_file ./5.jpeg 
```
### <a href="">Live demo</a> 
* This demo uses <a href="https://github.com/sonttran/server">Vpop Node.js server</a> and expose this image recognition engine to the web