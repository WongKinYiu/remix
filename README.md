# ReMixing Features from Detectors and Visual Foundation Models for Efficient Object Detection

## Performance

| Model | AP | AP50 | AP75 | Latency (T4) | FPS (T4) | Note |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| RT-DETRv4-S | 49.8 | 67.1 | 54.0 | 3.66 ms | 273 | official |
| + Mix |  |  |  | 3.66 ms | 273 |  |
| + Re |  |  |  | 3.66 ms | 273 |  |
| + ReMix |  |  |  | 3.66 ms | 273 |  |
|  |  |  |  |  |  |  |
| RT-DETRv4-M | 53.7 | 71.0 | 58.4 | 5.91 ms | 169 | official |
| + Mix |  |  |  | 5.91 ms | 169 |  |
| + Re |  |  |  | 5.91 ms | 169 |  |
| + ReMix |  |  |  | 5.91 ms | 169 |  |
|  |  |  |  |  |  |  |
| RT-DETRv4-L | 55.4 | 73.0 | 60.3 | 8.07 ms | 124 | official |
| + Mix | 56.5 | 74.2 | 61.6 | 8.07 ms | 124 | [weights](https://github.com/WongKinYiu/storage/releases/download/remix/RTv4-L-hgnet-Mix.pth) |
| + Re | 56.6 | 74.0 | 61.5 | 8.07 ms | 124 |  |
| + ReMix |  |  |  | 8.07 ms | 124 |  |
|  |  |  |  |  |  |  |
| RT-DETRv4-X | 57.0 | 74.6 | 62.1 | 12.90 ms | 78 | official |
| + Mix | 58.5 | 75.9 | 63.8 | 12.90 ms | 78 | [weights](https://github.com/WongKinYiu/storage/releases/download/remix/RTv4-X-hgnet-Mix.pth) |
| + Re | 58.6 | 76.0 | 63.9 | 12.90 ms | 78 |  |
| + ReMix |  |  |  | 12.90 ms | 78 |  |
|  |  |  |  |  |  |  |

* Our models are under training, the reported performance are temporarily results.

| Model | AP | AP50 | AP75 | Latency (T4) | note |
| :---: | :---: | :---: | :---: | :---: | :---: |
| DEIMv2-S | 50.9 | 68.3 | 55.1 | 5.78 | official |
| + Mix |  |  |  | 5.78 |  |
| + Re |  |  |  | 5.78 |  |
| + ReMix |  |  |  | 5.78 |  |
|  |  |  |  |  |  |
| DEIMv2-M | 53.0 | 70.2 | 57.6 | 8.80 | official |
| + Mix |  |  |  | 8.80 |  |
| + Re |  |  |  | 8.80 |  |
| + ReMix |  |  |  | 8.80 |  |
|  |  |  |  |  |  |
| DEIMv2-L | 56.0 | 73.4 | 60.9 | 10.47 | official |
| + Mix |  |  |  | 10.47 |  |
| + Re |  |  |  | 10.47 |  |
| + ReMix |  |  |  | 10.47 |  |
|  |  |  |  |  |  |
| DEIMv2-X | 57.8 | 75.4 | 63.2 | 13.75 | official |
| + Mix |  |  |  | 13.75 |  |
| + Re |  |  |  | 13.75 |  |
| + ReMix |  |  |  | 13.75 |  |
|  |  |  |  |  |  |

* The performance for DEIMv2s are just temporarily results.



## Acknowledgement

Our work is built upon [RT-DETRv4](https://github.com/RT-DETRs/RT-DETRv4), [DEIMv2](https://github.com/Intellindust-AI-Lab/DEIMv2), [DINOv3](https://github.com/facebookresearch/dinov3), and [D-FINE](https://github.com/Peterande/D-FINE).
Thanks for thier excellent works!
