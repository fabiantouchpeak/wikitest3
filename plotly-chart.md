<!-- TITLE: PLOTLY CHART -->
<!-- SUBTITLE: A quick summary of New Page -->

# PLOTLY TEST CHART

<head>
               <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
</head>


<div id="tester" style="width:1000px;height:500px;"></div>
<script>
	TESTER = document.getElementById('tester');
	Plotly.plot( TESTER, [{
	x: [1, 2, 3, 4, 5],
	y: [1, 2, 4, 8, 16] }], {
	margin: { t: 0 } } );
</script>


