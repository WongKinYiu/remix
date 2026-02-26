# ReMixing Features from Detectors and Visual Foundation Models for Efficient Object Detection

## Performance

| Model | AP | AP50 | AP75 | Latency (T4) | FPS (T4) | Note |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| RT-DETRv4-S | 49.8 | 67.1 | 54.0 | 3.66 ms | 273 | 132e/132e |
| + Mix | 46.3 | 63.0 | 50.4 | 3.66 ms | 273 | 59e/132e |
| + Re |  |  |  | 3.66 ms | 273 |  |
| + ReMix |  |  |  | 3.66 ms | 273 |  |
|  |  |  |  |  |  |  |
| RT-DETRv4-M | 53.7 | 71.0 | 58.4 | 5.91 ms | 169 | 102e/102e |
| + Mix | 53.5 | 70.6 | 58.7 | 5.91 ms | 169 | 56e/102e |
| + Re |  |  |  | 5.91 ms | 169 |  |
| + ReMix |  |  |  | 5.91 ms | 169 |  |
|  |  |  |  |  |  |  |
| RT-DETRv4-L | 55.4 | 73.0 | 60.3 | 8.07 ms | 124 | 58e/58e |
| + Mix | 56.4 | 73.9 | 61.6 | 8.07 ms | 124 | 51e/58e |
| + Re |  |  |  | 8.07 ms | 124 |  |
| + ReMix |  |  |  | 8.07 ms | 124 |  |
|  |  |  |  |  |  |  |
| RT-DETRv4-X | 57.0 | 74.6 | 62.1 | 12.90 ms | 78 | 58e/58e |
| + Mix | 57.4 | 75.1 | 63.0 | 12.90 ms | 78 | 43e/58e |
| + Re |  |  |  | 12.90 ms | 78 |  |
| + ReMix |  |  |  | 12.90 ms | 78 |  |
|  |  |  |  |  |  |  |

* Our models are under training, the reported performance are temporarily results.

## Acknowledgement

Our work is built upon [RT-DETRv4](https://github.com/RT-DETRs/RT-DETRv4), [DEIMv2](https://github.com/Intellindust-AI-Lab/DEIMv2), [DINOv3](https://github.com/facebookresearch/dinov3), and [D-FINE](https://github.com/Peterande/D-FINE).
Thanks for thier excellent works!
