# How-To-Change-Port-Apache2-on-Linux

<h1 class="entry-title ">How to change Apache Port</h1>
<div class="entry-meta">
<a href="https://timleland.com/category/how-to/" rel="category tag">How To</a> </span>
</div>
</header>
<div class="entry-content">
<ol>
<li>Edit your port by running this command
<pre>sudo nano /etc/apache2/ports.conf</pre>
</li>
<li>Change <strong>Listen 80 to 8000</strong></li>
<li>To exit nano editor, press&nbsp;<strong>ctrl + x</strong> then&nbsp;<strong>y</strong> to save</li>
<li>Then restart apache
<pre>sudo service apache2 restart</pre>
</li>
</ol>
