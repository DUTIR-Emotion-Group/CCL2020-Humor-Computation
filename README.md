# CCL2020-Humor-Computation

CCL2020，“小牛杯”幽默计算任务数据发布

**Update：测试集标签已发布**

任务说明参见CCL2020官方网站：http://cips-cl.org/static/CCL2020/humorcomputation.html

任务每个阶段的排名在该项目公布。

* 任务第一阶段持续10周（2020.6.15-2020.8.23）

在第一阶段，发布训练集和不带标签的开发集。

在第一阶段的每个周末，每个参赛队伍有一次提交开发集结果的机会，每周的结果排名会此处公布。

提交方式：

参赛队伍需要将包含结果文件的邮件发送至邮箱humorcomputing@163.com，邮件的标题为“CCL2020-参赛队名”，邮件附件为结果文件。

**中英文数据结果各自形成一个csv文件，命名格式为："en\_参赛队名.csv"和"cn\_参赛队名.csv"（分别对应英文测试集结果和中文测试集结果）**

csv文件以无BOM的utf-8格式编码，分隔符使用逗号“,”，每行结尾的换行符为“\n"。需要包含测试集ID和预测的Lable，参照"answer_example.csv"文件。

* 任务第二阶段持续1周（2020.8.24-2020.8.30）

在第二阶段，发布测试集数据。

参赛队伍需在最终截止日期前提交完整测试集结果，每个队伍仅有一次提交机会。组织方将根据完整测试集上的得分对参赛队伍进行排名，同时该排名结果将会在**CCL2020**官方网站公布。

最终结果排名以第二阶段的测试集结果为准，第一阶段成绩不作为最终成绩，仅为参赛队伍迭代模型提供参考。

提交方式与第一阶段提交方式相同，**每个队伍只有一次机会提交最终结果。**

### 第一阶段第一周结果

第一阶段第一周（6.15-6.21）接收到验证集结果提交2份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第一周排名：

| 参赛队名    | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分 |
| ----------- | -------- | ------- | -------- | ------- | ---- |
| 我们都队    | 0.457    | 0.700   | 0.417    | 0.722   | 2.30 |
| cn_mAI@pumc | 0.466    | 0.742   | /        | /       | /    |

### 第一阶段第二周结果

第一阶段第二周（6.22-6.28）接收到验证集结果提交8份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第二周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| Walking Dad  | 0.507    | 0.739   | 0.489    | 0.755   | 2.490 |
| BERT 4EVER   | 0.517    | 0.719   | 0.463    | 0.744   | 2.443 |
| 哈哈哈       | 0.444    | 0.701   | 0.472    | 0.770   | 2.387 |
| mAI@pumc     | 0.462    | 0.736   | 0.410    | 0.745   | 2.345 |
| 我们都队     | 0.458    | 0.710   | 0.447    | 0.718   | 2.331 |
| LastDance    | 0.472    | 0.691   | 0.502    | 0.621   | 2.286 |
| will         | 0.000    | 0.749   | 0.324    | 0.728   | 1.802 |
| 好未来_AI_ML | 0.477    | 0.726   | \        | \       | \     |

### 第一阶段第三周结果

第一阶段第三周（6.29-7.05）接收到验证集结果提交8份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第三周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| LastDance    | 0.489    | 0.717   | 0.571    | 0.784   | 2.560 |
| 好未来_AI_ML | 0.484    | 0.739   | 0.500    | 0.745   | 2.468 |
| 哈哈哈       | 0.511    | 0.711   | 0.463    | 0.751   | 2.437 |
| BERT 4EVER   | 0.515    | 0.721   | 0.451    | 0.738   | 2.425 |
| 我们都队     | 0.489    | 0.697   | 0.465    | 0.737   | 2.389 |
| Walking Dad  | 0.484    | 0.759   | 0.224    | 0.739   | 2.206 |
| will         | 0.397    | 0.731   | 0.301    | 0.734   | 2.164 |
| 第一次打比赛 | 0.091    | 0.755   | 0.399    | 0.299   | 1.544 |

### 第一阶段第四周结果

第一阶段第四周（7.06-7.12）接收到验证集结果提交7份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第四周排名：

| 参赛队名    | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ----------- | -------- | ------- | -------- | ------- | ----- |
| 我们都队    | 0.492    | 0.696   | 0.547    | 0.747   | 2.482 |
| Walking Dad | 0.520    | 0.685   | 0.515    | 0.745   | 2.466 |
| 哈哈哈      | 0.456    | 0.733   | 0.486    | 0.768   | 2.443 |
| BERT 4EVER  | 0.468    | 0.727   | 0.467    | 0.754   | 2.416 |
| LastDance   | 0.450    | 0.722   | 0.513    | 0.707   | 2.392 |
| DUT93814    | 0.427    | 0.758   | 0.390    | 0.761   | 2.337 |
| mAI@pumc    | 0.273    | 0.600   | 0.252    | 0.605   | 1.730 |

