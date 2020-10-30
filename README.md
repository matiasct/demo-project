# Demo Project
As part of the hiring process, We want you to deliver a small code project following the best coding practices. 
You will use this repository to present your work. Feel free to update this readme for us to start and test the application before code evaluation. Backend should use Express.js, and Frontend should use React.js.
# Functional Requirements:

The main functionality should be the ability to display a line chart with data provided in data.json (further specified at data structure section).
Line chart should have he hability to be zoomed in by level of detail (minute/hour/day).

# Data structure
data.json
```jsonc
{
   "iterative":{
      "timestamp": number, //milliseconds 
      "i": number//reading
    }
}
```

# Other Requirements:
The project must be extensible within the main workflow. i.e., leave logging of who is sending which messages.
