# Learn-0.3
## OpenCV
You  guys might've finished the previous module, [Learn-0.2](https://github.com/Training-2024/Learn-0.2), if not, make sure you finish that first!<!--first finish that and then visit this module.-->Now we are going to start with **Computer Vision** also known as OpenCV.
OpenCV<!--Cv here is Computer Vision--> is a Python library which is designed to solve computer vision problems. OpenCV was originally developed in 1999 by Intel but later it was supported by Willow Garage.
OpenCV supports a wide variety of programming languages such as C++, Python, Java etc. Support for multiple platforms including Windows, Linux, and MacOS.
OpenCV Python is nothing but a wrapper class for the original C++ library to be used with Python. Using this, all of the OpenCV array structures gets converted to/from NumPy arrays.Dont get vexed with these names 🤣 ..you will learn it once after stepping into the main content.

As <!--previously-->told in the First Module, our **Robotics Club** <!--is promoting-->encourages and expects **_SELF LEARNING_**. So you guys might have understood what to do now...

This is the the second important & essential step in this whole Training-2024 Program. <!--So-->Learning OpenCV helps you to work with many Computer Vision related real world situations. Use these resources that we have curated for you to learn OpenCV.

- [OpenCv Tutorials](https://github.com/Training-2024/Learn-0.3/tree/main/opencv_tutorials)

You can ask your doubts to the assigned mentors.
<hr/>
<h2>Task Description</h2>

<h2><a class="header" href="#b-problem-statement" id="b-problem-statement">Problem Statement</a></h2>
<ul>
<li>
<p>All the images in the <em><strong>Samples</strong></em> folder have <strong>different shapes</strong> and have <strong>only one of the three colors</strong> <em><strong>(Red, Green, Blue)</strong></em>.</p>
</li>
<li>
<p>Task is to <strong>find out the following details</strong> for each image in the manner as shown below:</p>
<ol>
<li><strong>Detect all the non-white</strong> shapes in the images.</li>
<li><strong>Store</strong> the details of the these detected shapes <strong>in a dictionary</strong> in the same order as mentioned below in form of <strong>key:value pair</strong>, where <em><strong>key</strong></em> is a <strong>string</strong> in single quotation marks and <em><strong>value</strong></em> is an <strong>array</strong> of details.
<ul>
<li><strong>{ 'Shape': ['color', Area, cX, cY] }</strong></li>
<li><em>Example</em> =&gt; <strong>{ 'Circle': ['red', 1011.0, 350, 420] }</strong></li>
</ul>
</li>
<li>It is <strong>mandatory</strong> to make sure that each of these <strong>details are of definite data type</strong> as listed below:
<ul>
<li>
<p><b><u>Key:</u></b></p>
<ul>
<li><strong>'Shape'</strong> 	 =&gt; <em>String</em> in single quotation marks, with <em><strong>only first letter capital</strong></em>, can take any one of these values: <em><strong>Circle/ Triangle/ Quadrilateral(anything with 4 sides can be displayed like this)/ Pentagon/ Hexagon</strong></em></li>
</ul>
</li>
<li>
<p><b><u>Value:</u></b></p>
<ul>
<li><strong>'color'</strong> 		=&gt; <em>String</em> in single quotation marks, with <em><strong>all letters in small caps</strong></em> can take any one of these values: <em><strong>red/ blue/ green</strong></em></li>
<li><strong>Area</strong> 		   =&gt; <em>Float</em> value up to <em><strong>one decimal point</strong></em> (area of the detected shape)</li>
<li><strong>cX</strong> 		       =&gt; <em>Int</em> value (<em><strong>centroid coordinate</strong></em> of shape on <em><strong>horizontal X-axis</strong></em> direction)</li>
<li><strong>cY</strong> 		       =&gt; <em>Int</em> value (<em><strong>centroid coordinate</strong></em> of shape on <em><strong>vertical Y-axis</strong></em> direction)</li>
</ul>
</li>
</ul>
</li>
</ol>
</li>
</ul>
<blockquote>
<p><strong>Note:</strong> </p>
<ul>
<li>
<p>Shapes could be any of these: <em>Circle/ Triangle/ Quadrilateral(anything with 4 sides can be displayed like this)/Pentagon/ Hexagon</em>. <strong>No other shape except these</strong>.</p>
</li>
<li>
<p>For <em>cX</em> and <em>cY</em> consider the <strong>top-left point of the image as origin (0, 0) reference.</strong></p>
</li>
<li>
<p>If there are multiple shapes in the image then they should be stored in <strong>decreasing order of their respective area</strong> as shown below:</p>
<ul>
<li>
<p>Example	=&gt; </p>
<p><strong>{ 'Circle' : ['red', 1011.0, 350, 420], 'Quardrilateral' : ['green', 706.0, 469, 786], 'Triangle' : ['blue', 555.0, 350, 50] }</strong></p>
</li>
</ul>
</li>
</ul>
</blockquote>
<h3><a class="header" href="#task-instructions" id="task-instructions">Task Instructions</a></h3>
<hr />
<p>Inside <em><strong>this repo</strong></em> you will find <strong>files &amp; folders</strong> as shown below:</p>
<ul>
<li><em>task2.py</em></li>
<li><em>Samples</em>
<ul>
<li><em>Sample1.png</em></li>
<li><em>Sample2.png</em></li>
<li><em>Sample3.png</em></li>
<li><em>Sample4.png</em></li>
</ul>
</li>
<li>task2_output.pdf</li>
</ul>
<p>For this part of the task we have provided a <strong>“snippet”</strong> of outline code in <strong><code>task2.py</code></strong> file:</p>
<ul>
<li>You have to modify the <strong><code>scan_image()</code></strong> function to take <strong>image file path</strong> as input and return a <strong>dictionary</strong> with <em><strong>details of non-white shapes</strong></em> detected in the image as explained above.</li>
<li>When you run the <strong><code>task2.py</code></strong>, as a default, the <strong>main()</strong> function will feed the file path of <strong>Sample1.png</strong> file which is present in the <strong>Samples</strong> folder as shown above.</li>
 <li>If u want check the code on other images change the variable <strong>img_file_path</strong> in the main function and mention the particular image name that u want to test your code on.
<li>Verify the output accuracy by referring the <strong>task2_output.pdf</strong>.</li>
</ul>
