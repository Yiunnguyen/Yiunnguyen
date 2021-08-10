	<style>
		.foo {
			color: red;
			font-weight: bold;
		}
	</style>
	<script>
		Function changeContent(s) {
		{
			Document.getElementByid(content").innerhtml = "Xin chào các bạn! Tôi là <span class="foo">" + s  </span>! Chúc các bạn thi tốt!";
		}
	</script>
</head>
<body>
	<table width="500" align="center" border="1" cellpadding="8">
		<tr>
			<td align="center">
				<div id="content">Click vào các nút bên dưới để xem kết quả!</div>
			</td>
		</tr>
		<tr>
			<td align="center">
				<button onclick="ChangeContent(this.textContent);">Chiến</button> - 
				<button onclick="ChangeContent(this.textContent);">Thắng</button>
			</td>
		</tr>
	</table>
