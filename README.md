# myQA
知识库问答系统

使用nlpcc 中文知识库
目前使用sqlite存储知识库

涉及

实体查询

分词

词性标注

命名实体识别

候选答案生成

答案排名

问答样例如下

1.

question:

可口可乐公司的总部

('可口可乐公司', '总部所在地', '美国佐治亚州亚特兰大', 0.9228786528110504)

('可口可乐公司', '总部地点', '美国亚特兰大', 0.9036357402801514)

('可口可乐公司', '公司名称', '可口可乐公司', 0.7027411013841629)

('可口可乐公司', '公司口号', '我们血管流的不是血，而是可口可乐。', 0.685183584690094)

('可口可乐公司', '首席执行官', 'Muhtar Kent', 0.6813816726207733)

2.

question:

百度公司的成立时间

('百度公司', '创建时间', '2000年1月', 0.9196667075157166)

('百度公司', '公司口号', '百度一下，你就知道', 0.8491597473621368)

('百度公司', '产品服务', '中文搜索引擎', 0.821622222661972)

('百度公司', '法人代表', '李彦宏', 0.8163981139659882)

('百度公司', '创建地点', '北京中关村', 0.7995074689388275)

3.

question:

杭州有什么旅游景点

('杭州', '著名景点', '西湖、西溪国家湿地公园、千岛湖、灵隐寺、河坊街、雷峰塔等', 0.7894240617752075)

('杭州', '市树、市花', '香樟、桂花', 0.691900834441185)

('杭州', '地理位置', '浙江省北部\xa0钱塘江下游，京杭大运河南端', 0.6776783466339111)

('杭州', '著名高等学府', '浙大/浙工大/中国美院等[7]', 0.6712144911289215)

('杭州', '火车站', '杭州站、杭州东站、杭州南站等', 0.6686091125011444)

4.
question:

太原理工大学的校歌是什么

('太原理工大学', '校歌', '《圣火在百年前点燃》', 0.9298478066921234)

('太原理工大学', '学校地址', '山西省太原市迎泽西大街79号（迎西校区）', 0.8612709641456604)

('太原理工大学', '校训', '求实、创新', 0.8138610124588013)

('太原理工大学', '校址', '山西省太原市迎泽西大街79号', 0.8073568642139435)

('太原理工大学', '学校前身', '山西大学堂西学专斋', 0.7971555888652802)
