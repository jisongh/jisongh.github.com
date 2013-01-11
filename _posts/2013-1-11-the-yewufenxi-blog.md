---
layout : post
category : lessons
tags : [开始]
title : [业务分析]
---

<div class="basetop"><a href="#" onclick="expandAll(document.getElementById('base'))">Expand</a> -
<a href="#" onclick="collapseAll(document.getElementById('base'))">Collapse</a></div><div id="base" class="basetext"><ul>
	<li class="col" id="FMID_704877707FM"><div class="nodecontent" style="color:#000000;font-size:167%;"><p>
      仓库库存管理系统
    </p><p>
      原库表结构交流会
    </p></div>
		<ul class="subexp">
	<li class="col" id="FMID_257378465FM"><div class="nodecontent" style="color:#0033ff;font-size:150%;">会议主题</div>
		<ul class="subexp">
	<li class="basic" id="FMID_745914107FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">WMS原库表结构交流会</div></li></ul></li>
	<li class="col" id="FMID_1214922968FM"><div class="nodecontent" style="color:#0033ff;font-size:150%;">会议时间</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1427606871FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">20121213</div></li>
	<li class="basic" id="FMID_317194161FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">9:30~10:45</div></li></ul></li>
	<li class="col" id="FMID_958554969FM"><div class="nodecontent" style="color:#0033ff;font-size:150%;">会议地点</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1553637373FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">隆巍会议室</div></li></ul></li>
	<li class="col" id="FMID_763639161FM"><div class="nodecontent" style="color:#0033ff;font-size:150%;">会议记录</div>
		<ul class="subexp">
	<li class="col" id="FMID_1771176485FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">会前疑问确认</div>
		<ul class="subexp">
	<li class="col" id="FMID_1243500664FM"><div class="nodecontent" style="color:#990000;font-size:117%;">周光甫</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1683676579FM"><div class="nodecontent" style="color:#111111;">问题一：仓库做损益会有2个表的数据变动，比如资源表记录是100吨，实际是99吨；损益表应该填写-1吨，资源表记录改为99吨。是这样吗？</div></li>
	<li class="basic" id="FMID_955947731FM"><div class="nodecontent" style="color:#111111;">问题二：仓库资源出库可以出库的最小单位数量和重量是多少？一个资源卡号是否可以拆开卖？如果可以拆开卖，拆开的原子数量、重量是多少？</div></li></ul></li>
	<li class="col" id="FMID_460904108FM"><div class="nodecontent" style="color:#990000;font-size:117%;">张军</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1131311909FM"><div class="nodecontent" style="color:#111111;">回答问题一：实际情况是和你所说的一致。</div></li>
	<li class="basic" id="FMID_1388300651FM"><div class="nodecontent" style="color:#111111;">回答问题二：出库的最小单位数量和重量会依据货物的特性确定，没有具体标准；这样一个资源卡号依据货物的特性可以拆开卖的，同样最小单位数量和重量没有标准确定。</div></li></ul></li></ul></li>
	<li class="col" id="FMID_417295400FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">库表结构疑问解答</div>
		<ul class="subexp">
	<li class="col" id="FMID_66859074FM"><div class="nodecontent" style="color:#990000;font-size:117%;">钱文豪、张军</div>
		<ul class="subexp">
	<li class="col" id="FMID_1259722330FM"><div class="nodecontent" style="color:#111111;">缩写</div>
		<ul class="subexp">
	<li class="col" id="FMID_492419909FM"><div class="nodecontent" style="color:#111111;">BC</div>
		<ul class="subexp">
	<li class="basic" id="FMID_334508666FM"><div class="nodecontent" style="color:#111111;">银行相关</div></li></ul></li>
	<li class="col" id="FMID_487662414FM"><div class="nodecontent" style="color:#111111;">BS</div>
		<ul class="subexp">
	<li class="basic" id="FMID_102954890FM"><div class="nodecontent" style="color:#111111;">基础信息(维护)</div></li></ul></li>
	<li class="col" id="FMID_301010877FM"><div class="nodecontent" style="color:#111111;">CF</div>
		<ul class="subexp">
	<li class="col" id="FMID_1537946022FM"><div class="nodecontent" style="color:#111111;">费用相关</div>
		<ul class="subexp">
	<li class="basic" id="FMID_656384595FM"><div class="nodecontent" style="color:#111111;">发票</div></li>
	<li class="basic" id="FMID_726216936FM"><div class="nodecontent" style="color:#111111;">财务</div></li></ul></li></ul></li>
	<li class="col" id="FMID_1650756356FM"><div class="nodecontent" style="color:#111111;">DA</div>
		<ul class="subexp">
	<li class="basic" id="FMID_276760188FM"><div class="nodecontent" style="color:#111111;">到货信息</div></li></ul></li>
	<li class="col" id="FMID_1522831489FM"><div class="nodecontent" style="color:#111111;">IN</div>
		<ul class="subexp">
	<li class="basic" id="FMID_942012610FM"><div class="nodecontent" style="color:#111111;">入库信息</div></li></ul></li>
	<li class="col" id="FMID_740846857FM"><div class="nodecontent" style="color:#111111;">OUT</div>
		<ul class="subexp">
	<li class="basic" id="FMID_392614219FM"><div class="nodecontent" style="color:#111111;">出库信息</div></li></ul></li>
	<li class="col" id="FMID_121920416FM"><div class="nodecontent" style="color:#111111;">SM</div>
		<ul class="subexp">
	<li class="col" id="FMID_1036391080FM"><div class="nodecontent" style="color:#111111;">移库表</div>
		<ul class="subexp">
	<li class="basic" id="FMID_944070001FM"><div class="nodecontent" style="color:#111111;">无效</div></li></ul></li></ul></li>
	<li class="col" id="FMID_1642796855FM"><div class="nodecontent" style="color:#111111;">SO</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1231034945FM"><div class="nodecontent" style="color:#111111;">特殊业务表</div></li></ul></li></ul></li>
	<li class="col" id="FMID_1385045032FM"><div class="nodecontent" style="color:#111111;">库表意义</div>
		<ul class="subexp">
	<li class="col" id="FMID_168076063FM"><div class="nodecontent" style="color:#111111;">Logon_key</div>
		<ul class="subexp">
	<li class="basic" id="FMID_71064817FM"><div class="nodecontent" style="color:#111111;">客户登录访问表</div></li></ul></li>
	<li class="col" id="FMID_910942079FM"><div class="nodecontent" style="color:#111111;">BC_BankControlDetailTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1352341213FM"><div class="nodecontent" style="color:#111111;">银行质押分类表</div></li></ul></li>
	<li class="col" id="FMID_1240774212FM"><div class="nodecontent" style="color:#111111;">BC_BankControlHisInfo</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1758978607FM"><div class="nodecontent" style="color:#111111;">银行质押删除后的表</div></li></ul></li>
	<li class="col" id="FMID_1677775846FM"><div class="nodecontent" style="color:#111111;">BC_BankControlTotalTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1688827750FM"><div class="nodecontent" style="color:#111111;">银行质押信息总表</div></li></ul></li>
	<li class="col" id="FMID_1627950046FM"><div class="nodecontent" style="color:#111111;">BD_RegTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1824336075FM"><div class="nodecontent" style="color:#111111;">日志信息表</div></li></ul></li>
	<li class="col" id="FMID_1721226042FM"><div class="nodecontent" style="color:#111111;">BS_AdjustReasonTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1266316170FM"><div class="nodecontent" style="color:#111111;">调整原因表</div></li></ul></li>
	<li class="basic" id="FMID_1985298835FM"><div class="nodecontent" style="color:#111111;">BS_BankTab银行表</div></li>
	<li class="col" id="FMID_995782759FM"><div class="nodecontent" style="color:#111111;">BS_BreedListTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1636690510FM"><div class="nodecontent" style="color:#111111;">品种表</div></li></ul></li>
	<li class="basic" id="FMID_268737695FM"><div class="nodecontent" style="color:#111111;">BS_ClientBadgetTab客户样章表</div></li>
	<li class="basic" id="FMID_1598383658FM"><div class="nodecontent" style="color:#111111;">BS_ClientChargeTab客户费用表</div></li>
	<li class="basic" id="FMID_251569251FM"><div class="nodecontent" style="color:#111111;">BS_ClientContractTab合同表</div></li>
	<li class="basic" id="FMID_1954141948FM"><div class="nodecontent" style="color:#111111;">BS_ClientGoodsFreeze品种冻结表</div></li>
	<li class="basic" id="FMID_1846143972FM"><div class="nodecontent" style="color:#111111;">BS_ClientTab客户表</div></li>
	<li class="basic" id="FMID_1494503047FM"><div class="nodecontent" style="color:#111111;">BS_CutMachineTab加工设备表</div></li>
	<li class="basic" id="FMID_1206850971FM"><div class="nodecontent" style="color:#111111;">BS_DatabaseSet数据库设置表</div></li>
	<li class="basic" id="FMID_462427057FM"><div class="nodecontent" style="color:#111111;">BS_DepartmentTab岗位表</div></li>
	<li class="basic" id="FMID_594946518FM"><div class="nodecontent" style="color:#111111;">BS_DedpositPlaceTab货位表</div></li>
	<li class="basic" id="FMID_813410945FM"><div class="nodecontent" style="color:#111111;">BS_EmerageWayTab到货方式表</div></li>
	<li class="col" id="FMID_557411655FM"><div class="nodecontent" style="color:#111111;">BS_FeeName</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1980582831FM"><div class="nodecontent" style="color:#111111;">费用类型表</div></li></ul></li>
	<li class="basic" id="FMID_1316920475FM"><div class="nodecontent" style="color:#111111;">BS_FreightWayTab出货方式表</div></li>
	<li class="basic" id="FMID_1392210391FM"><div class="nodecontent" style="color:#111111;">BS_GoodsAttributeAddition品种规格单重表</div></li>
	<li class="basic" id="FMID_1802341028FM"><div class="nodecontent" style="color:#111111;">BS_GoodsAttributeTab品名规格材质表</div></li>
	<li class="basic" id="FMID_751519149FM"><div class="nodecontent" style="color:#111111;">BS_GoodsCutTab 物资加工表</div></li>
	<li class="col" id="FMID_1825896616FM"><div class="nodecontent" style="color:#111111;">BS_GoodsOuttrip品名超发表</div>
		<ul class="subexp">
	<li class="basic" id="FMID_36761814FM"><div class="nodecontent" style="color:#111111;">关联品种，设置超发限制</div></li></ul></li>
	<li class="col" id="FMID_530258952FM"><div class="nodecontent" style="color:#111111;">BS_MaterialTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1985165606FM"><div class="nodecontent" style="color:#111111;">材质表</div></li></ul></li>
	<li class="col" id="FMID_441877424FM"><div class="nodecontent" style="color:#111111;">BS_MeasurewayTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_513390193FM"><div class="nodecontent" style="color:#111111;">计量方式表</div></li></ul></li>
	<li class="basic" id="FMID_1043968291FM"><div class="nodecontent" style="color:#111111;">BS_PersonnelTab人员表</div></li>
	<li class="basic" id="FMID_1971731147FM"><div class="nodecontent" style="color:#111111;">BS_PopedomTab权限表</div></li>
	<li class="basic" id="FMID_1649976923FM"><div class="nodecontent" style="color:#111111;">BS_ProdareaTab产地表</div></li>
	<li class="col" id="FMID_1997389675FM"><div class="nodecontent" style="color:#111111;">CF_ChargetTable</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1099791198FM"><div class="nodecontent" style="color:#111111;">费用表</div></li></ul></li>
	<li class="basic" id="FMID_1719762453FM"><div class="nodecontent" style="color:#111111;">CF_InvoiceDetailTab发票明细表</div></li>
	<li class="basic" id="FMID_503741788FM"><div class="nodecontent" style="color:#111111;">CF_InvoiceTotalTab发票汇总表</div></li>
	<li class="col" id="FMID_334241730FM"><div class="nodecontent" style="color:#111111;">DA_DaoDetailTab</div>
		<ul class="subexp">
	<li class="basic" id="FMID_327172585FM"><div class="nodecontent" style="color:#111111;">到货明细表</div></li></ul></li>
	<li class="basic" id="FMID_804463315FM"><div class="nodecontent" style="color:#111111;">DA_DaoTotalTab到货汇总表</div></li>
	<li class="basic" id="FMID_254856150FM"><div class="nodecontent" style="color:#111111;">In_inAdjustTab入库调整表</div></li>
	<li class="basic" id="FMID_1486240074FM"><div class="nodecontent" style="color:#111111;">In_InDetailTab入库明细表</div></li>
	<li class="basic" id="FMID_568792482FM"><div class="nodecontent" style="color:#111111;">In_inFeeTab入库费用表</div></li>
	<li class="col" id="FMID_1874543025FM"><div class="nodecontent" style="color:#111111;">In_inStackTab入库码单表</div>
		<ul class="subexp">
	<li class="basic" id="FMID_350057127FM"><div class="nodecontent" style="color:#111111;">板材</div></li>
	<li class="basic" id="FMID_1982022877FM"><div class="nodecontent" style="color:#111111;">货物堆码（？）</div></li>
	<li class="basic" id="FMID_1691568335FM"><div class="nodecontent" style="color:#111111;">货物的存放库位？</div></li></ul></li>
	<li class="basic" id="FMID_963332679FM"><div class="nodecontent" style="color:#111111;">In_inTotalTab入库总表</div></li>
	<li class="basic" id="FMID_308836514FM"><div class="nodecontent" style="color:#111111;">OUT_OUTFeeTab出库费用表</div></li>
	<li class="basic" id="FMID_906612957FM"><div class="nodecontent" style="color:#111111;">OUT_OutDetailTab出库明细表</div></li>
	<li class="basic" id="FMID_1304721620FM"><div class="nodecontent" style="color:#111111;">OUT_OutStackDetailTab出库码单明细表</div></li>
	<li class="basic" id="FMID_33773009FM"><div class="nodecontent" style="color:#111111;">OUT_OutStackTotalTab出库码单总表</div></li>
	<li class="basic" id="FMID_546065895FM"><div class="nodecontent" style="color:#111111;">OUT_outTotalTab出库总表</div></li>
	<li class="basic" id="FMID_357165212FM"><div class="nodecontent" style="color:#111111;">SM_RemoveTable移库表</div></li>
	<li class="basic" id="FMID_1322990117FM"><div class="nodecontent" style="color:#111111;">SO_BillLossTab提单挂失表</div></li>
	<li class="basic" id="FMID_1904303322FM"><div class="nodecontent" style="color:#111111;">SO_InputSet入库统计格式表（报表界面显示控制）</div></li>
	<li class="basic" id="FMID_1587693028FM"><div class="nodecontent" style="color:#111111;">SO_LossforGraneTab吊装设备状态记录表（损坏）</div></li>
	<li class="col" id="FMID_1789415807FM"><div class="nodecontent" style="color:#111111;">SO_OutSet</div>
		<ul class="subexp">
	<li class="basic" id="FMID_138576693FM"><div class="nodecontent" style="color:#111111;">出库统计格式表</div></li></ul></li>
	<li class="col" id="FMID_1774841954FM"><div class="nodecontent" style="color:#111111;">SO_StoreDetail</div>
		<ul class="subexp">
	<li class="basic" id="FMID_1082965490FM"><div class="nodecontent" style="color:#111111;">库存明细表</div></li></ul></li></ul></li></ul></li></ul></li></ul></li>
	<li class="col" id="FMID_12846562FM"><div class="nodecontent" style="color:#0033ff;font-size:150%;">与会人员</div>
		<ul class="subexp">
	<li class="basic" id="FMID_250065945FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">张军</div></li>
	<li class="basic" id="FMID_334165629FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">钱文豪</div></li>
	<li class="basic" id="FMID_1704242957FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">吴章强</div></li>
	<li class="basic" id="FMID_1443784224FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">周光甫</div></li></ul></li>
	<li class="col" id="FMID_94339744FM"><div class="nodecontent" style="color:#0033ff;font-size:150%;">会议决议</div>
		<ul class="subexp">
	<li class="basic" id="FMID_669968588FM"><div class="nodecontent" style="color:#00b439;font-size:133%;">参见会议纪要</div></li></ul></li></ul></li></ul></div>