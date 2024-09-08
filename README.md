# first one

### Challenge: Integrating p5.js Sketches with React

#### Objective

Create a React application that integrates a p5.js sketch from an external JavaScript file. The sketch should be modular and separate from the React application logic.

#### Requirements

1. **Setup**: Set up a basic React application using Create React App (CRA).

2. **Directory Structure**: Organize the project with the following structure:
   ```
   /src
     /sketches
       mySketch.js
     /components
       P5Canvas.js
     /utils
       P5Wrapper.js
     App.js
     index.js
   ```

3. **Sketch Implementation**:
   - **`sketches/mySketch.js`**: Define and export `setup` and `draw` functions for a p5.js sketch. The sketch should use p5.js features like `createCanvas`, `background`, `lights`, `noStroke`, and `orbitControl`.
   - **`components/P5Canvas.js`**: Create a React component that integrates the p5.js sketch using a wrapper function. This component should render the canvas where the sketch is displayed.
   - **`utils/P5Wrapper.js`**: Implement a wrapper function to initialize p5.js with the provided `setup` and `draw` functions from the external sketch file.

4. **React Integration**:
   - **`App.js`**: Use the `P5Canvas` component to display the p5.js sketch within the React application.

5. **Bonus**:
   - Add a control in the React application to change the color of the background in the p5.js sketch.

#### Detailed Instructions

1. **Initialize the Project**:
   - Create a new React project using Create React App.

2. **Create Files**:
   - Create the directory structure as specified.
   - Implement the p5.js sketch in `mySketch.js` with the functions `setup` and `draw`.

3. **Implement Wrapper**:
   - In `P5Wrapper.js`, write a function to create and configure a p5.js instance with the provided setup and draw functions.

4. **Create the Canvas Component**:
   - In `P5Canvas.js`, create a React component that utilizes the p5 wrapper to render the sketch.

5. **Integrate with React**:
   - In `App.js`, include the `P5Canvas` component to display the p5.js sketch.

6. **Testing**:
   - Ensure the sketch runs correctly within the React application.
   - Confirm that the directory structure is maintained as specified.

#### Time Limit

- **1 Hour**

#### Evaluation Criteria

- **Code Quality**: Clean, well-organized, and modular code.
- **Correctness**: Correct implementation of p5.js sketch and React integration.
- **Adherence to Instructions**: Proper directory structure and functionality as described.
- **Bonus**: Bonus points for additional features or improvements.

---

This challenge will assess the candidate's ability to work with p5.js and React, focusing on modularity, integration, and understanding of the project structure. It’s a good test of both their JavaScript skills and their ability to structure code effectively.
