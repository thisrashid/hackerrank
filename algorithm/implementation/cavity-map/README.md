<div class="content-text challenge-text mlB">
    <div class="msB">
    	<p><strong>Problem Statement</strong></p>
    </div>
    <div class="msB">
    	<p>You are given a square 
    		<span class="MathJax_Preview"></span>
    		<span class="MathJax" id="MathJax-Element-1-Frame" role="textbox" aria-readonly="true" style="">
	    		<nobr>
	    			<span class="math" id="MathJax-Span-1" style="width: 3.403em; display: inline-block;">
	    				<span style="display: inline-block; position: relative; width: 2.403em; height: 0px; font-size: 141%;">
	    					<span style="position: absolute; clip: rect(2.031em, 1000em, 2.769em, -0.334em); top: -2.64em; left: 0em;">
	    						<span class="mrow" id="MathJax-Span-2">
	    							<span class="mi" id="MathJax-Span-3" style="font-family: MathJax_Math; font-style: italic;">n</span>
	    							<span class="mo" id="MathJax-Span-4" style="font-family: MathJax_Main; padding-left: 0.222em;">×</span>
	    							<span class="mi" id="MathJax-Span-5" style="font-family: MathJax_Math; font-style: italic; padding-left: 0.222em;">n</span>
	    						</span>
	    						<span style="display: inline-block; width: 0px; height: 2.64em;"></span>
	    					</span>
	    				</span>
	    				<span style="border-left: 0em solid; display: inline-block; overflow: hidden; width: 0px; height: 0.819em; vertical-align: -0.071em;"></span>
	    			</span>
    			</nobr>
    		</span>
    		<script type="math/tex" id="MathJax-Element-1">n \times n</script> map. Each cell of the map has a value in it denoting the depth of the appropriate area. We will call a cell of the map a cavity if and only if this cell is not on the border of the map and each cell adjacent to it has <strong>strictly smaller depth</strong>. Two cells are adjacent if they have a common side.
    	</p>
		<p>You need to find all the cavities on the map and depict them with character uppercase <strong>X</strong>.</p>
		<p><strong>Input Format</strong></p>
		
		<p>The first line contains an integer 
			<span class="MathJax_Preview"></span>
			<span class="MathJax" id="MathJax-Element-2-Frame" role="textbox" aria-readonly="true" style="">
				<nobr>
					<span class="math" id="MathJax-Span-6" style="width: 0.847em; display: inline-block;">
						<span style="display: inline-block; position: relative; width: 0.591em; height: 0px; font-size: 141%;">
							<span style="position: absolute; clip: rect(1.843em, 1000em, 2.533em, -0.334em); top: -2.403em; left: 0em;">
								<span class="mrow" id="MathJax-Span-7">
									<span class="mi" id="MathJax-Span-8" style="font-family: MathJax_Math; font-style: italic;">n</span>
								</span>
								<span style="display: inline-block; width: 0px; height: 2.403em;"></span>
							</span>
						</span>
						<span style="border-left: 0em solid; display: inline-block; overflow: hidden; width: 0px; height: 0.75em; vertical-align: -0.071em;"></span>
					</span>
				</nobr>
			</span>
			<script type="math/tex" id="MathJax-Element-2">n</script> 
			<span class="MathJax_Preview"></span>
			<span class="MathJax" id="MathJax-Element-3-Frame" role="textbox" aria-readonly="true" style="">
				<nobr>
					<span class="math" id="MathJax-Span-9" style="width: 8.625em; display: inline-block;">
						<span style="display: inline-block; position: relative; width: 6.107em; height: 0px; font-size: 141%;">
							<span style="position: absolute; clip: rect(1.772em, 1000em, 3.008em, -0.261em); top: -2.64em; left: 0em;">
								<span class="mrow" id="MathJax-Span-10">
									<span class="mo" id="MathJax-Span-11" style="font-family: MathJax_Main;">(</span>
									<span class="mn" id="MathJax-Span-12" style="font-family: MathJax_Main;">1</span>
									<span class="mo" id="MathJax-Span-13" style="font-family: MathJax_Main; padding-left: 0.278em;">≤</span>
									<span class="mi" id="MathJax-Span-14" style="font-family: MathJax_Math; font-style: italic; padding-left: 0.278em;">n</span>
									<span class="mo" id="MathJax-Span-15" style="font-family: MathJax_Main; padding-left: 0.278em;">≤</span>
									<span class="mn" id="MathJax-Span-16" style="font-family: MathJax_Main; padding-left: 0.278em;">100</span>
									<span class="mo" id="MathJax-Span-17" style="font-family: MathJax_Main;">)</span>
								</span>
								<span style="display: inline-block; width: 0px; height: 2.64em;"></span>
							</span>
						</span>
						<span style="border-left: 0em solid; display: inline-block; overflow: hidden; width: 0px; height: 1.521em; vertical-align: -0.408em;"></span>
					</span>
				</nobr>
			</span>
			<script type="math/tex" id="MathJax-Element-3">(1 \le n \le 100)</script>
			, denoting the size of the map. Each of the following 
			<span class="MathJax_Preview"></span>
			<span class="MathJax" id="MathJax-Element-4-Frame" role="textbox" aria-readonly="true" style="">
				<nobr>
					<span class="math" id="MathJax-Span-18" style="width: 0.847em; display: inline-block;">
						<span style="display: inline-block; position: relative; width: 0.591em; height: 0px; font-size: 141%;">
							<span style="position: absolute; clip: rect(1.843em, 1000em, 2.533em, -0.334em); top: -2.403em; left: 0em;">
								<span class="mrow" id="MathJax-Span-19">
									<span class="mi" id="MathJax-Span-20" style="font-family: MathJax_Math; font-style: italic;">n</span>
								</span>
								<span style="display: inline-block; width: 0px; height: 2.403em;"></span>
							</span>
						</span>
						<span style="border-left: 0em solid; display: inline-block; overflow: hidden; width: 0px; height: 0.75em; vertical-align: -0.071em;"></span>
					</span>
				</nobr>
			</span>
			<script type="math/tex" id="MathJax-Element-4">n</script> lines contains 
			<span class="MathJax_Preview"></span>
			<span class="MathJax" id="MathJax-Element-5-Frame" role="textbox" aria-readonly="true" style="">
				<nobr>
					<span class="math" id="MathJax-Span-21" style="width: 0.847em; display: inline-block;">
						<span style="display: inline-block; position: relative; width: 0.591em; height: 0px; font-size: 141%;">
							<span style="position: absolute; clip: rect(1.843em, 1000em, 2.533em, -0.334em); top: -2.403em; left: 0em;">
								<span class="mrow" id="MathJax-Span-22">
									<span class="mi" id="MathJax-Span-23" style="font-family: MathJax_Math; font-style: italic;">n</span>
								</span>
								<span style="display: inline-block; width: 0px; height: 2.403em;"></span>
							</span>
						</span>
						<span style="border-left: 0em solid; display: inline-block; overflow: hidden; width: 0px; height: 0.75em; vertical-align: -0.071em;"></span>
					</span>
				</nobr>
			</span>
			<script type="math/tex" id="MathJax-Element-5">n</script> positive digits without spaces. A digit (1-9) denotes the depth of the appropriate area.
		</p>

		<p><strong>Output Format</strong></p>

		<p>Output <span class="MathJax_Preview"></span>
			<span class="MathJax" id="MathJax-Element-6-Frame" role="textbox" aria-readonly="true" style="">
				<nobr>
					<span class="math" id="MathJax-Span-24" style="width: 0.847em; display: inline-block;">
						<span style="display: inline-block; position: relative; width: 0.591em; height: 0px; font-size: 141%;">
							<span style="position: absolute; clip: rect(1.843em, 1000em, 2.533em, -0.334em); top: -2.403em; left: 0em;">
								<span class="mrow" id="MathJax-Span-25">
									<span class="mi" id="MathJax-Span-26" style="font-family: MathJax_Math; font-style: italic;">n</span>
								</span>
								<span style="display: inline-block; width: 0px; height: 2.403em;"></span>
							</span>
						</span>
						<span style="border-left: 0em solid; display: inline-block; overflow: hidden; width: 0px; height: 0.75em; vertical-align: -0.071em;"></span>
					</span>
				</nobr>
			</span>
			<script type="math/tex" id="MathJax-Element-6">n</script> lines, denoting the resulting map. Each cavity should be replaced with character <code>X</code>.
		</p>

		<p><strong>Sample Input</strong></p>

		<pre><code>4
1112
1912
1892
1234
</code></pre>

<p><strong>Sample Output</strong></p>

<pre><code>1112
1X12
18X2
1234
</code></pre>
</div>