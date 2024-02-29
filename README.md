# S2S-sim
The first ship collaborative perception simulation dataset.

We proposed the ship cooperative perception dataset S2S-sim. Based on Unity3D, we simulated three typical navigation scenes and constructed a 64-line simulated LiDAR mounted on typical ships to collect data according to the characteristics of real LiDAR sensors. A total of 7000 frames of cooperative sensing data were collected for collaboration within a range of 2 km.

## Dataset acquisition
You can obtain data from our [cloud storage](https://pan.baidu.com/s/11mqQPwbV-Y9KcczWnBRaiQ) using the code: zn8k

## How to use dataset
Our dataset can be easily integrated into the [OpenCOOD](https://github.com/DerrickXuNu/OpenCOOD.git) framework for usage. However, it is important to note that before conducting experiments, adjustments to parameters such as perception range and voxel size need to be made.

## Citation
Welcome to use our dataset and cite our paper.
```Tex
@article{yang2024s2s,  
  title={S2S-Sim: A Benchmark Dataset for Ship Cooperative 3D Object Detection}, 
  author={Yang, Wenbin and Wang, Xinzhi and Luo, Xiangfeng and Xie, Shaorong and Chen, Junxi},
  journal={Electronics},
  volume={13}, 
  number={5},  
  pages={885}, 
  year={2024}, 
  publisher={MDPI}
}
```
