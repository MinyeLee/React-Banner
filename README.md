# React-Banner
The below shows How I solve the problem. I describe it in 2 (Task, Solution) or 3 (Task, Problems, Solution) steps.</br></br>
<h3>1. Infinite Scroll Loop Carousel</h3>
<blockquote>&emsp;a. How to make the first slide appear again after the last slide?</blockquote></br>
<ol>  
<li>&emsp;<strong>Reordering arrays</strong> : Set the ‘order’ to the elements inside the array ‘Company_RC’ and Identify which items have changed. Use this ‘order’ for Keys.<br/><br/>
<img src="https://user-images.githubusercontent.com/6896920/61291280-0f842000-a809-11e9-9537-cd8d7623d287.png" height="400px"></img>

</li></br></br>
<li>&emsp;<strong>Animation</strong> : Only shows part of Carousel<br/><br/>
<img src="https://user-images.githubusercontent.com/6896920/61291468-8de0c200-a809-11e9-9d08-a080f401bc24.png" height="150px"></img><br/><br/>

<img src="https://user-images.githubusercontent.com/6896920/61291541-b9fc4300-a809-11e9-87ee-1362afa50592.png" height="140px"></img>
</li></br></br>
<li>&emsp;<strong>Current Status</strong>  : </li></br></br>
<li>&emsp;<strong>Reference</strong>  : </br></br>
&emsp;&emsp;<a target="_blank" href="https://github.com/express-labs/pure-react-carousel/issues/60">GitHub-React Infinite Loop Issue</a></br>
&emsp;&emsp;<a target="_blank" href="https://codepen.io/MattPeck/pen/pZbWjN?editors=0010">CodePen-Carousel Fundamentals React</a>
</li>
</ol>

<blockquote>&emsp;b. How to stop slides while MouseOver?</blockquote></br>
<ol>
<li>&emsp;<strong>Mouse Over Event</strong> : Detect mouse over event by onMouseOut() function, change class Name, and apply css ‘animation-play-state’ property as paused. 
	
<img src="https://user-images.githubusercontent.com/6896920/61291612-f2038600-a809-11e9-9524-8a75d17383e1.png" height="35px"></img><br/><br/>
<img src="https://user-images.githubusercontent.com/6896920/61291682-25461500-a80a-11e9-9e46-b7b02f5fc37b.png" height="50px"></img>
</li></br>
</ol>
<blockquote>&emsp;c. How to allow sliding to finish animation when using stop?</blockquote></br>
<ol>
<li>&emsp;<strong>Change animation</strong> : Set animation fill-mode as forwards, iteration-count as 1, not infinite.<br/><br/>
<img src="https://user-images.githubusercontent.com/6896920/61291800-7a822680-a80a-11e9-9406-5dadac6a2560.png" height="150px"></img>	
</li>
<li>&emsp;<strong>Reference </strong>  : </br></br>
&emsp;&emsp;<a target="_blank" href="https://stackoverflow.com/questions/25314215/how-to-allow-slidedown-and-slideup-to-finish-animation-when-using-stop">StackOverflow</a></li>
</ol>
<h3>2. Next/Prev Control Buttons</h3>
<blockquote>&emsp;a. How to make the first slide appear again after the last slide?</blockquote></br>
<ol>
	<li>&emsp;<strong>Reordering arrays</strong> : Same as 1-a </li>
</ol>
<h3>3. Stop on Mouse Focus</h3> : Same as 1-b	
<h3>4. Mobile Swipe Touch Slider</h3> <br/><br/>
<ol>
<li>&emsp;<strong>Swipe Event</strong> : Detect Swipe event by onMouseDown() -> onMouseMove() -> onMouseLeave() , change class Name, and apply css property as paused. And detect direction in onMouseMove(). For cross-platform compatibility, onTouchStart() -> onTouchMove() ->onTouchEnd().</li>

		
<li>&emsp;<strong>Reference  </strong>:</br></br>
&emsp;&emsp;<a target="_blank" href="https://codepen.io/swingthing/pen/ZBGBJb/">Codepen - Swipe to remove the item</a></li>
</ol>
<h3>5. Data Fetching</h3>
<blockquote>&emsp;a. How to enable CORS(Cross Origin Resource Sharing)?</blockquote></br>
<ol>
<li>&emsp;<strong>Change mode</strong> : Implement fetch api in componentDidMount() and Set the mode as ‘no-cors’, however it doesn’t occur CORS error but, doesn’t send the data.</li><br/><br/>
<img src="https://user-images.githubusercontent.com/6896920/61291799-7a822680-a80a-11e9-98b8-147c0db2a277.png" height="140px"></img>	
	
</ol>

