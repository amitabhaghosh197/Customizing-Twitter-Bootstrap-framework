Customizing-Twitter-Bootstrap-framework
=======================================

Customizing Twitter Bootstrap framework other than 940px width

========================================================================

The container width of bootstrap.css is 940px. 
ANd that of bootstrap-responsive.css is 1170px.

Now the question arises if my container width is 960px;

Then in your base .css write additional code for container div:--

 .container
{
    
    max-width:960px;
    margin-left:auto;
    margin-right:auto;}

Be it noted to customize the container width according to your width (for responsive view)
always code for container div in css like above e.g. for 940px width mention max-width:940px; for 980px mention max-width:980px and so on

It organizes the container to 960px or 940px or 980px; 

Remember to call both the css files (bootstrap.css and bootstrap-responsive.css) in head.

In html instead of writing <div class=”row”> always write <div class=”row-fluid”> to get the responsive grid.

Example: https://c9.io/amitabha197/bootstrap-resize

Resource: http://twitter.github.io/bootstrap/examples/marketing-narrow.html# 
