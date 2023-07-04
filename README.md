# Exercise 07 - tempConversion

Write two functions that convert temperatures from Fahrenheit to Celsius, and vice versa:

```
convertToCelsius(32) // fahrenheit to celsius, should return 0

convertToFahrenheit(0) // celsius to fahrenheit, should return 32
```

Because we are human, we want the result temperature to be rounded to one decimal place: i.e., `convertToCelsius(100)` should return `37.8` and not `37.77777777777778`.

This exercise asks you to create more than one function so the `module.exports` section of the spec file looks a little different this time. Nothing to worry about, we're just packaging both functions into a single object to be exported.
