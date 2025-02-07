# My Python App

This project is a simple Python application that prints "Hello, World!" to the console. It is packaged as an AppImage for easy distribution.

## Project Structure

```
my-python-app
├── .github
│   └── workflows
│       └── build.yml
├── src
│   └── hello.py
├── appimage
│   └── AppRun
├── requirements.txt
└── README.md
```

## Getting Started

To build and run this application, follow these steps:

### Prerequisites

- Ensure you have Python installed on your system.
- Install the required dependencies listed in `requirements.txt`.

### Building the AppImage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/my-python-app.git
   cd my-python-app
   ```

2. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Build the AppImage using GitHub Actions. Push your changes to the main branch, and the workflow defined in `.github/workflows/build.yml` will automatically build the AppImage.

### Running the Application

Once the AppImage is built, you can run it by executing the generated AppImage file. Make sure to give it executable permissions:

```
chmod +x my-python-app.AppImage
./my-python-app.AppImage
```

You should see the output:
```
Hello, World!
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.