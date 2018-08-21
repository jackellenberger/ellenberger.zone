---
layout: about
title: Jack
site_name: 'Jack Ellenberger'
favicon: assets/images/jack_favicon.ico
landing-title: 'Jack Ellenberger'
description: Software Engineer at Braintree. BS in CS and Statistics from the University of Chicago
permalink: /jack
image: assets/images/iceland.jpg
nav-menu: true
front-page: true
---


<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>The top line</h2>
		</header>
		<p>
			I am a software engineer currently based in Chicago, working at <a href="https://www.braintreepayments.com/careers">Braintree Payments</a>	 on API integrity, site reliability, a bit of dev ops, and a smattering of open source problem solving.
			<br/>
			<br/>
			You might know me from my greatest hits, <a href="https://www.braintreepayments.com/">braintreepayments.com</a>, <a href="https://www.developers.braintreepayments.com/">braintree's developer docs</a>, and <a href="https://www.developer.paypal.com/">PayPal's developer docs.</a>
			<br/>
			<br/>
			Find me spreding knowledge around the 'net on <a href="https://stackoverflow.com/users/5261045/jellenberger">Stackoverflow</a> and <a href="https://github.com/jackellenberger?tab=overview">GitHub</a>
		</p>
		<ul class="actions">
			<li><a href="/resumes/jack/ellenberger.pdf" class="button icon fa-download">Take this, you might need it</a></li>
		</ul>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic08.jpg" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Experience</h3>
				</header>
				<p>
<h4>Braintree Payments</h4>
<h5>Software Engineer  June 2016 - Present</h5>
<li> Maintained the Braintree and PayPal developer docs and marketing sites, while working with technical writers to expand and improve functionality.  Rewrote Braintree's federated site search to use a custom parser and Algolia front end to serve tens of thousands more useful results. Streamlined release processes while eliminating downtime, implementing nginx caching, and reducing AWS asset storage load by 97%. Secured form inputs against attack via backend validation and captcha.</li>
<br/>

<li> Integrated new features into the C++, Java, Ruby, Python, .NET, PHP, and Node server SDKs including porting .NET to .NET Core compatibility. Wrote tools to allow seamless migration of sensitive customer any payment information to and from Braintree, leveraging awk regular expressions. Improved Jenkins testing for multiple projects, expanding usefulness for non-technical users while surfacing specifically identified issues to developers, and bringing version controlled CI to PayPal projects. Helped to Dockerize development and release of multiple services using legacy Capistrano processes as well as Kubernetes. Made additions to Jenkins and Docker Ruby DSL's for use on our team and others. Wrote shim into exiting core to enable GraphQL endpoints. Wrote thorough API validation tests to ensure nothing went undocumented.</li>
<br/>

<li> Co-founded Python Tutorial group to encourage technical literacy among Braintree Support employees, provided one on one mentorship for interns, and forced Slack to paginate their emoji page via excessive use.</li>
<br/><br/>


<h4>Revenew Inc.</h4>
<h5>Operations Administrator & Technologist Intern  Summer 2015</h5>
<li> Wrote scripts and queries for Piwik Analytics to decrease analysis duration of 14,000+ tracked sites by a factor of 120x while collaborating with creators and users. Edited existing code base to allow for secure SSH access from .NET webapp to Ruby scripts. Designed database and storage procedures to maintain Financial Services data in cloud-based WORM compliant manner. Created automated testing environment to ensure that latency is minimized and reliability is guaranteed for a non URI routable platform. Created sample webpage to demonstrate ability to cobrand video, rendering on demand. Created procedure for duplicating and migrating Wordpress sites automatically, updated existing templates and plugins, and implemented okta single sign-on.</li>
<br/><br/>


<h4>Land O'Lakes Inc.</h4>
<h5>Project Management & Application Development Intern  Summer 2013 and 2014</h5>
<li> Created iOS sample for a secure, internal crisis management app, oversaw its development by an offshore team, composed documentation and test scripts. Wrote tool chain to increase readability of scanned data. Implemented ELMAH system to report client side API errors to developers. Performed code maintenance and extensions on projects from previous internship.</li>
<br/>

