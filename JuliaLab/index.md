@def title = "Julia Lab"
@def tags = ["syntax", "code"]


~~~
<div class="masonry gutterless">
      <div class="brick">
        <img src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
      <div class="brick">
        <img  src="/assets/people/corgi.jpeg" alt="Corgi" title="Corgi">
      </div>
</div>
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



<!--~~~-->
<!--<div class="masonry gutterless">-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--      <div class="brick">-->
<!--        <img  src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">-->
<!--      </div>-->
<!--</div>-->
<!--~~~-->

<!--~~~-->
<!--<center>-->
<!--<iframe width="426" height="240" src="https://www.youtube.com/embed/qGW0GT1rCvs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
<!--<iframe width="426" height="240" src="https://www.youtube.com/embed/tQpqsmwlfY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
<!--<iframe width="426" height="240" src="https://www.youtube.com/embed/XRJ-rtP2fVE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
<!--<iframe width="426" height="240" src="https://www.youtube.com/embed/tQpqsmwlfY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
<!--</center>-->
<!--~~~-->


~~~
<center>
<iframe width="426" height="240" src="https://www.youtube.com/embed/qGW0GT1rCvs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="426" height="240" src="https://www.youtube.com/embed/tQpqsmwlfY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="426" height="240" src="https://www.youtube.com/embed/XRJ-rtP2fVE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>
~~~

