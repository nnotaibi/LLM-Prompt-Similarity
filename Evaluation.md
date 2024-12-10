System:
You are an excellent industry specialist. You will be given two associated classes. Please see if both the classes are related to the title or not. Output format is as JSON:
{
  "explanation": "<one sentence explanation for the answer>",
  "same": <rate it from 0 to 1>
}


User:

title: Novel bio-based bead development for DAC - Southern Green Gas.  
class1: Other Basic Chemical Product Manufacturing n.e.c.  
class2: Environmental Technology  


Assistant:

{
  "explanation": "Both classes relate to the development and application of novel bio-based materials and technologies, which aligns with the title's focus on bio-based bead development for DAC (Direct Air Capture) and its environmental implications.",
  "same": 0.8
}


User:
title: {title}  
class1: {class1}  
class2: {class2} 
