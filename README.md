# Interactive Quadratic Curve Explorer

This project is an HTML-based tool that allows users to visualize and interact with quadratic equations.

## Features

- **Visualize Quadratic Equations:** Display one or two quadratic equations of the form `y = ax² + bx + c`.
- **Dynamic Coefficient Adjustment:** Use sliders to change the `a`, `b`, and `c` coefficients for each curve and see the graph update in real-time.
- **Real-time Equation Display:** View the mathematical equation as it changes with the coefficients.
- **Dual Curve Comparison:** Enable or disable a second curve for comparative analysis.
- **Adjustable Step Increments:** Toggle between integer or decimal step increments for the coefficient sliders.
- **Automatic & Manual Zoom:**
  - Automatically zoom and center the graph on the vertex of the primary curve.
  - Manually adjust the zoom level.
- **AI-Powered Explanations (Optional):**
  - Input a Gemini API key to receive AI-generated explanations about:
    - The characteristics of the primary curve (direction, vertex, y-intercept, shape).
    - The roots of the primary curve (calculated using the quadratic formula, with explanations of the discriminant and graphical interpretation).

## How to Use

1. Open the `quadratic_explorer.html` file in a web browser.
2. Use the sliders to adjust the coefficients `a`, `b`, and `c` for "Curve 1".
3. Observe the graph and the equation updating in real-time.
4. Optionally, enable "Curve 2" and adjust its coefficients for comparison.
5. Use the "Integer Steps" checkbox to change the precision of the sliders.
6. Use the "Auto Zoom" checkbox or the manual zoom slider to adjust the view.
7. To get AI-powered explanations:
   - Enter your Gemini API Key in the designated input field.
   - Click the "Explain Curve 1" or "Explain Roots of Curve 1" buttons.

## Technologies Used

- HTML
- JavaScript
- Tailwind CSS

## Setup

No special setup is required. Simply download the `quadratic_explorer.html` file and open it in your browser. For the AI features, a Gemini API key is needed.

## Future Enhancements (Ideas)

- Displaying x-intercepts (roots) directly on the graph.
- Showing the axis of symmetry.
- Allowing users to input equations directly.
- More advanced analytical features.

## Contributing

Contributions are welcome! Please feel free to fork the repository and submit pull requests.
