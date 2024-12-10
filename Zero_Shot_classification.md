
In this classification, the title is classified into an industry without giving any possible classes/groups. GPT selects the class based on the title. The prompt to select the classes are as follows

System:
You are an excellent industry specialist. You will be given a title of a paper. Please classify the title text to a recommended industry class.
Output format:
{
  "explanation": "<one sentence explanation for choosing the category>",
  "categories": "<category chosen>"
}

User:
Title of the paper
