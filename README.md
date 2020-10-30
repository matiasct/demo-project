# Demo Project

As part of the hiring process, We want you to deliver a small code project following the best coding practices. 
You will use this repository to present your work. Feel free to update this readme for us to start and test the application before code evaluation. Backend should use Express.js, and Frontend should use React.js.

## Functional Requirements:

The main functionality should be the ability to display a line chart with data provided in data.json (further specified at data structure section).
Line chart must show on axis Y the corresponding average sensor reading and should have the ability to be zoomed by level of detail on axis X. For example yo could use the following X axis ranges:
      20 minutes of data
      1 hour of data
      2 hours of data

## Data structure
#### **`data.json`**
The Json file contains ~6 hours of sensor reading data.
```typescript
{
   [x: string]:{ //iterative number
      "timestamp": number,  //unix timestamp in miliseconds - link to https://www.unixtimestamp.com/
      "i": number//reading 
    }
}
```

## Other Requirements:

- Each api call should be optimized according the selected level of detail.
- Project must be testeable.
- Don't repeat yourself.
- Keep it simple
