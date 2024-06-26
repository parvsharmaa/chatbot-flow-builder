A React application built with [React Flow](https://reactflow.dev/) and [Next.js](https://nextjs.org/).

### Check out the deployed application [here](https://chatbot-flow-builder-puce.vercel.app/) on Vercel
![ChatBot Flow App](<Screenshot 2024-05-17 at 10.37.27 PM.png>)
Deployment Link : https://chatbot-flow-builder-puce.vercel.app/

# Setup and Run Project

1. run `npm install` inside the root directory, to install dependencies.
2. run `npm run dev` to start the project on the localhost.


# Features:

1. **Text Node** 
    1. Our flow builder currently supports only one type of message (i.e Text Message).
    2. There can be multiple Text Nodes in one flow.
    3. Nodes are added to the flow by dragging and dropping a Node from the Nodes Panel.
2. **Nodes Panel** 
    1. This panel houses all kind of Nodes that our Flow Builder supports.
    2. Right now there is only Message Node, but we’d be adding more types of Nodes in the future so make this section extensible 
3. **Edge**
    1. Connects two Nodes together
4. **Source Handle**
    1. Source of a connecting edge 
    2. Can only have **one edge** originating from a source handle
5. **Target Handle** 
    1. Target of a connecting edge
    2. Can have **more than one edge** connecting to a target handle 
6. **Settings Panel**
    1. Settings Panel will replace the Nodes Panel when a Node is selected
    2. It has a text field to edit text of the selected Text Node
7. **Save Button**
    1. Button to save the flow 
    2. **Save button press will show an error if there are more than one Nodes and more than one Node has empty target handles**