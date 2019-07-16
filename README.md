# React-Banner
The below shows How I solve the problem. I describe it in 2 (Task, Solution) or 3 (Task, Problems, Solution) steps.</br></br>
<h3>1. Infinite Scroll Loop Carousel</h3>
<blockquote>&emsp;a. How to make the first slide appear again after the last slide?</blockquote></br>
<ol>  
<li>&emsp;<strong>Reordering arrays</strong> : Set the ‘order’ to the elements inside the array ‘Company_RC’ and Identify which items have changed. Use this ‘order’ for Keys.</li></br></br>
<li>&emsp;<strong>Animation</strong> : Only shows part of Carousel</li></br></br>
<li>&emsp;<strong>Current Status</strong>  : </li></br></br>
<li>&emsp;<strong>Reference</strong>  : </br></br>
&emsp;&emsp;<a target="_blank" href="https://github.com/express-labs/pure-react-carousel/issues/60">GitHub-React Infinite Loop Issue</a></br>
&emsp;&emsp;<a target="_blank" href="https://codepen.io/MattPeck/pen/pZbWjN?editors=0010">CodePen-Carousel Fundamentals React</a>
</li>
</ol>

<blockquote>&emsp;b. How to stop slides while MouseOver?</blockquote></br>
&emsp;<strong>-Mouse Over Event</strong> : Detect mouse over event by onMouseOut() function, change class Name, and apply css ‘animation-play-state’ property as paused. </br>

<blockquote>&emsp;c. How to allow sliding to finish animation when using stop?</blockquote></br>
&emsp;<strong>-Change animation</strong> : Set animation fill-mode as forwards, iteration-count as 1, not infinite.
&emsp;<strong>-Reference </strong>  : </br></br>
&emsp;&emsp;<a target="_blank" href="https://stackoverflow.com/questions/25314215/how-to-allow-slidedown-and-slideup-to-finish-animation-when-using-stop">StackOverflow</a>

<h3>2. Next/Prev Control Buttons</h3>
<blockquote>&emsp;a. How to make the first slide appear again after the last slide?</blockquote></br>
Reordering arrays : Same as 1-a (href!!)

<h3>3. Stop on Mouse Focus</h3> : Same as 1-b	
<h3>4. Mobile Swipe Touch Slider</h3> <br/><br/>
&emsp;<strong>-Swipe Event</strong> : Detect Swipe event by onMouseDown() -> onMouseMove() -> onMouseLeave() , change class Name, and apply css ‘????’ property as paused. And detect direction in onMouseMove(). For cross-platform compatibility, onTouchStart() -> onTouchMove() ->onTouchEnd().

		
&emsp;<strong>-Reference </strong>
&emsp;&emsp;<a target="_blank" href="https://codepen.io/swingthing/pen/ZBGBJb/">Codepen - Swipe to remove the item</a>

<h3>5. Data Fetching</h3>
<blockquote>&emsp;a. How to enable CORS(Cross Origin Resource Sharing)?</blockquote></br>
Change mode : Implement fetch api in componentDidMount() and Set the mode as ‘no-cors’, however it doesn’t occur CORS error but, doesn’t send the data.


