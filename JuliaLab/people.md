# Current members

~~~
<div class="people-container">
        {{for name in current_members}}
          <div class="people">
            <center>
            <img class="circle" width="100" height="100" src="/assets/people/{{name}}"/><br>
            {{name}}
            </center>
          </div>
        {{end}}
</div>
~~~

# Collaborators

~~~
<div class="people-container">
        {{for name in collaborators}}
          <div class="people">
            <center>
            <img class="circle" width="100" height="100" src="/assets/people/{{name}}"/>
            {{name}}
            </center>
          </div>
        {{end}}
</div>
~~~
