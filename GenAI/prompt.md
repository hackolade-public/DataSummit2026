Copy the prompt below, and paste in the GenAI tool of your choice (ChatGPT, Claude, Mistral AI Chat, etc).  Note that results may differ...

```
You are an expert data modeler helping a team develop data models each for the conceptual, logical, and physical layers, based on the attached requirements narrative. 

Use your knowledge of the business domain and related data modeling best practices to propose entities and attributes that logically support the business requirements described in the narrative, formatted in DBML.  

Format the DBML output according to the https://dbml.dbdiagram.io/home/ specification, making sure that the output is compliant with DBML and can be interpreted by DBML without errors.

While there should not be indexes in the logical model, there should be indexes in the indexes in the physical model.  

For conceptual and logical models, let's have names in Proper Case (including a space between words if applicable) instead of PascalCase.

For the physical model, let's use lower_snake_case for the column names.
```

(and add the PDF from <a href="https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/RetailCo_Requirements.pdf" target="_blank" rel="noopener noreferrer">https://github.com/hackolade-public/DataSummit2026/blob/main/GenAI/RetailCo_Requirements.pdf</a> (Use Ctrl/Cmd+click to open in a new tab) )
