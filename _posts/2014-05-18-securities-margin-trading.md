---
layout: post
title: 融资融券业务的会计处理
comments: true
categories:
- investment
tags:
- 融资融券
- 会计处理
---

融资融券(securities margin trading)又称“证券信用交易”，是指投资者向具有上海证券交易所或深圳证券交易所会员资格的证券公司提供担保物，借入资金买入本所上市证券或借入本所上市证券并卖出的行为。从财务处理角度来看，这个行业的财务有其独有的特点，也就是说，在会计处理过程中，应有一套会计处理的优化思想。

1.融资融券业务的会计处理思路

对于融资业务的会计处理，证券公司将资金借给客户，形成一项应收债权，与银行贷款业务并无本质区别。因此，证券公司和客户根据银行贷款的业务做相似的会计处理即可。而对于融券业务的会计处理，证券公司由于仅是暂时性借出证券，在约定的期限之后，客户将归还证券公司相同数量和种类的证券，证券公司并没有真正转移借出证券的风险和报酬，因此，不应该终止确认该证券，但是为了反映该证券已被借出的事实，可以将证券的“自营账户”金额转移到“融券账户”，“融券账户”则按照以前相同的会计计量方法核算。对客户而言，因借入证券应确认“交易性金融资产”，同时因为承担金融负债的目的，主要是为了近期内回购，因此，在出售该证券期间可以相对应地确认“交易性金融负债”，用以反映企业因证券价格浮动而带来负债金额的变动。

2.案例说明

假设2014年10月1日沪市大盘位于3000点，甲企业预期大盘有可能进一步走低，因此，向乙证券公司融券，做空交易。甲企业融券A股票100000股，此时A股票市价10元/股，约定3个月后于2014年12月31日按年利率12％归还给A股票，同时按照股票市值的60％缴纳保证金600000元。假定2010年12月31日A股票市价8元，不考虑相关交易的手续费。

* 10月1日甲企业融券缴纳保证金、实际融券以及出售股票时的会计分录为：

　　借：其他应收款——融券保证金 　　　               600000
		贷：银行存款——自有资金 　　 　　　　        600000
		
	借：交易性金融资产——A股票融券成本              1000000
		贷：交易性金融负债——A股票融券本金          1000000

	借：其他货币资金——融券存款 　　                1000000
		贷：交易性金融资产——A股票融券成本          1000000
	
* 12月31日，A股票市价跌至8元，公允价值变动＝(10-8)*100000股＝200000元，甲企业会计分录为：
　　
	借：交易性金融负债——A股票公允价值变动           200000
		贷：公允价值变动损益——A股票                 200000
	
* 12月31日，甲企业购入100000股A企业股票归还乙证券公司，此时应冲销交易性金融负债科目余额，会计分录如下：

　　借：交易性金融资产——A股票融券成本               800000
		贷：其他货币资金——融券存款 　　　　　       800000
		
	借：交易性金融负债——A股票融券本金              1000000
		贷：交易性金融负债——A股票公允价值变动       200000
		贷：交易性金融资产——A股票融券成本           800000
		
通过“交易性金融负债”及其对应的“公允价值变动”会计科目，确认和计量融券业务因证券价格浮动而带来负债金额的变动及其收益，最终甲企业通过融券做空交易获得200000元利得，扣除融券利息费用30000元，净利润170000元。

需要注意的是，乙证券公司是逐日盯市，假如12月20日A股票的价格与甲企业预期相反，上升到15.7元，那么3万元融券利息和57万元的负债浮亏将抵消60万元保证金，如果甲企业没有追加保证金，则其证券账户中资金将会被强制平仓，购买A股票以归还乙证券公司的股票，相关会计处理如下：

借：公允价值变动损益——A股票（融券）                570000
	贷：交易性金融负债——A股票融券公允价值变动      570000
	
借：交易性金融负债——A股票融券本金 　　　          1000000
	交易性金融负债——A股票融券公允价值变动          570000
	应付利息——A股票（融券） 　　　　　　            30000
	贷：其他应收款——融券保证金 　　　　　　　　    600000
		其他货币资金——融券存款 　　　　　　　     1000000