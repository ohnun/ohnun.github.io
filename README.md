# 液压与气压传动笔记
<body>
	<h2>1.液压传动的基本原理及组成</h2>
	<h3>基本原理</h3>
		<button type="button" onclick="alert('施加于密封容器内平衡液体中的某一点的压力等值地传递到全部液体的各点.')">帕斯卡原理
		</button>
		<button type="button" onclick="alert('由于理想流体的不可压缩性, 而且流体不会穿过流管的壁, 即质量在运动过程中守恒.')">液体连续性原理
		</button>
		<button type="button" onclick="alert('一般表述为: 能量既不会凭空产生, 也不会凭空消失, 它只会从一种形式转化为另一种形式,或者从一个物体转移到其它物体, 而能量的总量保持不变. 也可以表述为: 一个系统的总能量的改变只能等于传入或者传出该系统的能量的多少. 总能量为系统的机械能、热能及除热能以外的任何内能形式的总和.')">能量守恒定律
		</button>
	<h3>液压系统的组成</h3>
		<ul>
			<li>动力元件: 输入的机械能->油液的压力能;</li>
			<li>执行元件: 油液的压力能->机械能;</li>
			<li>控制元件: 各种泵;</li>
			<li>辅助元件;</li>
			<li>工作介质.</li>
		</ul></body>
<body>
	<h2>2.液压动力元件</h2>
	<h3>2.1.液压泵的性能参数</h3>
	<h4>压力</h4>
		<ul>
			<li>工作压力: 液压泵在实际工作时输出油液的压力值, 此压力值取决于系统中阻止液体流动的阻力;</li>
			<li>额定压力: 通过实验获得的可长期工作的压力值.</li>
		</ul>
		<button type="button" onclick="alert('低压不超过2.5兆帕, 中压不超过8兆帕, 中高压不超过16兆帕, 高压不超过32兆帕, 超高压超过32兆帕.')">压力分级
		</button>
	<h4>排量与流量</h4>
		<ul>
			<li>排量: 液压泵的轴转动一转时, 封闭工作容腔的容积变化量;
			<table>
			<tr><td>泵的类型</td><td>排量</td></tr>
			<tr><td>齿轮泵</td><td><math><mi>V</mi><mo>=</mo><mn>6.66</mn><mi>z</mi><msup><mi>m</mi><mn>2</mn></msup><mi>B</mi></math></td></tr>
			<tr><td>双作用叶片泵</td>
				<td><math>
					<mi>V</mi><mo>=</mo>
					<mn>2</mn><mi>B</mi>
					<mo>[</mo>
					<mi>&pi;</mi>
					<mo>(</mo><msup><mi>R</mi><mn>2</mn></msup><mo>-</mo><msup><mi>r</mi><mn>2</mn></msup><mo>)</mo>
					<mo>-</mo>
					<mo>(</mo><mi>R</mi><mo>-</mo><mi>r</mi><mo>)</mo><mo>/</mo><mi>cos</mi><mi>&theta;</mi><mo>&sdot;</mo><mi>b</mi><mi>Z</mi>
					<mo>]</mo>
					</math></td></tr>
			<tr><td>单作用叶片泵</td>
				<td><math>
					<mi>V</mi><mo>=</mo>
					<mn>2</mn><mi>&pi;</mi><mi>D</mi><mi>B</mi><mi>e</mi>
					</math></td></tr>
			<tr><td>径向柱塞泵</td>
				<td><math>
					<mi>V</mi><mo>=</mo>
					<mi>&pi;</mi><msup><mi>d</mi><mn>2</mn></msup><mo>/</mo><mn>4</mn>
					<mo>&sdot;</mo>
					<mn>2</mn><mi>e</mi><mi>Z</mi>
					</math></td></tr>
			<tr><td>轴向柱塞泵</td>
				<td><math>
					<mi>V</mi><mo>=</mo>
					<mi>&pi;</mi><msup><mi>d</mi><mn>2</mn></msup><mo>/</mo><mn>4</mn>
					<mo>&sdot;</mo>
					<mi>D</mi><mi>tan</mi><mi>&gamma;</mi><mi>Z</mi>
					</math></td></tr>
				</table></li>
		<li>理论流量: 在不考虑泄漏的情况下, 单位时间内所输出的液体的体积,<mark><math><msub><mi>q</mi><mi>t</mi></msub><mo>=</mo><mi>V</mi><mi>n</mi></math></mark>;</li>
		<li>实际流量: 泵工作时的输出流量, 需考虑泄漏量Δq,<mark><math><mi>q</mi><mo>=</mo><msub><mi>q</mi><mi>t</mi></msub><msub><mi>&eta;</mi><mi>pv</mi></msub></math></mark>;</li>
		<li>额定流量: 泵在额定转速和额定压力下输出的流量.</li>
	</ul>
	<h4>功率与效率</h4>
	<p>
	液压泵由原动机驱动, 因此其输入功率为机械功率, 输出功率为液压功率, 而总效率则是输出功率与输入功率的比值. 液压泵的功率损失由容积损失和机械损失两部分构成.
	</p>
	<table>
		<tr><td>理论转矩</td><td>
			<math>
				<msub><mi>T</mi><mi>i</mi></msub><mo>=</mo>
				<mi>&Delta;p</mi><mi>V</mi>
				<mo>/</mo>
				<mn>2</mn><mi>&pi;</mi>
				</math></td></tr>
		<tr><td>实际转矩</td><td></td></tr>
		<tr><td>输入功率</td><td></td></tr>
		<tr><td>输出功率</td><td></td></tr>
		<tr><td>容积效率</td><td></td></tr>
		<tr><td>机械效率</td><td></td></tr>
		<tr><td>总效率</td><td></td></tr>
	</table>
</body>
