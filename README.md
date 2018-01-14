# javaiot简介
Javaiot是支持Http、CoAP、MQTT、MQTT-SN、Modbus,BACNet等物联网协议,专为物联网设计的高性能并发服务器。 <br/>

## javaiot架构
- 服务端 

   - 多协议支持组件 <br/>
   - 发布/订阅等微服务组件 <br/>
   - 消息存储组件 <br/>
   - 可视化显示组件 <br/>
   - 配置、监控组件 <br/>
- 设备端

   - 嵌入式SDK（支持NB-IoT、Zigbee、LoRa、WirelessHart、蓝牙等）

##  主要功能
- 支持多种物联网通讯协议 (HTTP, MQTT, WebSocket, CoAP, MQTT-SN、Modbus,BACNet等)
- 支持发布/订阅（Pub/Sub）和点对点（P2P）消息模型 
- 支持多种服务标准 (OPC-UA，OCF等)
- 支持时间敏感网络（TSN）和QoS
- 线性可伸缩数据存储能力
- 分布式高可用的集群部署架构
- 基于D3.js演进的可视化界面
- 提供配置、指标和监控等功能丰富的 Dashboard 
- 提供 docker 镜像用于隔离测试和云集群部署

##  安全特性
- 防火墙
- 访问控制，认证，授权和数据保护服务（例如验证代码完整性和数据加密）
- 使用区块链技术来跟踪/监测传感器数据
- 静态加密敏感数据
- 安全的服务间通信（HTTPS）
- 设备的白名单
- 监视和维护第三方组件的安全补丁
