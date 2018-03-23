## Use of tables and their common attributes
#### HTML code
```html
<div class="box">
		<table border="1" cellspacing="0" cellpadding="0">
    		<tr style="background-color: #FDA43A;">
    			<td colspan="8">赴德总决赛各项活动应缴付价格说明</td>
    			<!--<td style="width: 140px;"></td>
    			<td style="width: 226px;"></td>
    			<td style="width: 100px;"></td>
    			<td style="width: 120px;"></td>
    			<td style="width: 120px;"></td>
    			<td style="width: 120px;"></td>
    			<td style="width: 120px;"></td>-->
    		</tr>
    		<tr style="font-size: 22px;background-color: #f5f5f5;">
    			<td style="width: 48px;">组</td>
    			<td style="width: 140px;">出席人员</td>
    			<td style="width: 226px;">项目</td>
    			<td style="width: 100px;">天</td>
    			<td style="width: 120px;">总费用</td>
    			<td style="width: 120px;">奖金</td>
    			<td style="width: 120px;">预定费</td>
    			<td style="width: 120px;">应付款项</td>
    		</tr>
   			<tr>
 				<td rowspan="2" style="width: 48px;font-size: 22px">1</td>
    			<td style="width: 140px;">参赛学生</td>
    			<td style="width: 226px;">钢琴比赛</td>
    			<td style="width: 100px;">05</td>
    			<td style="width: 120px;">23800元</td>
    			<td style="width: 120px;">2000元</td>
    			<td style="width: 120px;">3000元</td>
    			<td style="width: 120px;">18800元</td>
    		</tr>
    		<tr>
    			<!--<td style="width: 48px;"></td>-->
    			<td style="width: 140px;">随行家长</td>
    			<td style="width: 226px;">钢琴比赛</td>
    			<td style="width: 100px;">05</td>
    			<td style="width: 120px;">20800元</td>
    			<td style="width: 120px;">--</td>
    			<td style="width: 120px;">--</td>
    			<td style="width: 120px;">20800元</td>
    		</tr>
    		<tr>
    			<td rowspan="2" style="width: 48px;font-size: 22px">2</td>
    			<td style="width: 140px;">参赛学生</td>
    			<td style="width: 226px;">钢琴比赛&文化之旅</td>
    			<td style="width: 100px;">12</td>
    			<td style="width: 120px;">32800元</td>
    			<td style="width: 120px;">2000元</td>
    			<td style="width: 120px;">3000元</td>
    			<td style="width: 120px;">27800元</td>
    		</tr>
    		<tr>
    			<!--<td style="width: 48px;"></td>-->
    			<td style="width: 140px;">随行家长</td>
    			<td style="width: 226px;">钢琴比赛&文化之旅</td>
    			<td style="width: 100px;">12</td>
    			<td style="width: 120px;">29800元</td>
    			<td style="width: 120px;">--</td>
    			<td style="width: 120px;">--</td>
    			<td style="width: 120px;">29800元</td>
    		</tr>
    		<tr>
    			<td rowspan="2" style="width: 48px;font-size: 22px">3</td>
    			<td style="width: 140px;">参赛学生</td>
    			<td style="width: 226px;">钢琴比赛文化之旅大师班</td>
    			<td style="width: 100px;">20</td>
    			<td style="width: 120px;">41800元</td>
    			<td style="width: 120px;">2000元</td>
    			<td style="width: 120px;">3000元</td>
    			<td style="width: 120px;">36800元</td>
    		</tr>
    		<tr>
    			<!--<td style="width: 48px;"></td>-->
    			<td style="width: 140px;">随行家长</td>
    			<td style="width: 226px;">钢琴比赛文化之旅大师班</td>
    			<td style="width: 100px;">20</td>
    			<td style="width: 120px;">38800元</td>
    			<td style="width: 120px;">--</td>
    			<td style="width: 120px;">--</td>
    			<td style="width: 120px;">38800元</td>
    		</tr>
    		<tr>
    			<td colspan="8" style="height: 30px;font-size: 14px;color: #FDA43A;line-height: 30px;">注：以上费用均不含签证费，得到通知后需一周内完成付款事宜!</td>
    		</tr>
    	</table>
	</div>
  ```
  #### CSS code
  ```css
  *{
			margin: 0;
			padding: 0;
		}
		.box{
			width: 980px;
			margin: 200px auto 0;
			overflow: hidden;
		}
		.box table{
			width: 976px;
			border-collapse: collapse;
			border: 1px solid #E5E5E5;
			margin-top: 20px;
		}
		.box table tr{
			font-size: 18px;
			color: #666666;
			line-height: 45px;
			text-align: center;
		}
		.box table tr td{	
			height: 45px;		
		}
