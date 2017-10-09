
#列表页规则 

## 1.路径规则
http://www.domain.com/{zufang||ershoufang}/{行政区拼音||行政区拼音-商圈拼音}/tags 
http://www.domain.com/{ditiefang||ditiezufang}/li{地铁编号}s{站点编号}/tags 
## 2.参数解释 
### 1）
{ershoufang}-二手房按区域筛选   
eg：http://www.domain.com/ershoufang/ 
{zufang}-租房按区域筛选   
eg：http://www.domain.com/zufang/    
{ditiefang}-二手房安地铁筛选  
eg：http://www.domain.com/ditiefang/  
{ditiezufang}-租房安地铁筛选  
eg：http://www.domain.com/ditiezufang/  
### 2）
{行政区拼音} 
eg：http://www.domain.com/ershoufang/CYQ  
    二手房按区域筛选-朝阳区  
{行政区拼音-商圈拼音}  
eg：http://www.domain.com/ershoufang/CYQ-GM   
    二手房按区域筛选-朝阳区-国贸  
li{地铁编号}  
eg：http://www.domain.com/ditiefang/li123  
   二手房安地铁筛选-地铁线路ID为123  
li{地铁编号}s{站点编号}  
eg：http://www.domain.com/ditiefang/li123s456  
   二手房安地铁筛选-地铁线路ID为123-站点ID为456  
### 3）tags
s:售价  
a:面积  
f:房型  
g:地铁房  
v:随时看房 <br />
l:房本满5年         
k:降价          
bs:最低价格            
es:最高价格            
ba:最小面积            
ea:最大面积            
pg:分页            
rs:搜索关键词             
列表选项卡和排序             
热门房源：PA  
最新发布：P1   
房屋总价 (P3: ASC, P4: DESC)  
房屋单价 (P5: ASC, P6: DESC)  
房源面积 (P7: ASC, P8: DESC) 

其他请参考:http://statictest.koofang.com/ershoufang/pg1 
