# T2.1 Pre-trained YOLO evaluation

Evaluates the COCO-pre-trained `yolo11n.pt` on the test set for the Car class: AP50, AP50-95 and the precision-recall curve. Part of [2D Object Detector](https://github.com/2DObjectDetector).

**Result:** Car AP50 = 0.713 and AP50-95 = 0.405 on the test set. The model finds cars well but localises them imprecisely at high IoU thresholds, which is consistent with the domain shift from COCO to onboard-camera images.

**Run:** Outputs are saved in the notebook, so the results are visible without running it. To rerun: use a Colab GPU runtime and add the `kitti3k_yolo` dataset (not included) and update its path.
