# yolovision

Notebook-first repository for quick object-detection experiments and visualizations (YOLO-style workflows).

Detected files
- my_first_yolo_model.ipynb — a hands-on notebook for building / training / inspecting a first YOLO model
- another_yolo.ipynb — additional experiments and visualization demos

Quickstart

1. Clone
   git clone https://github.com/jumanewton/yolovision.git
   cd yolovision

2. Create environment
   python3 -m venv .venv
   source .venv/bin/activate

3. Install dependencies
   pip install -r requirements.txt
   If you plan to use a particular YOLO implementation (Ultralytics, YOLOv5), follow its install notes. The requirements include Ultraytics for notebook convenience.

4. Run
   jupyter lab
   Open the notebooks and follow their top-cell instructions for dataset paths and expected structure.

Typical flows
- Prepare / convert datasets (VOC / COCO / custom) into a simple images/labels layout used in the notebooks.
- Train small models for quick iteration (use small image sizes and few epochs).
- Run inference on sample images and visualize bounding boxes, confidences, etc.

Notes
- GPU is strongly recommended for any non-trivial training.
- The notebooks are for prototyping and visualization. If you move to production training, extract the core scripts from notebook cells to standalone Python scripts.

Suggestions for repo improvements
- Add an examples/ folder with a tiny sample dataset (2–10 images + labels)
- Add training configs or links to configs used in the notebooks
- Add a LICENSE and CONTRIBUTING file

Contact
- Open an issue if you want specific notebook cleanups or requirements tuned for a particular YOLO implementation.
