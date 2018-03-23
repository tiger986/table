## Use of tables and their common attributes
#### HTML code
```html
<div class="box">
    <table border="1" cellspacing="0" cellpadding="0">
    	<tr style="background-color: #FDA43A;">
    	    <td colspan="8">The activity should pay the price description</td>
    	    <!--<td style="width: 140px;"></td>
    	    <td style="width: 226px;"></td>
    	    <td style="width: 100px;"></td>
    	    <td style="width: 120px;"></td>
    	    <td style="width: 120px;"></td>
    	    <td style="width: 120px;"></td>
            <td style="width: 120px;"></td>-->
    	</tr>
    	<tr style="font-size: 22px;background-color: #f5f5f5;">
    	    <td style="width: 48px;">Group</td>
    	    <td style="width: 140px;">Attendees</td>
    	    <td style="width: 226px;">Project</td>
    	    <td style="width: 100px;">Day</td>
    	    <td style="width: 120px;">Total cost</td>
            <td style="width: 120px;">Bonus</td>
    	    <td style="width: 120px;">Reservation fee</td>
    	    <td style="width: 120px;">Payables</td>
    	</tr>
   	<tr>
 	    <td rowspan="2" style="width: 48px;font-size: 22px">1</td>
    	    <td style="width: 140px;">Students</td>
    	    <td style="width: 226px;">Piano Competition</td>
    	    <td style="width: 100px;">05</td>
    	    <td style="width: 120px;">23800</td>
    	    <td style="width: 120px;">2000</td>
    	    <td style="width: 120px;">3000</td>
    	    <td style="width: 120px;">18800</td>
    	</tr>
    	<tr>
    	    <!--<td style="width: 48px;"></td>-->
    	    <td style="width: 140px;">Accompanying parents</td>
    	    <td style="width: 226px;">Piano Competition</td>
    	    <td style="width: 100px;">05</td>
    	    <td style="width: 120px;">20800</td>
    	    <td style="width: 120px;">--</td>
    	    <td style="width: 120px;">--</td>
    	    <td style="width: 120px;">20800</td>
    	</tr>
    	<tr>
    	    <td rowspan="2" style="width: 48px;font-size: 22px">2</td>
    	    <td style="width: 140px;">Students</td>
    	    <td style="width: 226px;">Cultural Tour</td>
    	    <td style="width: 100px;">12</td>
    	    <td style="width: 120px;">32800</td>
    	    <td style="width: 120px;">2000</td>
    	    <td style="width: 120px;">3000</td>
    	    <td style="width: 120px;">27800</td>
    	</tr>
    	<tr>
    	    <!--<td style="width: 48px;"></td>-->
    	    <td style="width: 140px;">Accompanying parents</td>
    	    <td style="width: 226px;">Cultural Tour</td>
    	    <td style="width: 100px;">12</td>
    	    <td style="width: 120px;">29800</td>
    	    <td style="width: 120px;">--</td>
    	    <td style="width: 120px;">--</td>
    	    <td style="width: 120px;">29800</td>
    	</tr>
    	<tr>
    	    <td rowspan="2" style="width: 48px;font-size: 22px">3</td>
    	    <td style="width: 140px;">Students</td>
    	    <td style="width: 226px;">Master class</td>
    	    <td style="width: 100px;">20</td>
    	    <td style="width: 120px;">41800</td>
    	    <td style="width: 120px;">2000</td>
    	    <td style="width: 120px;">3000</td>
    	    <td style="width: 120px;">36800</td>
    	</tr>
    	<tr>
    	    <!--<td style="width: 48px;"></td>-->
    	    <td style="width: 140px;">Accompanying parents</td>
    	    <td style="width: 226px;">Master class</td>
    	    <td style="width: 100px;">20</td>
    	    <td style="width: 120px;">38800</td>
    	    <td style="width: 120px;">--</td>
    	    <td style="width: 120px;">--</td>
    	    <td style="width: 120px;">38800</td>
    	</tr>
    	<tr>
    	    <td colspan="8" style="height: 30px;font-size: 14px;color: #FDA43A;line-height: 30px;">
	        Note: the payment will be completed within a week after the notice!
	    </td>
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
