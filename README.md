# 曹柏志_414join
# 1：自我介绍
大家好，我叫曹柏志，来自北京海淀。我是一个严谨认真，热爱生活的人。我的学习能力很强，在高中时期我作为共青团员，参加了许多团学和实践活动，这些经历让我积累了许多学习经验，同时我还自学了ps，剪映，au等软件，对修图，音频，视频剪辑有一定的基础。我吃苦耐劳，在高中时期我加入了国旗队，一次次的训练磨练了我的意志，让我能更冷静乐观的面对困难与挑战。我乐于助人，在学校期间，我积极帮助老师和同学解决问题，曾多次获得西城区三好学生奖项。
# 2：加入414的原因和想要学习到的知识
我想要加入414的原因很简单，就是因为对游戏的热爱。此次加入414也是为了完善自己的能力，我想往软件学习方面发展，我想学习更多和制作游戏有关的软件，提升自己的个人能力，最后通过我自己的努力实现制作游戏的梦想。我对场景制作，人物建模方面十分感兴趣，希望在加入414后可以学习3dmax，blender等相关软件。
# 3:图片
![4f12e453583495e38f0b3c3554c7267](https://github.com/Yozorawo/CaoBaiZhi_414join/assets/146621057/746475ea-ec28-44f0-a971-e6d4adf603ce)
# 2.1代码基础
## 一.什么是冒泡排序？
例如一组无序的数组，最左边就是水底，最右边就是水面，最左边的元素不断地跟右边的元素比较，最后交换位置到最右边，这就是冒泡排序。
## 二.基础案例
### -时间复杂度：O(n^2)
### -空间复杂度:O(1)
### Array.prototype.bubbleSort= function （) {
###       for (let i = 0; i < this.length - 1; i++) {               
###           for (let j = 0; j < this.length - 1 - i; j++) {           
###              if (this[j] > this[j + 1]) {
###                const temp = this[j]
###                this[j] = this[j + 1]
###                this[j + 1] = temp
###              }
###         ｝
###     }
### ｝
### const arr = [5, 4, 3, 2, 1]

### arr.bubbleSort() //[1, 2, 3, 4, 5]
### 代码中存在两个嵌套循环，所以时间复杂度O（n^2),而空间复杂度O（1），因为没有使用会随着数据增大而增大的变量。


# 2.2美工基础
![梦步见](https://github.com/Yozorawo/CaoBaiZhi_414join/assets/146621057/6ba480d5-6594-42b1-a0e1-cc7356d68d40)
## 一.设计思路
### 人物：这幅简笔画的人物是摇曳露营中的志摩凛，我用我自己的绘画风格表现出了她的特点。
### 背景：以蓝色调打底，代表着人物安静，冷淡的性格。
### 服装：棒球服加摇滚卫衣内衬，体现出了人物外冷内热的特点。

# 2.4.1策划能力
## 一.职业设定
### 1.理气 控制类角色，可以通过技能对敌人施加减速，眩晕等效果，同时展开卦象可以提高暴击率，但会持续消耗蓝条
### 2.引雷 群伤类角色，可以通过技能对敌人造成群体伤害，同时可以与火，水等元素融合发生元素反应（伤害增加）
### 3.药师 奶位辅位 可以通过技能缓慢回复友方生命，群体和个体回复取决于天赋加点。同时可以为友方提供buff（增伤，暴击提高等取决于天赋加点）平A可以为敌人施加debuff（易伤 减速等，也取决于天赋加点）
### 4.虫师 侵蚀伤害类角色，可以通过技能对敌人施加持续中毒效果，可以叠层数，大招可以结算层数伤害，配合药师暴击提高增伤天赋更强
### 5.禁卫 直伤肉盾类角色，拥有更高的平A直伤和护盾技能（根据加点分为群体护盾和个体护盾）但同时无法参与反应伤害，移动速度更慢
## 二.职业背景
### 1.虫隐之道
#### 虫师本身是处理由虫引发的问题或缓解人与虫的矛盾的人。他们受朝廷任命，云游四海，出入穷乡僻壤去追寻虫的足迹。每当虫与人的生活交汇时，虫师就会出现。世世代代，虫师治虫的传统都流传了下来，甚至在某种程度上与救死扶伤的药师无异。
#### 可是在王权更迭，民不聊生的战争中，虫师们失去了他们的容身之所…青年虫师被发配战场，老年虫师无法靠虫为生…虫师这个职业曾一度消失，终于，在藩镇割据的背景下，在有能力的虫师的带领下，专属于虫师的组织流云会诞生了，他们的使命依旧像从前一样云游四方，救死扶伤，追寻虫的痕迹，但是不一样的是，这一次他们是为了自己而战，是为了穷苦百姓而战，他们带领百姓建立了自己的营地，他们通过自己的手段虫，悄无声息的除掉了每一个阻碍他们行动的人。
### 2.流云会背景：安史之乱之前就已经建立的虫师组织，立志于帮助底层人民生存，用自己的力量暗中解决了许多腐败的地主和权贵，他们不属于任何一方势力。
### 3.虫师培养：虫师需要从小学习基础药草知识，同时通过虫师手册等熟练认识昆虫的形态特点和喜好，从而更好的培养虫子，制作虫药。从小生活在多虫的环境里，可以操控昆虫的行动。战斗时会将昆虫藏于衣袖中，以便于隐秘行动。







