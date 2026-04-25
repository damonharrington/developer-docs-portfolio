# 🌐 Developer Docs Portfolio

A technical writing portfolio showcasing API documentation, developer guides, and troubleshooting content with real world structure and examples.

---

## 🚀 Overview

This repository demonstrates my ability to create clear, structured, and developer friendly documentation. It simulates real world API documentation, focusing on usability, readability, and practical implementation.

The project includes step-by-step guides, error handling documentation, and working code examples to reflect how developers interact with APIs in production environments.

---

## 📂 Repository Structure

```
developer-docs-portfolio/
│
├── README.md
├── docs/
│   ├── getting-started.md
│   ├── troubleshooting.md
│   └── api-reference.md
│
├── examples/
│   ├── javascript-example.js
│   └── curl-examples.txt
│
└── assets/
```

---

## ⚡ Quick Start

### Base URL

```
https://api.weatherexample.com/v1
```

### Example Request

```bash
curl "https://api.weatherexample.com/v1/weather?city=Chennai&apikey=YOUR_API_KEY"
```

### Sample Response

```json
{
  "city": "Chennai",
  "temperature": 32,
  "condition": "Sunny",
  "humidity": 70
}
```

---

## 📘 Documentation

Detailed documentation is available in the `/docs` directory:

* **Getting Started Guide** – Step-by-step instructions to use the API
* **Troubleshooting Guide** – Common issues with clear solutions
* **API Reference** – Endpoints, parameters, and response formats

---

## 💻 Example Usage

### JavaScript Example

```javascript
async function getWeather(city) {
  const apiKey = "YOUR_API_KEY";
  const url = `https://api.weatherexample.com/v1/weather?city=${city}&apikey=${apiKey}`;

  try {
    const response = await fetch(url);
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.error("Error:", error);
  }
}

getWeather("Chennai");
```

---

## 🧠 Skills Demonstrated

* API documentation (requests, responses, error handling)
* Basic understanding of APIs, JSON, and web technologies
* Use of Git, GitHub, and modern documentation workflows

---

## 🎯 Purpose

This repository was created to demonstrate my ability to:

* Write clear and concise developer documentation
* Simplify complex technical concepts
* Create content aligned with real world engineering workflows

---

## 📌 Future Improvements

* Add SDK and integration guides
* Include diagrams and API flow visuals
* Expand API endpoints and use cases
* Improve documentation based on user feedback

---

## 📄 License

This project is licensed under the Company License.