### 第一阶段第五周结果

第一阶段第五周（7.13-7.19）接收到验证集结果提交10份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第五周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| LastDance    | 0.499    | 0.720   | 0.560    | 0.777   | 2.557 |
| 好未来_AI_ML | 0.521    | 0.704   | 0.520    | 0.768   | 2.512 |
| Walking Dad  | 0.516    | 0.684   | 0.516    | 0.749   | 2.465 |
| 我们都队     | 0.500    | 0.682   | 0.522    | 0.744   | 2.448 |
| BERT 4EVER   | 0.513    | 0.706   | 0.441    | 0.747   | 2.406 |
| 哈哈哈       | 0.480    | 0.666   | 0.407    | 0.764   | 2.317 |
| DUT93814     | 0.401    | 0.745   | 0.377    | 0.750   | 2.274 |
| will         | 0.265    | 0.610   | 0.215    | 0.643   | 1.733 |
| 111          | /        | /       | 0.443    | 0.736   | /     |
| 暗裔剑魔     | 0.414    | 0.751   | /        | /       | /     |

### 第一阶段第六周结果

第一阶段第六周（7.20-7.26）接收到验证集结果提交8份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第六周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| 我们都队     | 0.527    | 0.711   | 0.549    | 0.754   | 2.541 |
| 好未来_AI_ML | 0.503    | 0.723   | 0.524    | 0.752   | 2.502 |
| Walking Dad  | 0.506    | 0.697   | 0.536    | 0.761   | 2.499 |
| LastDance    | 0.473    | 0.749   | 0.496    | 0.748   | 2.466 |
| DUT93814     | 0.499    | 0.748   | 0.462    | 0.755   | 2.463 |
| BERT 4EVER   | 0.518    | 0.726   | 0.394    | 0.760   | 2.390 |
| will         | 0.026    | 0.735   | 0.030    | 0.721   | 1.512 |
| 111          | /        | /       | 0.474    | 0.745   | /     |

### 第一阶段第七周结果

第一阶段第七周（7.27-8.02）接收到验证集结果提交9份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第七周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| 我们都队     | 0.495    | 0.685   | 0.578    | 0.760   | 2.519 |
| 好未来_AI_ML | 0.503    | 0.723   | 0.520    | 0.768   | 2.515 |
| LastDance    | 0.481    | 0.738   | 0.530    | 0.763   | 2.512 |
| Walking Dad  | 0.495    | 0.725   | 0.526    | 0.759   | 2.505 |
| DUT93814     | 0.499    | 0.748   | 0.479    | 0.759   | 2.484 |
| BERT 4EVER   | 0.515    | 0.722   | 0.505    | 0.738   | 2.480 |
| 哈哈哈       | 0.487    | 0.645   | 0.423    | 0.769   | 2.324 |
| will         | 0.373    | 0.709   | 0.362    | 0.715   | 2.159 |
| 111          | /        | /       | 0.460    | 0.740   | /     |

### 第一阶段第八周结果

第一阶段第八周（8.03-8.09）接收到验证集结果提交11份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第八周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| LastDance    | 0.505    | 0.694   | 0.544    | 0.772   | 2.515 |
| 我们都队     | 0.503    | 0.700   | 0.556    | 0.752   | 2.511 |
| 111          | 0.473    | 0.725   | 0.528    | 0.741   | 2.468 |
| BERT 4EVER   | 0.516    | 0.727   | 0.449    | 0.758   | 2.451 |
| 好未来_AI_ML | 0.495    | 0.719   | 0.471    | 0.756   | 2.441 |
| cc           | 0.451    | 0.738   | 0.452    | 0.744   | 2.385 |
| 哈哈哈       | 0.469    | 0.696   | 0.458    | 0.737   | 2.360 |
| qingbo       | 0.465    | 0.726   | 0.416    | 0.723   | 2.330 |
| GO           | 0.438    | 0.734   | 0.314    | 0.718   | 2.203 |
| will         | 0.371    | 0.729   | 0.347    | 0.523   | 1.969 |
| DUT93814     | /        | /       | 0.426    | 0.742   | /     |

### 第一阶段第九周结果

