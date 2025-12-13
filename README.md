# Covering-Manifold-Database  
Coverage Manifold Dataset over Main Urban Area of Nanjing, Jiangsu, China  

## 数据集概述 / Dataset Overview  
本仓库提供中国江苏省南京市主城区的三类数据：  
This repo provides three kinds of data for the main urban area of Nanjing, Jiangsu, China:

1. **DEM 数据**  
   DEM data ( digital elevation model)

2. **基站位置数据**（851 个 5G 宏基站经纬度、高度）  
   Base-station locations (851 5G macro cells with longitude, latitude, height)

3. **覆盖流形数据**（五种门限：0 dB, 5 dB, 10 dB, 15 dB, 20 dB）  
   Coverage manifold data under five thresholds: 0 dB, 5 dB, 10 dB, 15 dB, 20 dB  
   每种门限包含三种策略 / Three strategies per threshold:  
   - 最大 SINR 选择策略 / Max-SINR selection  
   - 相干合并策略 / Coherent combining  
   - 非相干合并策略 / Non-coherent combining  
