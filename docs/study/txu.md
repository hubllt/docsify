# 学习说明

## 读书



## 管理

## 其他



## T恤网站简单对比

###### 以下是十个网站定制1-3件T恤的收费起步价。

|网站 | 1件 | 2件 | 3件 |
| :-----| ----: | :----: | :----: |
| [Zazzle](https://www.zazzle.com)| 20.1 | 40.2 | 80.4 |
| [Allied Shirts](https://www.alliedshirts.com/) | 27.19 | 54.26 | 99.16 |




Money = Sarlary is a job work

![zheji](1.jpg)

![图片描述](image/1.jpg)

### 账号

本地wordpress

后台地址：http://localhost:8888/wp-admin/
用户名：yeheic
密码：H!s3x4#M&S(riBQlGb


# 折线图展示


### z-chart
z-chart组件是基于echarts的组件，只需要设置父容器的宽高，再设置 options 值即可。
<!-- markdown文档里插入vuep代码 -->

<vuep template="#basicBar"></vuep>
<script v-pre type="text/x-template" id="basicBar">
<template>
  <div style="width:100%; height:100%;">
    <z-chart :options="chartData" />
  </div>
</template>

<script>
 module.exports = {
    created () {
      this.chartData = {
          title: {
            text: "ECharts 入门示例"
          },
          tooltip: {},
          xAxis: {
            data: ["衬衫", "羊毛衫", "雪纺衫", "裤子", "高跟鞋", "袜子"]
          },
          yAxis: {},
          series: [
            {
              name: "销量",
              type: "bar",
              data: [5, 20, 36, 10, 10, 20]
            }
          ]
        }
    }
  }
</script>

> An awesome project.
