
# Environmental Science QA System
 
  
<img src="qa_image.png" width="600" height="200" title="Art made with Disco Diffusion"/>

A domain-specific QA system for answering questions about environmental issues.  
The system uses the Haystack pipeline to answer questions by querying a set of environment-related Wikipedia articles (dataset <a href=https://github.com/ekohrt/wikipedia-environmental-articles-dataset>here</a>).

## Example Output:  
  
Query: What is the main cause of deforestation in the amazon?  
Answers:  
[   {   'answer': 'cattle ranching',  
        'context': 's. Some 80% of the deforestation of the Amazon can be '  
                   'attributed to cattle ranching, as Brazil is the largest '  
                   'exporter of beef in the world. The Amazo'},  
    {   'answer': 'Consumption and production of beef',  
        'context': 'lion hectares of virgin tropical forest was lost in 2018. '  
                   'Consumption and production of beef is the primary driver '  
                   'of deforestation in the Amazon, wit'},  
    {   'answer': 'Agricultural expansion',  
        'context': 'lobally due to increasing stocks in temperate and boreal '  
                   'forest.Agricultural expansion continues to be the main '  
                   'driver of deforestation and forest fra'}]  
  
<i>This is a prototype, not for business or academic use.</i>
