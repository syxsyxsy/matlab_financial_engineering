# 实验报告

## 专业:金融工程

## 应用：

### 金融衍生品计算

#### 现金流(cash flow)

#### 债券工具(Bond instrument)

#### 债券期权(Bond option)

#### 固定收益票据(Fixed-rate note instrument)

#### 帽子期权(Cap instrument)

#### 地板期权(Floor instrument)

#### 利率互换(Swap instrument)

### 金融数据可视化

#### G上港(600018)2006年4月7日至5月22日收盘价做出股价图，然后更改坐标。

1. % plot times.m

2. load qq

3. plot(a1(:,2),'r*','markersize',6);

4. hold on;

5. plot(a1(:,2))

6. axis([1 27 10,14])

7. xlabel('时间');

8. ylabel('股价');

9. title('G上港2006年4月7日－5月22日股价图','Color','r')

10. set(gca,'XTick',[1,5,10,15,20,25,30]);% 标出x轴刻度位置

11. set(gca,'XTickLabel',{'06-04-07';'06-04-13';

    ```
      '06-04-20';'06-04-27';...'06-05-11';
       '06-05-18';'06-05-25'});% 更改图像x轴坐标刻度。
    ```

12. grid on;  % 为图像背景添加网格线。grid off可以 消除图像中  
       的网格线

