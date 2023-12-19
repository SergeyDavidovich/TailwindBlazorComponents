# TailwindBlazorComponents
### The solution is intended for development, testing and demo using of Razor components in Blazor project
___ 
### Project - ControlsCollection 
- controls development
- nuget packages creation and publish
#### Terminal compilation string (sample):
```
npx tailwindcss -i ./Styles/tailwind.css -o ./wwwroot/dist/tailwind.css --watch
npx tailwindcss -i ./Card.razor.css -o ./wwwroot/input/input.css --watch
```
#### Project links:
[Generating Tailwind CSS output on a per-component basis](https://stackoverflow.com/questions/76831269/generating-tailwind-css-output-on-a-per-component-basis?noredirect=1&lq=1)
****

### Project - TestControlsCollection
- has dependency of ControlsCollection project
- intended for in product controls testing
***
### Project - UsingControlsCollection
- has no dependency of ControlsCollection project
- injects Nuget package of ControlsCollection,
- intended for controls using demonstration