<li> Designed and implemented public-facing API and UI for approved milk producers to archive milk quality data sets, as well as for regulators and third parties to audit. Wrote SQL calls to manage login and communication logging. Created scripts to facilitate cleaning of old data. Extended location API to allow for more useful queries.</li>
<br/><br/>

<h4>University of Chicago</h4>
<h5>Humanities Computing Technician  October 2012 - June 2016</h5>
<li> Conducted Tier 1 & 2 technical support directly with Faculty and Staff of the University to identify hardware and software issues and to resolve them with minimal loss of data or time. Performed on site repairs, basic data recovery, and documentation management tasks.</li>
				</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic09.jpg" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Education</h3>
				</header>
<script>
window.onload = function () {

var chart = new CanvasJS.Chart("chartContainer", {
	title:{
    	text: "University of Chicago", 
    	fontFamily: "Source Sans Pro"      
	},
    subtitles: [{
    	text: "Chicago IL, October 2012 - June 2016",
    	fontFamily: "Source Sans Pro"      		
    }],
	animationEnabled: true,
	zoomEnabled: true,
	backgroundColor: null,
	theme: 'dark1',
	axisX: {
		title:"Relevance",
		interval: 16,
		minimum: -15,
		maximum: 15,
		gridThickness:1,
		tickLength: 0,
		lineThickness: 0,
		labelFormatter: function() {
		  return " ";
		}
	},
	axisY:{
		margin:10,
		title: "Interest",
		interval: 16,
		minimum: -15,
		maximum: 15,
		gridThickness:1,
		tickLength: 0,
		lineThickness: 0,
		labelFormatter: function() {
		  return " ";
		}
	},
	data: [{
		type: "bubble",
		showInLegend: true,
		legendText: "Strength",
		legendMarkerType: "circle",
		legendMarkerColor: "grey",
		toolTipContent: "{name}",
		fillOpacity: 0.6,
		dataPoints: [
		{ x: 6, y: 6, z: 2, name: "Computer Security" },
		{ x: 5, y: 9, z: 6, name: "Computer Graphics" },
		{ x: 6, y: 8, z: 5, name: "Computer Architecture" },
		{ x: 7, y: 5, z: 6, name: "Computational Linguistics" },
		{ x: 9, y: 5, z: 7, name: "Mobile Computing" },
		{ x: 9, y: 4, z: 8, name: "Algorithms" },
		{ x: 5, y: 7, z: 8, name: "Compilers I" },
		{ x: 6, y: 6, z: 5, name: "Discrete Mathematics" },
		{ x: 4, y: 9, z: 7, name: "Operating Systems" },
		{ x: 6, y: 7, z: 3, name: "Complexity Theory" },
		{ x: 7, y: 5, z: 3, name: "Programming Languages" },
		{ x: 4, y: 5, z: 5, name: "Machine Learning I" },
		{ x: 5, y: 6, z: 8, name: "Networks & Distributed Systems" },
		{ x: 8, y: 3, z: 4, name: "Formal Languages" },
		{ x: 4, y: 2, z: 5, name: "Computer Systems I" },
		{ x: 3, y: 0, z: 7, name: "Honors Intro to Comp Sci I-II" },
		{ x: 0, y: -2, z: 7, name: "Biotechnology" },
		{ x: -1, y: 8, z: 9, name: "Digital Fabrication" },
		{ x: 3, y: 5, z: 8, name: "Scientific Visualization" },
		{ x: -4, y: 4, z: 8, name: "Digital Biology" },
		{ x: -5, y: -4, z: 5, name: "Calculus I-III" },
		{ x: -6, y: 9, z: 6, name: "Analysis & Linear Algebra" },
		{ x: -9, y: 1, z: 4, name: "Honors Mechanics" },
		{ x: 100, y: 100, z: 20, name: "weighter"}
		]
	}]
});
chart.render();
}
</script>
<div id="chartContainer" style="margin: 0 auto; height: 400px; width: 400px;"></div>
<script src="https://canvasjs.com/assets/script/canvasjs.min.js"></script>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic10.jpg" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Skills</h3>
				</header>
				<p>
					<li>Jenkins/Continuous Integration,</li> 
					<li>API design,</li>
					<li>Full stack site maintenance</li>
					<li>Pair programming,</li>
					<li>Unix/Linux systems,</li>
					<li> Android & iOS,</li>
					<li>Web development,</li>
					<li>Application Programming,</li>
					<li>Vim,</li>
					<li>Project Management,</li>
					<li>Parser design,</li>
					<li>Low-Level Programming,</li>
					<li>Database design & management,</li>
					<li>Azure systems management,</li>
					<li>High traffic Piwik instances,</li>
					<li>Wordpress templates & plugins,</li>
					<li>MVC RESTful APIs,</li>
					<li>Regular Expressions,</li>
					<li>git, svn, and tfs</li>
				</p>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic10.jpg" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Languages</h3>
				</header>
				<p>
					Ruby, Python, Node/Js, Java, C#.Net, C++, Arduino/C, Bash/Zsh, SQL, Linq, R
					<br/><br/>
					Working Knowledge: Objective-C, OpenGL / GLSL, Haskell, SML, Assembly (6502 & x86), PHP, Perl, Yacc, awk, sed, G-code
				</p>
			</div>
		</div>
	</section>
