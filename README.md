# COVID-19-PREDICTION
本项目的目标是建立预测模型，该模型可根据新冠肺炎患者的当前症状、状态和病史，预测患者是否有可能面临死亡风险。
## 项目简介
COVID-19是由冠状病毒引起的传染病。大多数感染新冠肺炎病毒的人会出现轻度至中度呼吸道疾病，无需特殊治疗即可康复。然而，老年人和患有心血管疾病、糖尿病、慢性呼吸道疾病和癌症等潜在疾病的人患上新冠病毒肺炎后，症状较为严重，有死亡风险。在COVID-19流行的过程中，医疗资源短缺和如何有效分配医疗资源是医疗机构面临的主要问题之一。在医疗资源紧缺时期，及时且准确地预测患者未来是否有可能面临死亡风险，并根据预测结果进行医疗资源的合理分配，对缓解医疗资源压力、保障国民生命健康具有重要意义。
本项目的目标是建立预测模型，该模型可根据新冠肺炎患者的当前症状、状态和病史，预测患者是否有可能面临死亡风险。
数据集由墨西哥政府提供，链接为https://www.kaggle.com/datasets/meirnizri/covid19-dataset。
## 复现说明
运行环境：
python 3.7.0  
使用包的版本：
numpy 1.21.5  
pandas 1.1.5  
matplotlib 3.5.1  
seaborn 0.9.0  
sklearn 1.0.2  
imblearn 0.0  
复现步骤：  
1.数据查看、数据清洗和数据可视化直接运行代码即可；  
2.模型分析部分，需要通过验证曲线寻找最优参数值，再将参数值带入到最优模型中；  
3.模型分析部分未设置随机数种子，所以每次运行的结果不完全一致。
