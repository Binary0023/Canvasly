# 🖌️ Examples

Here are some example use cases for **Canvasly**.

---

## ✏️ Drawing Shapes
```javascript
// Create a rectangle
canvasly.drawRect(50, 50, 200, 100, { color: 'blue' });

// Create a circle
canvasly.drawCircle(150, 150, 75, { color: 'red' });
📝 Adding Text
javascript
Copy code
canvasly.addText("Hello, Canvasly!", {
  x: 100,
  y: 200,
  font: "20px Arial",
  color: "black"
});
🖼️ Importing an Image
javascript
Copy code
canvasly.addImage("path/to/image.png", {
  x: 50,
  y: 50,
  width: 300,
  height: 200
});
📂 Exporting Your Work
javascript
Copy code
// Save canvas as PNG
canvasly.export("png");
🚀 Try It Yourself
Check out the /examples folder for ready-to-run demos.
