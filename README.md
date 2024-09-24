<h1>AZ-204: Mermaid Markdown, </h1>

<h2>Azure Visitor Count App Diagram</h2>

``` Mermaid

sequenceDiagram
    participant AZ204.JFTech.info
    participant Azure_Function
    participant Azure_Cosmos_DB
    AZ204.JFTech.info->> Azure_Function: Trigger on Visit
    Azure_Function->> Azure_Cosmos_DB: Increment Visitor Count Value
    Azure_Cosmos_DB->> Azure_Function: Return New Value
    Azure_Function->> AZ204.JFTech.info: Increment Visitor Count Value in DOM


```