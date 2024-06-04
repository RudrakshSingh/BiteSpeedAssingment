# Chatbot Flow Builder

This project is a simple Chatbot Flow Builder built using React and React Flow. It allows users to create and manage chatbot conversation flows by adding, connecting, and configuring text nodes.

## Features

1. **Text Node**:
    - Supports adding multiple text nodes in one flow.
    - Nodes can be dragged and dropped from the Nodes Panel.

2. **Nodes Panel**:
    - Contains the draggable nodes that can be added to the flow.
    - Currently supports only the Text Node.

3. **Edge**:
    - Connects two nodes together.

4. **Source Handle**:
    - Only one edge can originate from a source handle.

5. **Target Handle**:
    - Multiple edges can connect to a target handle.

6. **Settings Panel**:
    - Replaces the Nodes Panel when a node is selected.
    - Allows editing the text of the selected node.

7. **Save Button**:
    - Saves the flow.
    - Displays an error if there are more than one nodes with empty target handles.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/chatbot-flow-builder.git
    ```

2. Navigate to the project directory:
    ```bash
    cd chatbot-flow-builder
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Start the development server:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to see the application in action.


## Usage

- Drag a node from the Nodes Panel and drop it onto the canvas to add it to the flow.
- Click on a node to select it and open the Settings Panel.
- Edit the text of the selected node in the Settings Panel.
- Connect nodes by dragging from the source handle of one node to the target handle of another node.
- Click the Save Button to save the flow. An alert will notify if there are any errors.

## Deployed Link

- https://bite-speed-assingment.vercel.app/
