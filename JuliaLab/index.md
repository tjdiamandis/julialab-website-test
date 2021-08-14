@def title = "Julia Lab"
@def tags = ["syntax", "code"]


~~~
				<div id="ri-grid" class="ri-grid ri-grid-size-1 ri-shadow">
					<img class="ri-loading-image" src="images/loading.gif"/>
					<ul>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
						<li><a href="#"><img src="/assets//people/corgi.jpeg"/></a></li>
					</ul>
				</div>
				

				

			

        <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
		<script type="text/javascript" src="/js/jquery.gridrotator.js"></script>
		<script type="text/javascript">	
			$(function() {
			
				$( '#ri-grid' ).gridrotator( {
					w320 : {
						rows : 4,
						columns : 6
					},
					w240 : {
						rows : 4,
						columns : 4
					},
					nochange : [],
					preventClick : false
				} );
			
			});
		</script>
~~~




<!--```julia:people.jl -->
<!--using CSV, DataFrames #hide-->

<!--println("<div class=\"masonry gutterless\">") #hide-->
<!--people = CSV.read("./_assets/people.csv", DataFrame) #hide-->
<!--for p in eachrow(people) #hide-->
<!--  if p.Role !== missing && p.Role == "Current Member" #hide-->
<!--     img_name = replace(p.Name, r" " => s"_") #hide-->
<!--     println("<div class=\"brick\">") #hide-->
<!--     println("<img class=\"circle\" src=\"./assets/people/$(img_name)\" height=\"120\">") #hide-->
<!--     println("</div>") #hide-->
<!--  end #hide-->
<!--end #hide-->
<!--println("</div>") #hide-->
<!--println("</div>") #hide-->
<!--```-->
<!--\show{people.jl}-->



~~~
<center>
<iframe width="426" height="240" src="https://www.youtube.com/embed/qGW0GT1rCvs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="426" height="240" src="https://www.youtube.com/embed/tQpqsmwlfY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="426" height="240" src="https://www.youtube.com/embed/XRJ-rtP2fVE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>
~~~

