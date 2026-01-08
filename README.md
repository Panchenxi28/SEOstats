# AlphaPlatform具身智能仿真平台

## 简介
**基于自研引擎的场景渲染、物理仿真、训练可视化一体式仿真平台**

AlphaPlatform聚焦具身智能的真实感仿真与训练，支持实时渲染、动力学求解与训练闭环的完整流程。

## 特性

#### 高质量实时渲染引擎
- 实时动态响应：支持机器人模型运动轨迹的实时可视化
- 基于物理真实渲染：基于PBR渲染技术，准确模拟光照、材质、阴影效果

#### 高精度物理仿真引擎
- 多体动力学解算：采用递归牛顿-欧拉算法与复合刚体算法，高效处理机器人系统
- 驱动与感知：支持力矩、位置、速度控制执行器系统与触觉、加速度计、陀螺仪、关节编码器等传感器


## 功能场景

#### （1）支持机器人类型：人型/四足/轮式/机械臂/灵巧手

<table align="left">
  <thead>
    <tr>
      <th>G1</th>
      <th>H1</th>
      <th>Go2w</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="img/g1.png" width="240" alt="G1"></td>
      <td><img src="img/h1.png" width="240" alt="H1"></td>
      <td><img src="img/go2.png" width="240" alt="Go2w"></td>
    </tr>
  </tbody>
</table>

<table align="right">
  <thead>
    <tr>
      <th>Franka_Emika_Panda</th>
      <th>XHand</th>
      <th>R1_pro</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="img/franka+panda.png" width="240" alt="Franka Panda"></td>
      <td><img src="img/xhand.png" width="240" alt="XHand"></td>
      <td><img src="img/r1_pro.png" width="240" alt="R1_pro"></td>
    </tr>
  </tbody>
</table>

#### （2）支持RGB，深度，实例分割相机数据获取
<table align="right">
  <thead>
    <tr>
      <th>RGB</th>
      <th>Depth</th>
      <th>Segmentation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="img/RGB.png" width="250" alt="RGB"></td>
      <td><img src="img/depth.png" width="250" alt="Depth"></td>
      <td><img src="img/segmentation.png" width="250" alt="Seg"></td>
    </tr>
  </tbody>
</table>