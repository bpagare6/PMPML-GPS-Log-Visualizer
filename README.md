# PMPML-GPS-Log-Visualizer
COEP Hackathon Project on Pune Open Data of PMPML GPS Logs of 8 days 19/01/2019-27/01/2019

Problem Statement: To Visualize the GPS Logs of PMPML and make animation of it.

Approach:
	1. First Extract the given dataset from tar.gz file
	2. Make the clear Data Set by removing the irrelevent part
	3. Filter the Data Set with respect to One PMPML route-id
	4. Then Sorted the New Data Set as per Time Frame
	5. Plotted each point on the Google Map
	6. Then Created the Animation from it

To get started first install <a href="https://www.anaconda.com/distribution/">Anaconda<a>. Then run jupyter notebook,
<div class="highlight-bash nottranslate">
	<div class="highlight">
		jupyter-notebook
	</div>
</div>

And then complete the setup by running,
<div class="highlight-bash nottranslate">
	<div class="highlight">
		pip install -r requirements.txt
	</div>
</div>

To run this on Your System first <a href="https://drive.google.com/uc?id=1-kiz85TvxyHuZsSCDjGtP0IMH56v-uxN&export=download">Download the Dataset Here.<a>

This idea can be further be taken to finding out the traffic distribution over the city and understanding vehicle movements in city area.
