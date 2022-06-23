---  
layout: archive-taxonomies  
tags: ProFOLD Biology
categories: SummerVacation2022  
---  
<head>  
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>  
    <script type="text/x-mathjax-config">  
        MathJax.Hub.Config({  
            tex2jax: {  
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],  
            inlineMath: [['$','$']]  
            }  
        });  
    </script>  
</head>   
  
  
# 暑假实习学习笔记——蛋白质基础知识与常用工具的学习  

  
## 蛋白质基础知识 

### 肽键  
肽键作为一种酰胺键，一般使用羰基C和酰胺N之间的单键表示。肽链中的每一个酰胺基都是一个肽基（peptide group）或者是肽单位（peptide unit）。  
肽键有一部分双键的性质，其键长短于一个典型的单键，但是长于一个典型的双键。  
肽键具有的双键的性质是由酰胺N上的孤对电子与相邻的羰基之间发生共振作用造成的。   
>_注（酰胺）：_ 指的是羧酸中的羟基被氨基或胺基取代的有机物。在构造上，酰胺可看作是羧酸分子中羧基的羟基被氨基或烃氨基（-NHR或-NR2）取代而成的化合物；也可看作是氨或胺分子中氮原子上的氢被酰基取代而成的化合物。  

**肽键中与肽键相关的6个原子共处于一个平面，这个平面结构称为肽平面（peptide plane）或酰胺平面（amide plane）。**    


在一个肽平面上，有两个和C$\alpha$有关系的单键，这两个单键可以自由旋转，因此每一个肽平面都有两个可以旋转的角度：（1）由C$\alpha$-N单键旋转的角度称为$\varphi$。（2）C$\alpha$-C单键旋转的角度称为$\psi$。与同一个C$\alpha$有关的一对$\varphi$和$\psi$称为蛋白质的二面角。很容易看出，一条肽链上的所有二面角都被确定之后，这一条肽链的三维结构也就基本确定了。  

**定义：** 如果肽链处于完全伸展状态（所有的肽链位于同一个平面上），$\varphi$和$\psi$定为+180',如果$\varphi$的旋转单键C$\alpha$-N1的两侧的N1-C1和C$\alpha$-C2呈顺式时，就规定$\varphi$=0‘；如果$\psi$的旋转键C$\alpha$-C2两侧的C$\alpha$-N1和C2-N2呈顺式时，则规定$\psi$=0’；从C$\alpha$向N1观察，顺时针旋转C$\alpha$-N1键得到的$\varphi$角为正值，反之为负值；从C$\alpha$向C2观察，顺时针旋转C$\alpha$-C2键得到的$\psi$角为正值，反之为负值。  

