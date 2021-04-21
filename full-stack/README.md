You have to build a Full-Stack web app to calc all numeric params in a list. User will be able to see all previous queries too.

## Requirements:
- An endpoint `/calc` that receives an undetermined number of arguments and returns the sum of those arguments that are numerical (you could receive different types of data).
- A second endpoint `/history` that returns all previous calls to `/calc`.
- A form view to add several values (one per field, no limit), send them to `/calc` endpoint and, then, show the result.
- A list view with all previous queries.

## We will consider the following aspects in your code:
- Files and folders structure
- Component size
- Error handling
- Logic coupling

## Additional aspects we will consider:
- Good-looking interface
- Use local storage or Redux to store the last query between sessions
- Use Error Boundaries
- Use of Typescript
- Use of environment variables

### In case of using React:
- Don't use classes
- Use react hooks / custom hooks
- Use react redux
