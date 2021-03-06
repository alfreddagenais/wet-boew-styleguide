---
published: true
layout: default-theme-wet-boew-en
title: Links
hide_breadcrumb: false
date_modified: 2019-04-11
---
{::nomarkdown}
{% raw %}
<!-- Links -->
<div class="row">
	<div class="mrgn-lft-md mrgn-rght-md">
		<h2 id="links" class="page-header">Links</h2>
	</div>
	<div class="col-md-4 pull-right">
		<div class="panel panel-default">
			<div class="panel-heading">
				<h4 class="panel-title">Related to success criteria</h4>
			</div>
			<div class="panel-body">
				<ul class="list-unstyled">
					<li><a href="https://www.w3.org/TR/2012/NOTE-UNDERSTANDING-WCAG20-20120103/navigation-mechanisms-skip.html" rel="external">2.4.1 Bypass Blocks</a></li>
					<li><a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-refs.html" rel="external">2.4.4 Link Purpose (In Context)</a></li>
					<li><a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-mult-loc.html" rel="external">2.4.5 Multiple Ways</a></li>
					<li><a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-descriptive.html" rel="external">2.4.6 Headings and Labels</a></li>
					<li><a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-consistent-functionality.html" rel="external">3.2.4 Consistent Identification</a></li>
					<li><a href="https://www.w3.org/TR/2012/NOTE-UNDERSTANDING-WCAG20-20120103/consistent-behavior-consistent-locations.html" rel="external">3.2.3 Consistent Navigation</a></li>
				</ul>
			</div>
		</div>
		<div class="panel panel-info">
			<div class="panel-heading">
				<h3 class="panel-title">Design guide</h3>
			</div>
			<div class="list-group"><a href="../design/headings-en.html" class="list-group-item">Headings<span class="wb-inv"> - Design guide</span> </a></div>
		</div>
		<div class="panel panel-info">
			<div class="panel-heading">
				<h3 class="panel-title">Writing guide</h3>
			</div>
			<div class="list-group"><a href="../writing/principals-en.html#heading" class="list-group-item">Heading principles- Writing guide</a> <a href="../writing/formatting-en.html#headings" class="list-group-item">Heading and subheading formatting- Writing guide</a></div>
		</div>
	</div>
	<div class="mrgn-lft-md mrgn-rght-md">
		<p>
			A link is a type of <a href="keyboard-en.html">
				<abbr title="User Interface">UI</abbr>
				control</a> that performs one or more of the following behaviours:
		</p>
		<ul>
			<li>Takes the user to another web page</li>
			<li>Jumps to another location within the same web page</li>
			<li>Performs specialized
				<abbr title="User Interface">UI</abbr>
				functionality determined by client side scripting (JavaScript)</li>
		</ul>
		<p>The link element is <code>&lt;a&gt;</code></p>
		<h3 id="lt">Link text</h3>
		<p>Provide link text inside <strong>either</strong> the:</p>
		<ul>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H30" rel="external" title="WCAG 2.0, Technique H30"><code>&lt;a&gt;</code> element</a></li>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H33" rel="external" title="WCAG 2.0, Technique H33"><code>title</code> attribute</a></li>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H30" rel="external" title="WCAG 2.0, Technique H30"><code>alt</code> attribute of any <code>&lt;img&gt;</code> element</a> within the link</li>
		</ul>
		<p>Ensure <a href="#ic">independent context</a> of link text. Additional context can be established using <strong>either</strong>:</p>
		<ul>
			<li>The <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H78" rel="external" title="WCAG 2.0, Technique H78">paragraph</a>, <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G53" rel="external" title="WCAG 2.0, Technique G53">sentence</a>, <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H77" rel="external" title="WCAG 2.0, Technique H77">list item</a>, <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H81" rel="external" title="WCAG 2.0, Technique H81">parent list item</a>, <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H79" rel="external" title="WCAG 2.0, Technique H79">table cell, or table heading enclosing the link</a>; or</li>
			<li>The <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H80" rel="external" title="WCAG 2.0, Technique H80">preceding heading element</a>.</li>
		</ul>
		<p>Use <a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G197" rel="external" title="WCAG 2.0, Technique G197">consistent link text</a> for all links which perform the same function.</p>
		<div class="alert alert-info mrgn-tp-lg">
			<p id="ic"><strong>Note:</strong> Independent context means that the purpose of the link can be determined from the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-refs.html#pdlinkcontextdef" rel="external" title="WCAG 2.0, Understanding SC 2.4.4">link text alone or other elements with a programmatically determinable relationship with the link</a>.</p>
		</div>
		<h3 id="rp">Repeated navigation links</h3>
		<p>When a group of links are repeated on multiple web pages:</p>
		<ul>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G61" rel="external" title="WCAG 2.0, Technique G61">The relative order</a> of the links must be the same on each page</li>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G1" rel="external" title="WCAG 2.0, Technique G1">A skip mechanism</a> is provided <small><em>(satisfied by default in
				<abbr title="Web Experience Toolkit">WET</abbr>
				for primary navigation)</em></small>.</li>
		</ul>
		<h3 id="sr">Finding web pages</h3>
		<p>When establishing navigation on a web site, provide <strong>either</strong> a:</p>
		<ul>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G63" rel="external" title="WCAG 2.0, Technique G63">Site map</a>, providing links to different sections of the site; or</li>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G126" rel="external" title="WCAG 2.0, Technique G126">List of links</a> to all web pages within the web site; or</li>
			<li><a href="https://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/G161" rel="external" title="WCAG 2.0, Technique G161">Search engine</a> for the site.</li>
		</ul>
		<div class="alert alert-danger mrgn-tp-lg">
			<p>
				<strong>Important:</strong> Links have additional requirements because they are a type of <a href="#ui">
					<abbr title="User Interface">UI control</abbr></a>.
			</p>
		</div>
	</div>
</div>
{% endraw %}
{:/}
