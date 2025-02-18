# UAVanomaly
面向无人机视频的异常行为检测数据集

考虑到面向无人机视频感知预警的基准数据集较为稀缺，利用购买的无人机监控设备在河南大学金明校区采集了10个场景300个训练视频（约10万图像帧），60个测试视频（约2万图像帧），包含打斗、摔倒等异常事件，视频分辨率为720×480，数据采用事件级标注的模式，相比帧级别定位精度更高。目前已完成约6万张图像帧的数据标注工作，该数据集标注完成后会立即发布。

该数据集面向园区等开放复杂场景，包含群体和个体等多种异常事件。与其它数据集不同，该数据集属于开集数据集，即测试集中部分异常事件类型不包含在训练集中。数据类型更真实全面，包含无人机起飞、降落等动态复杂运动模式，以及弯腰系鞋带等易误判行为。该数据集具有数据量大、标注全面、类别多样等特点，弥补了现有数据集缺乏大场景、大数据量俯视视角的缺陷。
