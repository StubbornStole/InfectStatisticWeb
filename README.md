# InfectStatisticWeb

|作业链接|[结对第一次—疫情统计可视化（原型设计）](https://edu.cnblogs.com/campus/fzu/2020SPRINGS/homework/10460)|
|--    |--    |
|结对学号|221701121，221701124|
|项目介绍|疫情统计可视化的实现，采用web技术来实现先前原型中的功能，实现通过地图的形式来直观显示疫情的大致分布情况，还可以查看具体省份的疫情统计情况，点击某个省份则会显示该省疫情的具体情况|

##项目构建

&emsp;&emsp;采用纯web前端的方式对疫情统计可视化原型进行了实现，原型中的地图和表格都采用echarts进行实现，通过txt文件中的各个省份的数据，将其显示在是地图上和图表中。

##项目运行

&emsp;&emsp;打开网页即可运行，在全国地图上使用不同的颜色代表大概确诊人数区间颜色的深浅表示疫情的严重程度，可以直观了解高危区域
&emsp;&emsp;鼠标移到每个省份会高亮显示，点击鼠标会显示该省具体疫情情况，会有图表出现，该省份到目前为止的新增确诊趋势、新增疑似趋势、治愈趋势和死亡趋势；绘制该省份的趋势变化曲线图一共三张图表，直观的显示具体数据
&emsp;&emsp;通过选择具体的日期，显示到该日期为止的累计数据，包括对应的感染患者人数、疑似患者人数、治愈人数、死亡人数
&emsp;&emsp;点击疫情正能量即可进入共同抗疫相关文章，再点击文章进入具体网页。
&emsp;&emsp;点击防疫知识热搜即可进入防疫相关知识的文章，再点击文章进入具体网页。
