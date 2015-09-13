# Free-code-camp
useful things for my learning 


// how to have a docuent ready as soon as the browser is \\
<script>
$(document).ready(function() {
});
</script>
// Div's hold instructions on what the eliments iside need todo aswell as seperating the elements!!

<div class="container-fluid">

// h3 is a type or eliment just like h1, h2 ect, note how the class must be within the <h3/>
and the text must be in between these with a closeing statment after the chosen text.

  <h3 class="text-primary text-center">jQuery Playground</h3>
  
  <div class="row">
  
// you can create coloums by useing the below
    <div class="col-xs-6">
    
    // you can see the left well function below moves this to the left side of the screen
      <h4>#left-well</h4>
      
      //  you can see here that the below has an id for the left well so it only targets the items withhin the div
      <div class="well" id="left-well">
        <button class="btn btn-default target" id="target1">#target1</button>
        <button class="btn btn-default target" id="target2">#target2</button>
        <button class="btn btn-default target" id="target3">#target3</button>
      </div>
    </div>
    <div class="col-xs-6">
      <h4>#right-well</h4>
      <div class="well" id="right-well">
        <button class="btn btn-default target" id="target4">#target4</button>
        <button class="btn btn-default target" id="target5">#target5</button>
        <button class="btn btn-default target" id="target6">#target6</button>
      </div>
    </div>
  </div>
</div>
