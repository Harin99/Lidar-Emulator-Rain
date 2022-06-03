# Lidar-Emulator-Rain
## Introduction
This is the Lidar Emulator considering rainfall effect using Unity3d. This emulator can produce the lidar simulation data considering the rainfall effect for Lidar sensor. We constructed the simple simulation environment using RoadRunner, Matlab. 

## Effects by rainfall 
Lidar sensor is affected by weather like rain. Representative Effects include Intensity Attenuation effect caused by atmospheric transmission of a laser pulse and Noise Effect caused by a collision between laser and raindrop particles. By this effects, the Lidar sensor of Autonomous Vehicles suffer a significant performance degradation compared to clear weather. Therefore, Lidar sensor modeling is required to obtain the lidar data similar with real lidar sensor in simulation.

1) Intensity Attenuation 
    
2) Noise Effect 

## Evaluation
### Dataset 
Sensor : VLP-16
Place : Parking lot in University of Seoul
우리는 모델 캘리브레이션 및 평가를 위해 실제 강우 환경에서 라이다 데이터를 취득하였다. 데이터는 신호감쇠모델의 캘리브레이션을 위하여 균일하고 동일한 반사도로 구성된 평면이 존재한다. 또한 모델 검증을 위하여 도로에서 주로 볼 수 있는 차량 및 도로 콘을 배치하여 데이터를 취득하였다. 총 5가지 ( 6, 18, 30, 48, 60mm/h )의 강수량에 대한 데이터셋을 취득할 수 있었으며, 5분별 강수량 정보는 기상청 데이터를 이용하였다. 


### Results

