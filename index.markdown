---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Multiple Parson's Problems on One Page
---
# Parsons Practice

## Exercise 1 (Fuel Cost)
An algorithm is required to calculate the cost of filling a tank of fuel. The user is required to enter the number of litres of fuel and the cost per litre. The program will then calculate the cost and display it.

<div id="sequence_ex1-sortableTrash" class="sortable-code"></div> 
<div id="sequence_ex1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="sequence_ex1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="sequence_ex1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "BEGIN\n" +
    "	INPUT litres\n" +
    "	INPUT rate\n" +
    "	CALCULATE cost = litres * rate\n" +
    "	OUTPUT cost\n" +
    "END";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "sequence_ex1-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#sequence_ex1-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#sequence_ex1-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## Exercise 2 (Curtain Cost)
Brian’s Curtains charge $13 per metre of material and a fixed charge of $25 when making curtains for customers. Brian requires a program to help quickly calculate the cost of a job for his customers.

<div id="sequence_ex2-sortableTrash" class="sortable-code"></div> 
<div id="sequence_ex2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="sequence_ex2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="sequence_ex2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "BEGIN\n" +
    "	INPUT material\n" +
    "	CALCULATE cost = material * 13 + 25\n" +
    "	OUTPUT cost\n" +
    "END";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "sequence_ex2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#sequence_ex2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#sequence_ex2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
## Exercise 3 (Calculate Pay)
An insurance company pays its employees a salary of $100 per week plus $15 per hour for every hour worked during the week. Create an algorithm to calculate the weekly pay for an employee.

<div id="sequence_ex3-sortableTrash" class="sortable-code"></div> 
<div id="sequence_ex3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="sequence_ex3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="sequence_ex3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "BEGIN\n" +
    "    INPUT hours\n" +
    "    CALCULATE pay = hours * 15 + 100\n" +
    "    OUTPUT pay\n" +
    "END";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "sequence_ex3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#sequence_ex3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#sequence_ex3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

### Example Next Link
[Next](./parsons/example1.html)
