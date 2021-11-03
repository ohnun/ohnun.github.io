# 液压与气压传动笔记
## 1.液压传动的基本原理及组成
<details>
<summary>基本原理</summary>
<ul>
	<li>Pascal原理: 施加于密封容器内平衡液体中的某一点的压力等值地传递到全部液体的各点;</li>
	<li>液体连续性原理;</li>
	<li>能量守恒定理.</li>
</ul>
</details>
<details>
<summary>液压系统的组成</summary>
<ul>
	<li>动力元件: 输入的机械能->油液的压力能;</li>
	<li>执行元件: 油液的压力能->机械能;</li>
	<li>控制元件: 各种泵;</li>
	<li>辅助元件;</li>
	<li>工作介质.</li>
</ul>
</details>
## 2.液压动力元件
### 2.1.液压泵的性能参数
<head>
<script type="text/x-mathjax-config">
	MathJax.Hub.Config({
		tex2jax:{
			inlineMath:[['$','$'],["\\(","\\)"]],
			displayMath:[['$$','$$'],["\\[","\\]"]]
	}}
		{
		showProcessingMessages:false,
		messageStyle:"none"
	});
</script>
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=Tex-MML-AM_CHTML" async>
</script>
</head>
<details>
<summary>压力</summary>
<ul>
	<li>工作压力: 液压泵在实际工作时输出油液的压力值, 此压力值取决于系统中阻止液体流动的阻力;</li>
	<li>额定压力: 通过实验获得的可长期工作的压力值.</li>
</ul>
<mark>
<i>
压力分级: 低压不超过2.5兆帕, 中压不超过8兆帕, 中高压不超过16兆帕, 高压不超过32兆帕, 超高压超过32兆帕.
</i>
</mark>
</details>
<details>
<summary>排量与流量</summary>
<ul>
	<li>排量: 液压泵的轴转动一转时, 封闭工作容腔的容积变化量;</li>
	<li>理论流量: 在不考虑泄漏的情况下, 单位时间内所输出的液体的体积;</li>
	<li>实际流量: 泵工作时的输出流量, 需考虑泄漏量Δq;</li>
	<li>额定流量: 泵在额定转速和额定压力下输出的流量.</li>
</ul>
</details>
<details>
<summary>功率与效率</summary>
<p>
液压泵由原动机驱动, 因此其输入功率为机械功率, 输出功率为液压功率, 而总效率则是输出功率与输入功率的比值. 液压泵的功率损失由容积损失和机械损失两部分构成.
</p>
</details>
<table>
	<tr>
		<td rowspan="2">参数名称</td>
		<td colspan="2">计算公式与单位</td>
	</tr>
	<tr>
		<td>国际单位</td>
		<td>工程单位</td>
	</tr>
	<tr>
		<td>理论流量</td>
		<td>$q_t [m^3 \/s]=V[m^3 \/r]n[r\/s]$</td>
    </tr>
</table>
