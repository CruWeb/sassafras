---
layout: default
title: Getting Sass Installed
page-class: page--installation
---

<header class="page__header">
	<h1  class="page__title">{{page.title}}</h2>
</header>
<section class="section__block">
<div class="section__content">
<p class="strong">
	There are a few ways to get up and running:
</p>

<ol  class="bolded--numbers">
	<!-- Command Line -->
	<li class="command-line">
		<h3 class="h6  lead--heading">Command Line</h3>
	
		<!-- Operating Systems -->
		<!-- Mac -->
		<dl class="command-line__mac">
			<dt  class="weight--semibold">Mac</dt>
			<dd>It is very easy to get up and running on a Mac. If you prefer the command line then it will be a very quick process. Sass has a Ruby dependency but for those using a Mac, Ruby comes pre-installed.</dd>
		</dl>
		<!-- end .command-line__mac -->
	
		<!-- Linux -->
		<dl class="command-line__linux">
			<dt  class="weight--semibold">Linux</dt>
			<dd>If you are using a distribution of Linux you will first need to install Ruby. You can install Ruby throught the apt package manager, rbenv, or rpm.</dd>
		</dl>
		<!-- end .command-line__mac -->
	
		<!-- Windows -->
		<dl class="command-line__windows">
			<dt  class="weight--semibold">Windows</dt>
			<dd>To get up and running with Windows you will first need to install Ruby. The fastest way to do this is to use the  <a href="http://www.rubyinstaller.org/">Ruby Installer</a>.  This is a one-click installation process that will get verything set up for you lickity split. </dd>
			<dd>The installer will also install a Ruby command line powershell application that will let you use the Ruby libraries.</dd>
		</dl>
		<!-- end .command-line__mac -->
	
		<!-- The Installation -->
		<dl class="command-line__install">
			<dt  class="weight--semibold">Install Sass</dt>
			<dd>
				<p>Here is the quickest way to get going using the command line:</p>
				<ol>
					<li>
						<p><strong>Open up the command line application.</strong> On a Mac this will be the Terminal.app which is installed by default. It is located in the "Utilities" folder</p>
					</li>
					<li>
						<p><strong>Run the installation.</strong> Ruby uses gems to manage its packages of code. Sass is one of these packages. In your terminal window type:</p>
					
						{% highlight bash %} gem install sass {% endhighlight %}
					
						<p>This will install Sass and any other packages needed to run the program. If you get an error message then it is likely you will need to use the <code  class="sh">sudo</code> command to install the gem. This would look like:</p>
					
						{% highlight bash %} sudo gem install sass {% endhighlight %}
					
					</li>
					<li>
						<p><strong>Double-check.</strong> Sass should now be installed but it never hurts to make sure. In your terminal windo type:</p>
					
						{% highlight bash %} sass -v {% endhighlight %}
					
						<p>You should see something like <code class="sh">Sass 3.2.12 (Media Mark)</code></p>
						<p> Congratulations! You've successfully installed Sass.</p>								
					</li>
				</ol>
			</dd>
		</dl>
		<!-- end .command-line__install -->
	
	</li>
	<!-- end .command-line -->

	<!-- GUI Applications -->
	<li class="applications">
		<h3 class="h6  lead--heading">Applications</h3>
		<p>There are a good many of applications that will also allow you to get up and running in a few minutes. You can download most for free but some of them are paid apps <small>(but are totally worth it)</small></p>
		<div class="grid">
			<div class="grid__item  one-whole  lap--one-half  desk--one-half">
				<ul class="feature-list__paid">
					<strong>Paid</strong>
					<li>
						<a href="http://incident57.com/codekit/">CodeKit</a>
					</li>
					<li>
						<a href="http://compass.kkbox.com/">Compass.app</a>
					</li>
					<li>
						<a href="http://hammerformac.com/">Hammer</a>
					</li>
					<li>
						<a href="http://livereload.com/">LiveReload</a>
					</li>
					<li>
						<a href="http://mixture.io/">Mixture</a>
					</li>
					<li>
						<a href="http://alphapixels.com/prepros/">Prepros Pro</a>
					</li>
				</ul>
			</div><!--
		 --><div class="grid__item  one-whole  lap--one-half  desk--one-half">
				<ul class="feature-list__free">
					<strong>Free</strong>
					<li>
						<a href="http://koala-app.com/">Koala</a>
					</li>
					<li>
						<a href="http://alphapixels.com/prepros/">Prepros</a>
					</li>
					<li>
						<a href="http://mhs.github.io/scout-app/">Scout</a>
					</li>
				</ul>
			</div>
		</div>
	</li>
	<!-- end .applications -->
</ol>

<div class="next-lesson">
	<a href="/sass-basics/">
		<h5>Next in your learning material: </h5>
		<h4>
			<small>Lesson 2</small>
			The Basics
		</h4>
	</a>
</div>

<aside class="credit">
	<p>Information on installation and recommended applications obtained from <a href="http://sass-lang.com/">sass-lang.com</a></p>
</aside>



</div>
</section>
