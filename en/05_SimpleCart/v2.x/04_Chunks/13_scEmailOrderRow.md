The scEmailOrderRow chunk is used by the [Email Configuration](../Manager/Administration/Emails) for iterating over purchased products. 

## Default scEmailOrderRow chunk

```` html
<tr>
  <td>
    [[+title]]
    [[+options:notempty=`<br />[[+options]]`]]
    [[+fields:notempty=`<br />[[+fields]]`]]
  </td>
  <td style="text-align:right;">[[+price_formatted]]</td>
  <td style="text-align:center;">[[+quantity]]</td>
  <td style="text-align:right;">[[+subtotal_formatted]]</td>
</tr>

````