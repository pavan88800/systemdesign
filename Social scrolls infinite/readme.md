## 🚀 Social Media System design

## Topics:-

1. Rendering a Large List:-

2. Infinite Scrolling and Pagination:-

3. Handling Live video commenting

4. Resource Optimization

---

## What you mean rendering a Large List

When you try to render a large dataset all at once in your UI (for example, thousands of posts, comments, or images), the browser has to:

- Create many DOM elements.

- Handle layout calculations for each element.

- Manage memory for these elements.

This leads to:
✔ Slow rendering
✔ Janky or laggy while scrolling
✔ High memory consumption
✔ Poor user experience

---

✅ Solution: Render Only What’s Needed Using Virtualization
