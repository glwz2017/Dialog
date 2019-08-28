# Dialog
js 超轻量级,弹窗插件

无依赖任何插件,直接引入即可

Usages用法
<script src="js/diyDialog.js"></script>


Parameters参数

<table>
<thead>
<tr>
<th align="center">param</th>
<th align="center">function</th>
<th align="center">default</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">style</td>
<td align="center">弹窗风格</td>
<td align="center">
  <p>'msg'</p>
  <p>'tips'</p>
  <p>'confirm'</p>
  </td>
</tr>
<tr>
<td align="center">hideTitle</td>
<td align="center">是否隐藏标题</td>
<td align="center"><em>false</em></td>
</tr>
<tr>
<td align="center">title</td>
<td align="center">弹窗标题文字</td>
<td align="center">Title</td>
</tr>
<tr>
<td align="center">time</td>
<td align="center">msg 信息提示时长</td>
<td align="center">3000</td>
</tr>
<tr>
<td align="center">content</td>
<td align="center">弹窗内容</td>
<td align="center">
  <p>可接受标签 或者 拼接字符串</p>
  <p>示例1：$('#app').html() </p>
  <p>示例2："<div>我是弹窗内容</div>" </p>
  </td>
</tr>
<tr>
<td align="center">area</td>
<td align="center">弹窗大小</td>
<td align="center">['650px','auto']</td>
</tr>
<tr>
<td align="center">confirmBtn</td>
<td align="center">确认按钮</td>
<td align="center">确定</td>
</tr>
<tr>
<td align="center">cancelBtn</td>
<td align="center">取消按钮</td>
<td align="center">取消</td>
</tr>
<tr>
<td align="center">onBeforeShow</td>
<td align="center">弹窗显示前的回调函数</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">onShow</td>
<td align="center">弹窗显示后的回调函数</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">onBeforeClosed</td>
<td align="center">关闭弹窗前的回调函数</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">onClosed</td>
<td align="center">弹窗关闭后的回调函数</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">onClickConfirmBtn</td>
<td align="center">点击确定按钮的回调函数</td>
<td align="center"></td>
</tr>
<tr>
<td align="center">onClickCancelBtn</td>
<td align="center">点击取消按钮的回调函数</td>
<td align="center"></td>
</tr>
</tbody>
</table>
