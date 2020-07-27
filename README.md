# CCL2020-Humor-Computation

CCL2020，“小牛杯”幽默计算任务数据发布

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