第一阶段第九周（8.10-8.16）接收到验证集结果提交14份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第九周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| LastDance    | 0.509    | 0.734   | 0.553    | 0.767   | 2.563 |
| Walking Dad  | 0.500    | 0.733   | 0.543    | 0.751   | 2.527 |
| 哈哈哈       | 0.507    | 0.717   | 0.531    | 0.764   | 2.519 |
| 我们都队     | 0.502    | 0.704   | 0.553    | 0.753   | 2.512 |
| qingbo       | 0.498    | 0.708   | 0.517    | 0.769   | 2.492 |
| 111          | 0.512    | 0.711   | 0.513    | 0.747   | 2.483 |
| 好未来_AI_ML | 0.493    | 0.731   | 0.491    | 0.747   | 2.462 |
| DUT93814     | 0.499    | 0.748   | 0.460    | 0.754   | 2.461 |
| BERT 4EVER   | 0.507    | 0.703   | 0.498    | 0.725   | 2.433 |
| will         | 0.438    | 0.736   | 0.443    | 0.713   | 2.330 |
| NLPers       | 0.440    | 0.745   | 0.384    | 0.734   | 2.302 |
| DUFL         | 0.358    | 0.731   | 0.375    | 0.732   | 2.196 |
| vimos        | 0.456    | 0.729   | 0.271    | 0.731   | 2.187 |
| 暗裔剑魔     | 0.414    | 0.751   | 0.312    | 0.603   | 2.080 |

### 第一阶段第十周结果

第一阶段第十周（8.17-8.23）接收到验证集结果提交18份，请参赛者将中文数据集结果和英文数据集结果分开提交，各自形成一个csv文件。

以下是第十周排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| qingbo       | 0.519    | 0.703   | 0.563    | 0.783   | 2.568 |
| 好未来_AI_ML | 0.503    | 0.723   | 0.553    | 0.767   | 2.546 |
| LastDance    | 0.487    | 0.733   | 0.532    | 0.772   | 2.525 |
| BERT 4EVER   | 0.509    | 0.724   | 0.519    | 0.764   | 2.516 |
| Walking Dad  | 0.494    | 0.721   | 0.544    | 0.752   | 2.511 |
| 哈哈哈       | 0.517    | 0.705   | 0.533    | 0.753   | 2.508 |
| 我们都队     | 0.503    | 0.708   | 0.535    | 0.757   | 2.503 |
| 哇哈哈哈哈   | 0.510    | 0.716   | 0.497    | 0.761   | 2.484 |
| 疾风剑豪     | 0.484    | 0.725   | 0.510    | 0.753   | 2.472 |
| 111          | 0.510    | 0.714   | 0.489    | 0.750   | 2.462 |
| DUT93814     | 0.499    | 0.748   | 0.407    | 0.738   | 2.392 |
| will         | 0.447    | 0.697   | 0.442    | 0.726   | 2.311 |
| 鹰眼一号     | 0.431    | 0.702   | 0.370    | 0.742   | 2.244 |
| DUFL         | 0.316    | 0.740   | 0.316    | 0.724   | 2.096 |
| vimos        | 0.456    | 0.729   | 0.274    | 0.580   | 2.039 |
| jxnu-thy     | 0.271    | 0.552   | 0.280    | 0.697   | 1.799 |
| uirers       | 0.000    | 0.749   | 0.000    | 0.728   | 1.477 |
| temp         | /        | /       | 0.478    | 0.754   | /     |

## 第二阶段现已开启

本次评测测试集数据现已发布，请参赛队伍**于2020年8月30日24时前**将中英文**测试集**的预测结果进行提交。

提交方式，文件格式，文件命名格式与第一阶段相同。

**每个队伍只有一次机会提交测试集结果**，请参赛队伍在提交前进行确认，谨慎提交。

测试集结果将成为本次评测成绩排名的最终依据。

### 第二阶段结果

以下是第二阶段测试集结果排名：

| 参赛队名     | 中文f1值 | 中文acc | 英文f1值 | 英文acc | 总分  |
| ------------ | -------- | ------- | -------- | ------- | ----- |
| 好未来_AI_ML | 0.541    | 0.720   | 0.586    | 0.783   | 2.629 |
| qingbo       | 0.527    | 0.718   | 0.576    | 0.778   | 2.599 |
| BERT 4EVER   | 0.504    | 0.707   | 0.555    | 0.772   | 2.538 |
| 哈哈哈       | 0.499    | 0.690   | 0.565    | 0.762   | 2.515 |
| 我们都队     | 0.483    | 0.676   | 0.567    | 0.764   | 2.490 |
| LastDance    | 0.483    | 0.707   | 0.527    | 0.763   | 2.479 |
| Walking Dad  | 0.484    | 0.716   | 0.533    | 0.736   | 2.469 |
| DUT93814     | 0.382    | 0.718   | 0.574    | 0.780   | 2.453 |
| will         | 0.443    | 0.678   | 0.458    | 0.744   | 2.323 |
| NLPers       | 0.446    | 0.710   | 0.401    | 0.740   | 2.296 |
| DUFL         | 0.344    | 0.694   | 0.311    | 0.686   | 2.035 |
| uirers       | 0.304    | 0.686   | 0.276    | 0.691   | 1.957 |
| 超凡         | 0.333    | 0.530   | 0.221    | 0.683   | 1.769 |
| jxnu-thy     | 0.193    | 0.645   | 0.198    | 0.648   | 1.685 |
| vimos        | 0.000    | 0.000   | 0.000    | 0.000   | 0.000 |

更多消息，请留意CCL2020官网。

