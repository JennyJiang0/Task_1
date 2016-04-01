This is tasks for ife.baidu.task. 
Thanks.

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
		<title>JennyJiang_task_1_1_1</title>
	</head>

	<body>
  	<div class="wrap">
  			<h1>网站一级标题</h1>
  			<!-- 无序排列 -->
  			<ul>
					<li><a href="#">导航链接一</a></li>
					<li><a href="#">导航链接二</a></li>
				</ul>
				<!-- 有序排列-->
				<ol>
					<li>排名1</li>
					<li>排名2</li>
					<li>排名3</li>
				</ol>
				<!-- &span 空格-->
				<span>文章作者</span>&nbsp;<span>文章发表时间</span>
				<!-- 回车-->
				<br />
				<strong>这里有个粗体字</strong>
				<a href="http://ife.baidu.com" target="_blank">这里有一个链接点击后打开新窗口链接到http://ife.baidu.com</a>
				<img src="img.jpg" />
				<!-- 以表格方式排列输出-->
				<table>
  				<tbody>
    				<tr>
    				  <td>好看的图片<br /><img src="img.jpg"/></td>
    				</tr>
    				<tr>
    				  <td>好看的图片<br /><img src="img.jpg"/></td>
    				</tr>
  				</tbody>
				</table>
				<!-- 有边框的表格-->
				<table border="1px">
					<thead>
  					<tr>
  					<th>表头</th><th>表头</th><th>表头</th>
  					</tr>
					</thead>
					<tbody>
					  <tr>
  					<td>表内容单元格</td><td>表内容单元格</td><td><a href="#">操作</a></td>
  					</tr>
  					<tr>
  					<td>总计</td><td colspan="2">1000</td>
  					</tr>
					</tbody>
				</table>
				<!-- form 表格 -->
				<form method="post" action="#">
					...
						<td><label for="ad">请输入邮箱地址：</label></td>
						<td><input type="text" id="ad" placeholder="这是一个文本输入框" name="adress" /></td>
						...
						<td><label for="sex">性别：</label></td>
						<td><input type="radio" id="sex" value="男" name="male" checked />男<input type="radio" value="女" name="female" /></td>
						...
						<td><label for="city">城市：</label></td>
						<td><select id="city">
							<option value="beijing" id="city">北京</option>
							<option value="shanghai">上海</opiton>
							<option value="guangzhou">广州</option>
							<option value="shenzhen">深圳</option>
							</select></td>
						...
						<td><label for="sport">爱好：</label></td>
						<td><input type="checkbox" value="sport" name="sport" id="sport" />运动<input type="checkbox" value="style" name="style" />艺术<input type="checkbox" value="science" name="science" />科学</td>
						...
						<td><label for="des">个人描述：</label></td>
						<td><textarea rows="6" cols="60" id="des" placeholder="这是一个多行输入框，输入您的个人描述"></textarea></td>
					...
					<input type="submit" value="确认提交" id="button_s" />
				</form>
				
	<p>版权所有&copy;</p>
