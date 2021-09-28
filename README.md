# YOLOv5-Ghost
## Instructions:

1. **Clone project repository**

`git clone https://github.com/changhaochen-98/YOLOv5-Ghost.git`

2. **Unzip dataset**

Unzip YOLOv5-Ghost-dataset.zip

3. **Import dataset**

Put all the decompressed folders into /dataset path.

4. **Training dataset**

- You can call train.py from the command line via Python to execute;

- You can run train.py directly in the Python compiler.

After the training is completed, the runs/train/exp path will be generated in the root path, which contains each training result and model. The /wandb directory contains visualize experimental result.

5. **Testing**

Put the test files in the /testfiles path.

- You can call detect.py from the command line via Python to execute;

- You can run detect.py directly in the Python compiler.

After the testing is completed, the runs/detect/exp path will be generated in the root path, which contains each testing result with bounding box.


