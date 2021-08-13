# People

<!--```julia:people.jl -->
<!--using CSV, DataFrames #hide-->
<!--people = CSV.read("./_assets/people.csv", DataFrame) #hide-->
<!--println("<div class=\"people-container\">") #hide-->
<!--for p in eachrow(people) #hide-->
<!--  if p.Role !== missing && p.Role == "Current Member" #hide-->
<!--     img_name = replace(p.Name, r" " => s"_") #hide-->
<!--     println("<div class=\"people\"> <img class=\"circle\" src=\"./assets/people/$(img_name)\" width=\"100\" height=\"100\">  $(p.Name) </div>") #hide-->
<!--  end #hide-->
<!--end #hide-->
<!--println("</div>") #hide-->
<!--```-->


~~~
<div class="masonry gutterless">
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
      <div class="brick">
        <img width="100" hight="100" src="/assets/people/Alan_Edelman" alt="Alan Edelman" title="Alan Edelman">
      </div>
</div>
~~~




~~~
<div class="people-container">
~~~



<!--~~~-->
<!--```julia:people.jl -->
<!--using CSV, DataFrames #hide-->
<!--people = CSV.read("./_assets/people.csv", DataFrame) #hide-->
<!--for p in eachrow(people) #hide-->
<!--  if p.Role !== missing && p.Role == "Current Member" #hide-->
<!--     img_name = replace(p.Name, r" " => s"_") #hide-->
<!--     println("<div class=\"people\"> <img class=\"circle\" src=\"./assets/people/$(img_name)\" width=\"100\" height=\"100\">  $(p.Name) </div>") #hide-->
<!--  end #hide-->
<!--end #hide-->
<!--println("</div>") #hide-->
<!--```-->
~~~
</div>
~~~


\show{people.jl}