</section>

<!-- Experience Banner -->
<section id="banner" class="style4">
	<div class="inner">
		<span class="image">
			<img src="assets/images/iceland.jpg" alt="">
		</span>
		<header class="major">
			<h1>Projects</h1>
		</header>
		<div class="content">
			Here's what I've been up to, broken down roughly by context
		</div>
	</div>
</section>
<section id="two" class="spotlights">
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic08.jpg" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>@Home</h3>
				</header>
				<p>
<br/><br/><h5>Phyllo.apk</h5> A location based distributed information sharing app (mySQL, Django, Java). 
<br/><br/><h5>ellenberger.zone</h5> A personal website with subdomains for each of my family members.
<br/><br/><h5>FossFazor</h5> A 3D printed waveguide for Orthodynamic headphones based off the Audeze model. 
<br/><br/><h5>MuLtiplication</h5> A Python interface for radioligand binding assays to determine solubility of novel and published Dopamine D2 receptor-like ligands to be used by the Newman Group at the NIH.
<br/><br/><h5>ShowProdDehydron</h5> A 3D viewer for Dehydron distribution in proteins in Python.
<br/><br/><h5>oGrocer</h5> An app to crowdsource current food price trends and give consumers complete price knowledge about what to buy where.
<br/><br/><h5>Gerrymeleon</h5> A GPGPU project in its infancy to calculate and solve Efficiency Gap problems.
				</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic08.jpg" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>For Work/Open Source</h3>
				</header>
				<p>
					At a few of my workplaces implemented a <a href="https://www.inc.com/adam-robinson/google-employees-dedicate-20-percent-of-their-time-to-side-projects-heres-how-it-works.html">"20% time"</a> work structure, where a day every other week (or wherever you could fit it in) would be devoted to personal projects. These are those projects
<br/><br/><h5>Slack Yaml Manager</h5> A hybrid slack bot and standalone program to allow users to execute arbitrary code using configurations generated through slack commands.
<br/><br/><h5>html-to-text</h5> Improved upon existing design to better handle complex tables.
<br/><br/><h5>YamlLineNumbers</h5> A lightweight library to surface source line numbers in parsed ruby hashes.
<br/><br/><h5>Awesome-o</h5> A stateless Slackbot for parsing Trello boards, and tracking opensource issues. 
				</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="generic.html" class="image">
			<img src="assets/images/pic09.jpg" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>@University</h3>
				</header>
				<p>
					<li>Implemented PintOS kernel (C)</li>
					<li>TCP Protocol (C)</li>
					<li>FLang Compiler (SML)</li>
					<li>Optical Character Recognition (Python)</li>
					<li>Ray tracing (C)</li>
					<li>Protein Data Mining (Python)</li>
					<li>HMM for linguistic analysis (Python)</li>
					<li>TEC based 3D Ice Printer (G-Code/C++)</li>
				</p>
			</div>
		</div>
	</section>
</section>

<section id="banner" class="style5 minor">
	<div class="inner">
		<span class="image">
			<img src="assets/images/iceland.jpg" alt="">
		</span>
		<ul class="actions">
			<li><a href="https://www.linkedin.com/in/jack-ellenberger-149134b4/" class="button next">Link Me In</a></li>
		</ul>
	</div>
</section>

</div>


