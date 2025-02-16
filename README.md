# Data Science Project

A containerized data science application built with Python, featuring data analysis, visualization, and machine learning capabilities.

## 🛠️ Technologies Used

- Python 3.12
- Docker
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- Faker (for data generation)
- uvicorn (for serving the application)

## 🚀 Getting Started

### Prerequisites

- Docker installed on your system
- Git (optional)

### Installation

1. Clone the repository (or download the source code):
   ```bash
   git clone <repository-url>
   cd tds5
   ```

2. Build the Docker image:
   ```bash
   docker build -t ds-project .
   ```

3. Run the container:
   ```bash
   docker run -p 8000:8000 ds-project
   ```

The application will be available at `http://localhost:8000`

## 📂 Project Structure

```
tds5/
├── Dockerfile
├── README.md
└── app.py
```

## 🔧 Configuration

The application runs on port 8000 by default. You can modify this in the Dockerfile or when running the container.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
