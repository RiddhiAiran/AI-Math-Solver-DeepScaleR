# 🧮 AI-Powered Math Solver with DeepScaleR

This project uses **DeepScaleR** via **Ollama** and a **Gradio UI** to solve complex math problems—symbolic, algebraic, calculus, and more. Everything runs locally, with no API costs or internet needed.

---

## 🚀 Features

- ✅ Step-by-step math solutions using DeepScaleR
- ✅ Local inference with Ollama (no cloud required)
- ✅ Simple, interactive web interface built with Gradio
- ✅ Fast, secure, and private

---

## 📦 Requirements

- [Python 3.8+](https://www.python.org/)
- [Ollama](https://ollama.com) (installed and running)
- Gradio (`pip install gradio`)
- Ollama Python bindings (`pip install ollama`)

---

## 🛠️ Setup Instructions

### 1. Install Ollama
Download and install from: [https://ollama.com](https://ollama.com)

Pull the model:

```bash
ollama pull deepscaler
```

### 2. Clone the Repository

```bash
git clone https://github.com/riddhiairan/ai-math-solver-deepscaler.git
cd ai-math-solver-deepscaler
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
python app.py
```

---

## 📁 File Structure

```
├── app.py                  # Main Gradio application
├── requirements.txt        # Required Python packages
├── README.md               # Project documentation
```

---

## 📸 Preview

A simple textbox interface that provides solutions to math problems via DeepScaleR.
<img width="820" alt="Deepscaler" src="https://github.com/user-attachments/assets/87ac7828-a8d5-4bbf-804e-5f2f8c9339da" />

---

## 🙌 Credits

- Model: [DeepScaleR via Ollama](https://ollama.com/library/deepscaler)
- UI: [Gradio](https://gradio.app)
- Course: *Mastering DeepScaleR* by Vivian Aranha

---

## 📄 License

MIT License
