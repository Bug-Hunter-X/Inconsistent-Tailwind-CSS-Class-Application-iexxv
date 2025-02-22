# Inconsistent Tailwind CSS Class Application

This repository demonstrates a bug where Tailwind CSS classes are not consistently applied.  The issue is inconsistent application of styles, even with seemingly correct class names.

## Bug Report

The following code snippet demonstrates the issue.  The text within the div should be white, but it is not consistently rendered that way across different browsers or build processes:

```javascript
// bug.js
<div class="bg-red-500 p-4">
  <p class="text-white">This text should be white.</p>
</div>
```

## Solution

The solution involves double checking the Tailwind configuration and build process. Make sure that the styles are being correctly compiled and applied.

See `bugSolution.js` for a possible solution and steps to reproduce.