![pic:peptide:1](https://github.com/zyhacquaintance/zyhacquaintance.github.io/blob/main/images/2022-06-22/peptide-bond-1.png?raw=true)  

![pic:peptide:2](https://github.com/zyhacquaintance/zyhacquaintance.github.io/blob/main/images/2022-06-22/peptide-bond-2.png?raw=true)  
  
#### 肽平面的旋转  
+ 肽键不能旋转，但是与$\alpha$碳链相连的两个键是单键，因此可以自由旋转。  
+ 围绕C-C$\alpha$单键旋转的角称为$\psi$。
+ 围绕N-C$\alpha$单键旋转的角称为$\varphi$，如果所有的残基（$\varphi$,$\psi$）已知，那么由他们构成的肽链的主链结构也就知道了。（残基：在生物化学与分子化学里，是指一个聚合物中，如多糖、蛋白质或核酸上的某个特定单元。）
+ 由于侧链之间的某些空间位阻，事实上某些$\varphi$和$\psi$是不允许的。


![pic:peptide:3](https://github.com/zyhacquaintance/zyhacquaintance.github.io/blob/main/images/2022-06-22/peptide-bond-3.png?raw=true)  
  
（源自：<https://qinqianshan.com/biology/protein/peptide-bond/>)


### 二面角与肽链的高级结构   
**蛋白质的构象（conformation）：**也称为蛋白质的空间结构或高级结构，主要是指蛋白质分子中原子和基团在三维空间上的排列、分布以及肽链走向。  

**蛋白质的构型（configuration）**指的是分子中各个原子或者基团在空间中的排列方式。 
构型的改变必须通过共价键的断裂，而构象的改变不涉及共价键的改变。构象的变化是由于分子中单键的旋转，从而形成不同的立体结构。蛋白质的一级结构主要是指氨基酸序列；二级结构包含局部残基之间由氢键所调节的相互作用。最普遍的二级结构就是α螺旋及β折叠；三级结构在生物化学里指蛋白质整体几何形状，亦称为其折叠，蛋白质的三级结构是由其原子坐标定义的；四级结构是指多个多肽链的组装，主要是指是指蛋白质亚基相对于彼此的数目和排列。


上述两个$\psi$和$\varphi$被称为二面角，这个二面角并不是两个肽片面的夹角，具体的二面角仅仅只是指这两个角的度数，与数学上的二面角区分，这里的二面角主要是为了表示两个肽平面各自绕相应的单键旋转的角度。在这里二面角的度数的取值相比较于数学上的二面角，范围要相对大一些（取值为正负180‘，但是在实际上由于空间位阻的存在，能够取值的范围是很小的） 


（源自：<https://zhuanlan.zhihu.com/p/66129793>）




### 蛋白质的四级结构  
#### 蛋白质的一级结构  
是蛋白质的共价（肽键）结构，是由其编码的基因的核苷序列的序列决定，也是遗传信息的一种形式。  
肽键的结构与性质：  
+ 具有部分双链的性质，介于一个典型的单键和一个典型的双键之间。
+ 因为具有双键的一部分性质，所以肽键不能自由旋转，与肽键相关的六个原子共处于一个平面，这个平面结构被称为酰胺平面或者是肽平面。
+ 与C$\alpha$相连的两个单键可以自由旋转，因此产生上面所说的两个旋转角。
+ 多为反式异构，但是X-Pro是例外。
+ N带一部分正电荷，O带一部分负电荷。  

#### 蛋白质的二级结构  
前四种二级结构具有规律，反映在[拉氏图](https://zh.wikipedia.org/wiki/%E6%8B%89%E6%B0%8F%E5%9B%BE)上面具有相对固定的二面角。    
+ $\alpha$螺旋：肽链骨架围绕一个轴以螺旋的方式伸展，其螺旋的形成是自发的，$\alpha$螺旋有左手和右手之分，但是蛋白质中的$\alpha$螺旋主要是右手螺旋。氨基酸的残基R基团位于螺旋的外侧，并不参与螺旋的形成，但是其大小、形状和带点状态都能够影响螺旋的形成和稳定。  
+ $\beta$-折叠：肽段几乎是完全伸展，呈现平行排列，肽平面之间呈锯齿状，相邻肽段之间的肽键形成氢键，其中的每一股肽段被称为$\beta$-股。侧链基团垂直于相邻两个肽平面的交线，并且交替分布在折叠片层的两侧。  
+ $\beta$-转角:由肽链上四个连续的氨基酸残基组成，肽链骨架以180’回折而改变了肽链的方向，有利于反平行$\beta$-折叠的形成，其主要是因为$\beta$-转角改变了肽链的走向，促进相邻的肽段各自作为$\beta$-股，形成$\beta$-折叠。  
+ $\beta$-突起:由于$\beta$-折叠的一个$\beta$-股中额外插入一个氨基酸残基，使得原来连续的氢键结构被打破，从而使得肽链产生一种弯曲突起结构。主要发现于反平行$\beta$-折叠当中，也可以轻微地改变多肽链地走向。
+ 环（loop）和无规则卷曲：主要指一种无定规律的结构，主要指那些不能被归入明确的二级结构，但是本身又具有一定的稳定性，这些部位一般是蛋白质分子中功能实施和构象变化的重要区域。  


结构域：是指在二级结构或者超二级结构基础上形成的三级结构的局部折叠区，是相对独立的紧密球状实体。  

#### 蛋白质的三级结构
三级结构是指多肽链在二级结构的基础上，进一步盘绕、卷曲和折叠，形成主要是通过氨基酸侧链以[次级键](https://baike.baidu.com/item/%E6%AC%A1%E7%B4%9A%E9%8D%B5/10413614)（有时也会有二硫键和金属配位键）维系的完整的三维结构。三级结构通常由[模体](https://baike.baidu.com/item/%E6%A8%A1%E9%AB%94/984988)(motif)和[结构域](https://zh.wikipedia.org/wiki/%E8%9B%8B%E7%99%BD%E8%B4%A8%E7%BB%93%E6%9E%84%E5%9F%9F)(domain)组成。稳定的三级结构主要包括氢键、疏水键、离子键和范德华力。  

![pic:protein:3th](https://github.com/zyhacquaintance/zyhacquaintance.github.io/blob/main/images/2022-06-22/pic_protein_3.jpg?raw=true)




(源自：<https://zhuanlan.zhihu.com/p/432300831>, <https://zhuanlan.zhihu.com/p/451261927>)








## 蛋白质相关数据的计算  

### 二面角  

### 键长&键角  



## 常用工具的学习

