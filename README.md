# Pure PHP Framework
A Lite Framework for PHP

# The Idea:

I am using pure php to develop web application for more than 5+ years, I have also used frameworks like Laravel and CI, but the flexibility and performance that pure php provides is way better and with enough practice way faster to develop and that too without worrying about version changes, clients get way stable product and nearly hassle free use. But if you have developed using pure php for a long time, you know that you already have classes or libraries of code that you have reused a lot. You use that as your small lite framework, I do it too. But after talking to many developers I found that we actually need to have a standard development process with some basic functionality and with a structure. I believe with the help of each other we can come up with a framework which uses pure php, but provides libraries that can help us develop faster and better. A lite and simple framework but powerful enough to get anything done.


# The Structure:

I don’t like MVC, yes it helps you focus on problem and its solution more than focusing on coding and errors, but that's not the best way to go according to me. When projects are small there is no need to use frameworks and when projects are big and complex, frameworks just make it more complex due to their structure, execution and patterns. 

I believe we should come up with new structure, where all database related operations are handled separately just like Model in MVC, but Model fails in dealing with very complex queries and when you have many joins, we need more hybrid Model more like a DataManager where you can execute simple query just by passing values and table name( DM->add(‘tablename’, $argArray); ), but it gives you freedom to create your own method to execute complex queries.

Controller is the logical part of MVC, but it includes your logic, data management after its fetched and serve it to View for displaying. But again it fails in micro managing your logic, when you are dealing with a very big complex project, like say an ERP, you would rather distribute your projects into small parts, this helps you execute project in a better way. 

 

    

