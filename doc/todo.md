


已解决
2.处方模板和营养干预的，数字类的填写，都是>0的正整数            ✅
4.新增商品，数字类限定：输入框的，价格是精确到0.01，单位关系是整数，后面的能量那些，精确到0.1     ✅
5.输入身份证，自动出来性别、年龄；数字输入限定【全正整数】        ✅ 【patientBasicInfo.vue】
7.患者首页这里，默认显示第一个吧，这样页面就不空了              ✅
如果没有病人，显示暂无病人信息                                ✅
8.病人信息做成选项卡的样子                                  ✅
9.筛查等个别页面的table不要滚动条                            ✅   
10.新增病人必填页面、前端验证                                ✅
13.营养干预的周期（天）限定？目前正整数 默认1天                  ✅
15.病人选项卡间距                                          ✅6px
16.用餐时间     用餐内容      用量                           ✅
17.处方营养干预和处方模板，温水放在操作后面                     ✅
18.首页按图做                                              ✅                              
6.下拉icon【suffixIcon】                                ✅✅✅✅✅✅✅️别问了，都改了！！！
20.膳食营养计划模板+能量                                      ✅   
1.营养干预备注                                                ✅   
3.historyList样式问题                                       ✅
12.抛出接口异常                                               ✅   
19.windows系统滚动条                                         ✅已解决


   
其他、延期：
14.操作类型的不滚动，仅列表滚动                       ⚠️延期
21.营养干预膳食营养计划+能量                       ⚠️延期
问题：
1.膳食模板的用量，只能是数字？            ⚠️不能，但是服务端实体数据格式暂时不支持
2.根据医院查询营养师列表，把这个医院下所有的医生都查出来了
/api/patient/selectNutritionByHospital/{hospitalId}
method:get
接口文档：
http://49.232.14.93:8080/doc.html#/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86/%E7%97%85%E4%BA%BA%E4%BF%A1%E6%81%AF/selectNutritionByHospitalUsingGET
3.上述已解决的4，但是木木的只支持整数