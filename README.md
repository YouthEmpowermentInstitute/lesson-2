lesson-2
========
This example is all about using the jQuery Mobile framework to make the proposal you created in part one and making it into the correct format.

* Make a ‘page’ for each section of the proposal, i.e. Methodology, Goals, etc.
* At the bottom of each ‘page’ include a link to the previous page and the next page. You can use `<div data-role=”footer”>` if you like.
* Make sure that all the links work
* Don’t include the internal links from Project 1. They won’t work.

Each section of your proposal will be turned into an individual jQuery Mobile "page". You do that by wrapping it in a `div` with the `data-role=page` attribute.

Make headers by wrapping the `<h1>` in a `div` with the attribute `data-role=header`

A basic page would look like 

    <div data-role="page" id="exec-summary">
      
      <div data-role="header">
        <h1>Executive Summary</h1>
      </div><!--/header-->
      
      <div data-role="content>
        <p>The text of the executive summary</p>
        
        <a href="#needs-statement>Link to Needs Statement</a>
      </div><!--content-->
     
    </div> <!--/page-->