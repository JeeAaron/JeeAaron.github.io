功能	开源首选方案	基本原理核心
变脸	DeepFaceLab (追求质量) / InsightFace Swapper (追求便捷)	身份特征与属性特征解耦与融合。GAN或扩散模型负责将源身份与目标姿态/光照结合。
换装	Outfit Anyone (最新SOTA) / VITON-HD (经典研究)	几何变形 + 纹理迁移。先保证服装与人体的几何对齐（变形），再保证纹理细节的真实性（生成/增强）。
动作模仿	Animate Anyone / MagicAnimate	条件扩散 + 时序建模。用姿态序列作为空间控制条件，用注意力机制等保证时间连贯性，让参考图像“动起来”。
