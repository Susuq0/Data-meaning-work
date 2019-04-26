wine数据集说明
数据源：winemag-data_first 150 k.csv，包含10个属性和150K行有关葡萄酒评论的数据

country：葡萄酒来自哪个国家
description：对于葡萄酒的详细描述
designation：酒庄内的葡萄园，就是酿制葡萄酒的葡萄的产地
points：葡萄酒的评分为1-100分(然而他们说他们只对得分>=80分的葡萄酒进行评论)。
price：一瓶酒的价格
province：产酒的省或州
region_1：一个省或州的葡萄酒产地(纳帕)
region_2：有时在葡萄酒种植区(如纳帕谷内的卢瑟福)有更多的特定区域，但这个值有时是空白的。
variety：用来酿制葡萄酒的葡萄(黑比诺)
winery：酿制酒的酒厂


mlb_pitch数据集说明
数据源：atbats.csv，来自2015-2018年MLB常规赛期间每投一球的球场级别数据，包含10个属性和740k行的数据

ab_id：at-bat ID.前四位是年份
batter_id：击球手的球员编号，由MLB提供
event：击球结果的描述
g_id：游戏ID，前四位数字是年份
inning：局数
o：在这个打击后出局的次数
p_score：为投手队得分
p_throws：哪个投手投球，单个字符，R或L
pitcher_id：投手的球员编号，由MLB提供
stand：哪边击球手击球了，单个字符，R或L
top：如果是在上半局为真，如果是在下半局为假