# PyFlowUI

**PyFlowUI** is an interactive, modular workflow UI framework built using Python, ImGui, and OpenGL. It allows developers to create, manipulate, and visualize workflows and data pipelines through an intuitive and dynamic user interface. This project is especially useful for integration into larger systems like **ComfyUI**.

## Features

- **Modular Workflow Design**: Easily create and manage workflow modules with customizable input/output slots.
- **Real-time Interaction**: Move, resize, and connect modules in real-time using a drag-and-drop interface.
- **Visual Connections**: Create and manage connections between modules using dynamic Bezier curves.
- **Persistent Data Storage**: Use SQLite to store workflow data for easy retrieval and modification.
- **Customizable Interface**: Fully customizable layout and module behavior, tailored to your specific use cases.
- **High-performance Rendering**: Built on top of OpenGL for fast and responsive graphics rendering.
- **ImGui Integration**: Uses the ImGui immediate-mode GUI library for flexible, easy-to-use interfaces.

## Screenshots

![PyFlowUI Demo](https://github.com/msfocus/PyFlowUI/blob/main/demo.png)

## Getting Started

### Prerequisites

To use **PyFlowUI**, ensure you have the following dependencies installed:

- Python 3.7+
- OpenGL
- GLFW
- ImGui (with Python integration)
- Pandas
- SQLite3

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/msfocus/PyFlowUI.git
   cd PyFlowUI
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the project:

   ```bash
   python PyFlowUI.py
   ```

### Usage

Once you run the application, you’ll be presented with the **PyFlowUI** interface, where you can start adding modules, connecting them, and building your workflow.

1. Right-click to open the context menu and add a new module.
2. Drag and drop modules to rearrange them.
3. Click and drag between slots to create connections.
4. Use the **Apply** and **Clear** buttons to manage your workflow state.

## How It Works

**PyFlowUI** allows you to manage workflow modules through a simple and intuitive interface. Each module has input and output slots that you can connect to other modules to create a data flow. The workflow is rendered in real-time using OpenGL, and all data is saved in a local SQLite database for easy access and storage.

## Roadmap

- [ ] Add support for more advanced module types and interactions.
- [ ] Improve customization options for module appearance and behavior.
- [ ] Implement more efficient data handling for large workflows.
- [ ] Expand the documentation with more detailed usage examples.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or raise issues to discuss potential improvements and bug fixes.

### Steps for Contributing:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m "Add some feature"`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This project is licensed under the **GNU Lesser General Public License (LGPL)**. See the [LICENSE](./LICENSE) file for details.

### GNU Lesser General Public License (LGPL)

PyFlowUI is free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

PyFlowUI is distributed in the hope that it will be useful, but **WITHOUT ANY WARRANTY**; without even the implied warranty of **MERCHANTABILITY** or **FITNESS FOR A PARTICULAR PURPOSE**. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this program. If not, see [https://www.gnu.org/licenses/lgpl-3.0.html](https://www.gnu.org/licenses/lgpl-3.0.html).

## Acknowledgments

- Inspired by [ImGui](https://github.com/ocornut/imgui) and its powerful immediate-mode UI framework.
- Special thanks to the contributors who have helped shape this project.

